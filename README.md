![apigreenscore_logo](https://github.com/ytremblais/APIGreenScore/assets/13643712/58127821-e390-4922-bb96-ab6bfff12c43)
=============================
# API Green Score

## project

The API Green Score is a toolkit to help API consumers, designers and owners to ask themselves questions about the digital impact of their API.

Orignal document are available on ["API Thinking collectif"](https://www.collectif-api-thinking.com/ ) website.

2 Documents are available : 

  - [Evaluation grid](https://www.collectif-api-thinking.com/assets/deliverables/worksites/48_CAT_Sustainable_API_GreenScore_V1-2.xlsx)
  
  - [Guide](https://www.collectif-api-thinking.com/assets/deliverables/worksites/50_CAT_API_Sustainable_IT.pdf)

This tool is based on 7 differents domains in order to create relevant and realistic metrics that stakeholders can use.

The evaluation method is shared with all API Persona (API owners, API consumers, API developers)

We are talking about rules for the API Green Score Grid, but first, it's based on Best Practices. 

**/!\ Warning**: this is still a very early stage project. Any feedback or contribution will be highly appreciated. Please
refer to the contribution section.

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](https://github.com/green-code-initiative/ecoCode-common/blob/main/doc/CODE_OF_CONDUCT.md)

--------------------

This toolkit consists of an evaluation grid and evaluation rules.

But before using evaluation grid a short word about Best Practices.

For API we defined 7 Domains:

- API Lifecyle
- Data exchange
- Data
- Architecture
- Tools
- Infrastructure
- Communication

Each Domain, can contains many rules

Each rules are associated to 1 of categories :

- Architecture (AR)
- Design (DE)
- Usage (US)
- Log (LO)


### API Lifecycle
- [AR03 : Ensure Only One API fits same need](/chapters/AR03_en.md)
- [US02 : Decommission EOL or unused APIs](/chapters/US02_en.md)
- [US03 : Limit the number of API versions](/chapters/US03_en.md)
- [US05 : Choose the correct API based on use case](/chapters/US05_en.md)
- [US06 : API well designed and documented to increase reuse rate](/chapters/US06_en.md)
- [US07 : Monitor Error Rate](/chapters/US07_en.md)

### Data exchange
- [DE01 : Prefer smallest format for exchange (JSON instead of -XML](/chapters/DE01_en.md)
- [DE02 : Use Cache](/chapters/DE02_en.md)
- [DE03 : Use the cache efficiently to avoid useless resources consumption](/chapters/DE03_en.md)
- [DE05 : Align Cache refresh strategy to data source](/chapters/DE05_en.md)
- [DE07 : Is system, Business or CX API?](/chapters/DE07_en.md)
- [DE08 : Implemented filtering mechanism to limit payload size](/chapters/DE08_en.md)
- [DE11 : Availability of pagination](/chapters/DE11_en.md)
- [US01 : Use query parameters for GET Methods](/chapters/US01_en.md)

### Data
- [DE02 : Use Cache](/chapters/DE02_en.md)
- [DE03 : Use the cache efficiently to avoid useless resources consumption](/chapters/DE03_en.md)
- [DE06 : Allow a part cache refresh and align it on data refresh](/chapters/DE06_en.md)
- [DE09 : Leverage OData or GraphQL when relevant](/chapters/D09_en.md)
- [US04 : Optimize queries to limit the information returned to - what is strictly necessary](/chapters/US04_en.md)
- [US05 : Choose the correct API based on use case](/chapters/US05_en.md)
- [USXX : Compressed Payload](/chapters/USxx_en.md)

### Architecture
- [AR01 : Use Event Driven Architecture](/chapters/AR01_en.md)
- [AR02 : API Runtime close to the consumer](/chapters/AR02_en.md)
- [AR03 : Ensure Only One API fits same need](/chapters/AR03_en.md)


### Tools
- [LO01 : Define log Retention Period (ops and legal)](/chapters/LO01_en.md)

### Infrastructure
- [AR04 : Use Scalable infra to avoid over-provisioning](/chapters/AR04_en.md)
- [AR05 : Footprint dashboard of Cloud Provider](/chapters/AR05_en.md)

### Communication
- [US06 : API well designed and documented to increase reuse rate] (/chapters/US06_en.md)


Thanks a lot for your contribution!


## Needs

Given the continuous advancements of API, this repository needs to be regularly updated.
Any proposal or idea for improvement, modification, or deletion is welcome.

## How to contribute?

Feel free to read [the contributor's guide](CONTRIBUTING.md).

## Shortcut to discussions:

To simplify your search, don't forget to use the available filters on the discussions page.

  - :infinity: [List of all discussions](https://github.com/ytremblais/APIGreenScore/discussions)
  - :heavy_plus_sign: [List of discussions for adding rules](https://github.com/ytremblais/APIGreenScore/discussions?discussions_q=label%3Aaddition)
  - :memo: [List of discussions for modifying rules](https://github.com/ytremblais/APIGreenScore/discussions?discussions_q=label%3Amodification)
  - :heavy_multiplication_x: [List of discussions for deleting rules](https://github.com/ytremblais/APIGreenScore/discussions?discussions_q=label%3Adeletion)


## Licences

The sources and contents of this project are [protected](LICENCE.md)
