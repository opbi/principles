<p align="center">
  <img alt="ncm" src="https://raw.githubusercontent.com/opbi/logo/master/opbi/opbi.svg?sanitize=true" width="160">
</p>

<h3 align="center">OPBI - Open Business Institute</h3>
<p align="center" style="margin-bottom: 2em;">opinionated business agnostic open source solutions</p>

---

### Mission

#### Sharing Best Practices
With the power brought by the open-source community and Sass tools, it is much easier to curate an idea into a business than 2008. OPBI is founded with a mission to share the common technology decisions validated as best practices so that entrepreneurs can better focus on explore business logics. It is initialised with solution patterns found in various companies in different scales, and it is always more forward-looking to fix problems perceived in those organisations. It would stay open-source, so that it can be kept updated to set the technology structure models.

#### Reusable and Integrated Solutions
It often comes down to choose tools and services, integrate them with automations and process to achieve efficiency and technology-organisation fit. Common decisions on infrastructure, development process, pipeline, release pattern, data tracking and analytics can firstly be shared, discussed, updated. Secondly, architect and certain services can be made reusable as well, e.g. an image upload service, payment-accounting integration, etc. OPBI will be sharing here a list of technology choices and automations to integrate them into one system with a fitting organisation structure.

### Assumptions

#### Technology Choices

OPBI will be sharing automation toolings based on the a set of common technology choices to form an integrated system. We aim to use best-of-kind services while also would like to provide more flexibilities to support different choices. As change of the fundemental technology choices would largely impact the toolchain, we would like to keep the solutions more future proof by clear layer separations and lock some of the choices initially.

Here we assume a list of choices as below [in different layers]:
- *Cloud Infrastructure*: Google Cloud Platform (Google Kubernetes Engine) in Terraform
- *Container Orchestration*: Kubernetes, Helm
- *Continuous Integration*: GitHub, CircleCI, Coveralls, Snyk, etc.
- *Build Toolchain*: Language specific best-practice build toolchain managed in centralised repos
  - JavaScript: @opbi/ncm - package an updated best-practices build toolchain for multiple repos
- *Services & Programming Languages*
  - JavaScript(Applications): React, React-Native, Node
  - Python(Data Services)
  - Golang(DevOps Services)
- *Operation*:
  - @opbi/toolbox: Packaged Log, Metrics, Tracing Decorator
  - Prometheus, Grafana, ELK, etc.
- *Behaviour Analytics*: Segment
- *Marketing Automation*
- *Business Intelligence*

#### Organisation Structure


#### Technology Architecture

### Principles
```
"Those who want to do their job well must first sharpen their tools." -- Ban Lu
```
#### Code of Conduct

- Open-Source and Business Agnostic
- Zero-Configuration By Default
- While Always Configurable
- Consistency over Variety
- Repeatable and Automatable

#### Component Lifecycle Standard

#### Service Lifecycle Standard

#### Application Lifecycle Standard
