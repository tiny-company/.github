# ![tiny company logo](./images/logos/favicon.ico) tiny company

## Description

"Tiny-company" is a project that simulate an IT company. <br>
It's main goal is to gather all the main element of an infrastructure needed for such company. <br>

Repositories are separated using the naming convention below :
- **pckr-** : for all repository that contain packer code to create cloud image.
- **doc-** : for all repository that are related to documentation.
- **asbl-** : for all repository that contain ansible code, mostly role to be used as dependency.
- **tfm-** : for all repository that contain terraform/opentofu code to be used as module.
- **srv-** : for all repository that contain service code (a service is the tiniest virtualize element, and is commonly a container image)
- **prd-** : for all repository that contain product code (a product is a group of service gather by theme, i.e : monitoring product = Prometheus + Grafana services)