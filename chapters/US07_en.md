## Error Rate

### Identifiers

| API Green Score |  V1  |  V2  |  V3  |
|:-------:|:----:|:----:|:----:|
|   US06   | 1  |   |      |

### Categories

| Lifecycle |  Resources  |  Responsible  |
|:---------:|:----:|:----:|
| Usage | Network/Compute | API Producer/API Consumer |

### Indications

| Priority Level |      Implementation Difficulty      |  Ecological Impact Level   |
|:-------------------:|:-------------------------:|:---------------------:|
| tbd | tbd | tbd |

|Saving Resources                                           |
|:----------------------------------------------------------:|
|network / compute   |

### Description

Decrease the error rate (results different from 2xx) to avoid over processing.

Depending of your context, you can focus on 4xx or 5xx errors, or both.

One of objectives of this rule is to improve the quality of requests (fill all required fields, or better control of contract,etc… ) and improved the response if we have to many errors due to tech
 

### Example
TBD 

### Validation principle

rate

This is a sample rate calculation =  (Number of consumers *50) - 50, if you have more than 100%, it will be a bonus. 