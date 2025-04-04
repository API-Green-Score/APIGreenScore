## Prefer smallest format for exchange (JSON instead of XML)

### Identifiers

| API Green Score |  V1  |  V2  |  V3  |
|:-------:|:----:|:----:|:----:|
|   DE01   | 1  |   |      |

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

One of the structuring questions when designing an API is the selection of the exchange format to use. If the choice is often made by technical constraints or personal affinities, the durability aspect is also to be taken into account.

Indeed, there are exchange formats that are heavier than others. For example, JSON is smaller than XML. The second format will therefore have a stronger impact on the network, the computing and the storage.

In the interest of sustainability, we recommend to use a lighter exchange format to reduce the bandwidth consumed for the requests, the compute and storage resources consumption used to process and store the payloads.

### Example
For instance, this HTTP request `GET https://openlibrary.org/search.json?q=harry potter` returns a JSON value. We can convert it to XML and compare the sizes.

```java
String responseBody = new RestTemplate().getForEntity(url, String.class).getBody();

ObjectMapper objectMapper = new ObjectMapper();
JsonNode jsonNode = objectMapper.readTree(responseBody);

String xmlValue = new XmlMapper().writeValueAsString(jsonNode);
xmlPayloadSize = xmlValue.getBytes().length;

// since the XML serialized value does not contain indentation,
// we also re-serialize the JSON value without indentation
// so it is a fair comparison.
String jsonValue = objectMapper.writeValueAsString(jsonNode);
jsonPayloadSize = jsonValue.getBytes().length;		
```

Here is the result:
```json
{
    "url": "https://openlibrary.org/search.json?q=harry potter",
    "jsonPayloadSize": 40702,
    "xmlPayloadSize": 58332
}
```
By using XML, there is 18kB increase (43% !).

On an endpoint requested 1 million times per day, it represents 18GB that are "useless".

### Validation principle

true of false
