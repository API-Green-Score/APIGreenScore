## Use Event Driven Architecture to avoid polling madness.

### Identifiers

| API Green Score |  V1  |  V2  |  V3  |
|:-------:|:----:|:----:|:----:|
|   DE06   | 1  |   |      |

### Categories

| Lifecycle |  Resources  |  Responsible  |
|:---------:|:----:|:----:|
| Design | Network / Storage | API Producer |

### Indications

| Priority Level |      Implementation Difficulty      |  Ecological Impact Level   |
|:-------------------:|:-------------------------:|:---------------------:|
| tbd | tbd | tbd |

|Saving Resources                                           |
|:----------------------------------------------------------:|
|network / storage    |

### Description

When configuring a cache, it often happens that the data refresh policy (TTL) is not synchronized with the data life cycle.

In this case, the cache is not fully efficient because the data is expired too early or too late.

It is necessary to provide an expiration policy adapted to the data refresh cycle and to allow partial expiration of the cached data in order to be as efficient as possible on all the processed data. To optimize the cache as much as possible, it is also possible to build an architecture where the source of the data notifies, via an event, the cache of the expiration of a specific data.




### Example
TBD 

### Validation principle

true of false