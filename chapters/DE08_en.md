## Implement filters to limit which fields are returned by the API (send just the data the consumer need).

### Identifiers

| API Green Score |  V1  |  V2  |  V3  |
|:-------:|:----:|:----:|:----:|
|   DE08   | 1  |   |      |

### Categories

| Lifecycle |  Resources  |  Responsible  |
|:---------:|:----:|:----:|
| Design | Network/Compute/Storage | API Producer |

### Indications

| Priority Level |      Implementation Difficulty      |  Ecological Impact Level   |
|:-------------------:|:-------------------------:|:---------------------:|
| tbd | tbd | tbd |

|Saving Resources                                           |
|:----------------------------------------------------------:|
|network / compute / storage    |

### Description

It often happens that the implementation of filters in the APIs allowing to return only the necessary data to the consumers are forgotten or not efficient. 

This forces API consumers to make generic requests that retrieve unnecessary amounts of information, resulting in overconsumption of bandwidth and storage.

It is recommended to design and implement filters that allow the user to limit the amount of data returned to optimize network and storage consumption.



### Example
For instance, we want to know the postal addresses of stores in a city. Originally, the service does not provide filtering on the search endpoint, so each time we want to know the addresses we fetch _all_ addresses and _then_ filter the ones in the city. The API can potentially transfer a huge amount of useless data.
 
 With figures:
 - the service has 1000 addresses, representing 22kB of data for each query
 - we want to filter for a city that only has 30 stores, making 1.3kB of data
 - this represents 20kB useless data
 - for an endpoint requested 500k times per day, this is 10GB of useless data transfered daily.
 
 Here is a simple setup:
 ```java
 @GetMapping
 public ResponseEntity<List<String>> getAddresses(@RequestParam(defaultValue = "") String filter) {
   return ResponseEntity.ok(addresses
     .stream()
     .filter(a -> a.contains(filter));
 }
 ```
This can be used by a simple request: `GET <base_url>/addresses?filter=Marseille`

### Validation principle

true of false
