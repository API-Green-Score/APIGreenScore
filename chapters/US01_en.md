## Use query parameters for GET Methods

### Identifiers

| API Green Score |  V1  |  V2  |  V3  |
|:-------:|:----:|:----:|:----:|
|   US01   | 1  |   |      |

### Categories

| Lifecycle |  Resources  |  Responsible  |
|:---------:|:----:|:----:|
| Usage | Network/Compute | API Consumer |

### Indications

| Priority Level |      Implementation Difficulty      |  Ecological Impact Level   |
|:-------------------:|:-------------------------:|:---------------------:|
| tbd | tbd | tbd |

||Saving Resources                                           |
|:----------------------------------------------------------:|
|network / compute     |

### Description

Optimize queries to limit the information returned to what is strictly necessary.

It is often observed that requests made on APIs are not precise enough, which returns a volume of information greater than necessary.

This results in increased bandwidth consumption during exchanges.

The best practice is to create precise requests that return, as much as possible, the strictly necessary information, thus avoiding the transfer of useless information.

This rule is linked to DE08 : “Implement filters to limit which fields are returned by the API ”



### Example
TBD 

### Validation principle

true of false