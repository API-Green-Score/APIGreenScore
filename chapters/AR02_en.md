## AR02 : API Runtime close to the consumer


### Identifiers

| API Green Score |  V1  |  V2  |  V3  |
|:-------:|:----:|:----:|:----:|
|   AR02   | 1  |   |      |

### Categories

| Lifecycle |  Resources  |  Responsible  |
|:---------:|:----:|:----:|
| Architecture | Network | API Producer |

### Indications

| Priority Level |      Implementation Difficulty      |  Ecological Impact Level   |
|:-------------------:|:-------------------------:|:---------------------:|
| tbd | tbd | tbd |

|Saving Resources                                           |
|:----------------------------------------------------------:|
|network |

### Description

It is not uncommon to find that APIs are deployed in locations that are not selected in relation to their consumers.

This results in not only a degraded user experience in some cases, but also a greater demand on the network to route requests sometimes to a region on the other side of the world. 

Good architecture practices therefore recommend deploying APIs, and services in general, as close as possible to the consumers. Also, if possible, prefer a deployment in several locations with geo routing (aka. position based routing) to the closest instance to improve response times and reduce the number of kilometers traveled by requests.



### Example
TBD 

### Validation principle

true of false