![apigreenscore_logo](https://github.com/ytremblais/APIGreenScore/assets/13643712/58127821-e390-4922-bb96-ab6bfff12c43)

# API Green Score

## project

The API Green Score is a toolkit to help API consumers, designers and owners to ask themselves questions about the digital impact of their API.

This tool is based on 7 differents domains in order to create relevant and realistic metrics that stakeholders can use.

The evaluation method is shared with all API Persona (API owners, API consumers, API developers)

We are talking about rules for the API Green Score Grid, but first, it's based on Best Practices. 


This toolkit consists of an evaluation grid and evaluation rules.

But before using evaluation grid a short word about Best Practices.

For API we defined 7 Domains 
- API Lifecyle
- Data exchange
- Data
- Architecture
- Tools
- Infrastructure
- Communication

Each Domain, can contains many rules

Each rules are associated to 1 of categories

- Architecture (AR)
- Design (DE)
- Usage (US)
- Log (LO)


### API Lifecycle
- AR03 : Ensure Only One API fits same need
- US02 : Decommission EOL or unused APIs
- US03 : Limit the number of API versions
- US05 : Choose the correct API based on use case
- US06 : API well designed and documented to increase reuse rate
- US07 : Monitor Error Rate

### Data exchange
- DE01 : Prefer smallest format for exchange (JSON instead of -XML)
- DE02 : Use Cache
- DE03 : Use the cache efficiently to avoid useless resources consumption
- DE05 : Align Cache refresh strategy to data source
- DE07 : Is system, Business or CX API?
- DE08 : Implemented filtering mechanism to limit payload size
- DE11 : Availability of pagination
- US01 : Use query parameters for GET Methods

### Data
- DE02 : Use Cache
- DE03 : Use the cache efficiently to avoid useless resources consumption 
- DE06 : Allow a part cache refresh and align it on data refresh
- DE09 : Leverage OData or GraphQL when relevant
- US04 : Optimize queries to limit the information returned to - what is strictly necessary
- US05 : Choose the correct API based on use case
- USXX : Compressed Payload

### Architecture
- AR01 : Use Event Driven Architecture
- AR02 : API Runtime close to the consumer
- AR03 : Ensure Only One API fits same need


### Tools
- LO01 : Define log Retention Period (ops and legal)

### Infrastructure
- AR04 : Use Scalable infra to avoid over-provisioning
- AR05 : Footprint dashboard of Cloud Provider

### Communication
- US06 : API well designed and documented to increase reuse rate


Thanks a lot for your contribution!


## Needs

Given the continuous advancements of API, this repository needs to be regularly updated.
Any proposal or idea for improvement, modification, or deletion is welcome.

## How to contribute?

Feel free to read the contributor's guide.[the contributor's guide](CONTRIBUTING.md).

## Shortcut to discussions:

To simplify your search, don't forget to use the available filters on the discussions page.

  - :infinity: [List of all discussions](https://github.com/ytremblais/APIGreenScore/discussions)
  - :heavy_plus_sign: [List of discussions for adding rules](https://github.com/ytremblais/APIGreenScore/discussions?discussions_q=label%3Aaddition)
  - :memo: [List of discussions for modifying rules](https://github.com/ytremblais/APIGreenScore/discussions?discussions_q=label%3Amodification)
  - :heavy_multiplication_x: [List of discussions for deleting rules](https://github.com/ytremblais/APIGreenScore/discussions?discussions_q=label%3Adeletion)



## List of Best Practices:

* [AR01](/chapters/AR01_en.md)
* [AR02](/chapters/AR02_en.md)
* [AR03](/chapters/AR03_en.md)

* [US01](/chapters/US01_en.md)
* [US02](/chapters/US02_en.md)
* [US03](/chapters/US03_en.md)
* [US05](/chapters/US05_en.md)
* [US06](/chapters/US06_en.md)
* [US07](/chapters/US07_en.md)

* [DE01](/chapters/DE01_en.md)
* [DE02](/chapters/DE02_en.md)
* [DE03](/chapters/DE03_en.md)
* [DE04](/chapters/DE04_en.md)
* [DE05](/chapters/DE05_en.md)
* [DE06](/chapters/DE06_en.md)
* [DE07](/chapters/DE07_en.md)
* [DE08](/chapters/DE08_en.md)
* [DE09](/chapters/DE09_en.md)
* [DE10](/chapters/DE10_en.md)
* [DE11](/chapters/DE11_en.md)

* [LO01](/chapters/LO01_en.md)

## Licences

The sources and contents of this project are [protected](LICENCE.md)
