## Use cache to avoid useless requests and preserve compute resources.

### Identifiers

| API Green Score |  V1  |  V2  |  V3  |
|:-------:|:----:|:----:|:----:|
|   DE02   | 1  |   |      |

### Categories

| Lifecycle |  Resources  |  Responsible  |
|:---------:|:----:|:----:|
| Design | Network/Compute/Storage | API Producer |

### Indications

| Priority Level |      Implementation Difficulty      |  Ecological Impact Level   |
|:-------------------:|:-------------------------:|:---------------------:|
| tbd | tbd | tbd |

||Saving Resources                                           |
|:----------------------------------------------------------:|
|network / compute / storage    |

### Description

The use of a cache has become common in computer architectures to store frequently used information on a fast storage.

In addition to improving the response time of APIs, and therefore the consumer's experience of the service, it also saves computational resources by avoiding executing the same query on the same data multiple times. 

It is recommended to place a cache in front of each brick of an architecture returning data (API, database, frontend application, ...) and close to the users to preserve compute resources and improve performances of the API.



### Example
TBD 

### Validation principle

true of false