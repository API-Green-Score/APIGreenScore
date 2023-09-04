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

||Saving Resources                                           |
|:----------------------------------------------------------:|
|network / compute / storage    |

### Description

It often happens that the implementation of filters in the APIs allowing to return only the necessary data to the consumers are forgotten or not efficient. 

This forces API consumers to make generic requests that retrieve unnecessary amounts of information, resulting in overconsumption of bandwidth and storage.

It is recommended to design and implement filters that allow the user to limit the amount of data returned to optimize network and storage consumption.



### Example
TBD 

### Validation principle

true of false