## Choose the correct API based on use case to avoid requests on multiple systems or large number of requests. Refer to the data catalog to validate the data source

### Identifiers

| API Green Score |  V1  |  V2  |  V3  |
|:-------:|:----:|:----:|:----:|
|   US05   | 1  |   |      |

### Categories

| Lifecycle |  Resources  |  Responsible  |
|:---------:|:----:|:----:|
| Usage | Network/Compute | API Consumer |

### Indications

| Priority Level |      Implementation Difficulty      |  Ecological Impact Level   |
|:-------------------:|:-------------------------:|:---------------------:|
| tbd | tbd | tbd |

|Saving Resources                                           |
|:----------------------------------------------------------:|
|network / compute   |

### Description

We often notice that applications, in order to refresh their data, make very frequent requests to APIs.
This causes an important workload and we increase the computing resources to absorb this load in order not to penalize the other users.

The best practice is to use an event-driven architecture in order to receive a notification when a piece of information is modified to avoid making regular useless requests. But the data contained in the event must be precise to be sure to avoid a system making a request to retrieve an unused data.



### Example
TBD 

### Validation principle

true of false