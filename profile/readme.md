# ![tiny company logo](./images/logos/favicon.ico) tiny company

## Description

"Tiny-company" is a project that simulate an IT company. <br>
It's main goal is to gather all the main element of an infrastructure needed for such company. <br>

The main idea behind this project is to offer some basic solution to any new company such as start up to answer common IT services needs like :
- Forge : How to store code (git) and how to test and deploy it (CICD).
- Logging : How to get data about log happening on services and servers.
- Monitoring : How to monitor service and servers.
- ...

Find more about tiny company element at [tiny company main](https://github.com/tiny-company/tiny-company-main)

Repositories in this organization are separated using the naming convention below :
- [**pckr-**](https://github.com/orgs/tiny-company/repositories?q=topic%3Apckr) : for all repository that contain packer code to create cloud image.
- [**doc-**](https://github.com/orgs/tiny-company/repositories?q=topic%3Adocs) : for all repository that are related to documentation.
- [**asbl-**](https://github.com/orgs/tiny-company/repositories?q=topic%3Aasbl) : for all repository that contain ansible code, mostly role to be used as dependency.
- [**tfm-**](https://github.com/orgs/tiny-company/repositories?q=topic%3Atfmodule) : for all repository that contain terraform/opentofu code to be used as module.
- [**srv-**](https://github.com/orgs/tiny-company/repositories?q=topic%3Asrv) : for all repository that contain service code (a service is the tiniest virtualize element, and is commonly a container image)
- [**prd-**](https://github.com/orgs/tiny-company/repositories?q=topic%3Aprd) : for all repository that contain product code (a product is a group of service gather by theme, i.e : monitoring product = Prometheus + Grafana services)