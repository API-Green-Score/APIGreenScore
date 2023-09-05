## Prefer opaque token prior to JWT

### Identifiers

| API Green Score |  V1  |  V2  |  V3  |
|:-------:|:----:|:----:|:----:|
|   DE04   | 1  |   |      |

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

One of the structuring questions when designing an API is the selection of the token type to use. If the choice is often made by technical constraints or personal affinities, the durability aspect is also to be taken into account.

We can note that an opaque token, in addition to improve the security, is smaller than a JWT token which will have a stronger impact on the network, storage and compute resources.
In the interest of sustainability, it is therefore recommended that a lighter token type be preferred in order to reduce the bandwidth, compute and storage resources consumption.




### Example
TBD 

### Validation principle

true of false