# ALEX: AI Local climate and Energy eXchange

ALEX brings AI into Local Digital Twins for climate and energy planning in Helsinki and Prague. It is a Work Strand 3 pilot of [LDT4SSC](https://ldt4ssc.eu/) (Local Digital Twins for Smart and Sustainable Communities) and runs from 31 August 2026 to 29 February 2028.

This repository is the pilot's public record: progress Updates, documentation, and pointers to the pilot's outputs. Its Updates appear on the pilot's page on the [LDT4SSC Knowledge Hub](https://knowledgehub.ldt4ssc.eu/) and in the LDT4SSC project feeds. It was created from the [LDT4SSC pilot template](https://github.com/ldt4ssc/pilot-template).

## The pilots

- **Helsinki** develops the city's Energy and Climate Atlas into a Local Digital Twin capable of predictive analysis: prioritising energy retrofits across the building stock, estimating the effect of climate actions, and making the results understandable to private and public actors.
- **Prague** builds a Local Digital Twin that brings energy, environmental and spatial data into the early stages of urban planning, so that development scenarios can be simulated before they are built.

Both pilots share an interoperability layer based on Location Europe and OGC APIs, a Model Context Protocol (MCP) tool for AI-ready access to geospatial data, and a Prometheus-X data space connector for trusted data exchange.

## Repository structure

| Path | Contents |
| --- | --- |
| [`pilot.yaml`](pilot.yaml) | Pilot metadata read by the LDT4SSC aggregator: name, partners, locations, focus areas, contact |
| [`updates/`](updates/) | Updates on the pilot's progress, milestones, lessons, assets and events. See [`updates/README.md`](updates/README.md) for the format |
| [`docs/`](docs/) | Longer-lived documentation: architecture, decisions, methodology |
| [`assets/`](assets/) | Descriptions of the pilot's outputs, with links to where each lives |
| [`src/`](src/) | Source code, or pointers to the repositories where it lives |
| [`data-models/`](data-models/) | Data models, or references to where they are published openly |

<!--
Placeholder: uncomment once the first development or partner repository is public.

## Related repositories

| Repository | Owner | Contents |
| --- | --- | --- |
-->

## Contributing

Changes reach `main` only through pull requests, reviewed and approved by someone from another partner. See [CONTRIBUTING.md](CONTRIBUTING.md) for the workflow.

- **Updates:** at least one a month during active work, written by the task leaders or the maintainers. Copy an example from [`updates/_examples/`](updates/_examples/), and list everyone who contributed as authors.
- **Who can merge:** members of the pilot editors team, agreed by the consortium. Other consortium members propose changes through a pull request from a fork. For substantial content, open an [Update or Documentation Proposal](../../issues/new?template=3-content-proposal.yml) first.
- **Never in this repository:** confidential, sensitive or embargoed information; personal data without consent; third-party material without attribution and a licence; formal reports and deliverables.

The `lint` check validates `pilot.yaml` on every pull request, and the template's validation workflow checks every Update.

## Contacts

| Role | Contact |
| --- | --- |
| Main contact, City of Helsinki (pilot coordinator) | Tapani Heino |
| Main contact, Forum Virium Helsinki | Olli-Pekka Mattila |
| Repository maintainers | The ALEX-LDT maintainers team (Forum Virium Helsinki), through an [issue](../../issues/new/choose) in this repository |

To report a security vulnerability, follow the [security policy](https://github.com/ALEX-LDT/.github/blob/main/SECURITY.md). Do not open a public issue.

## Licensing

Code in this repository is licensed under the Apache License 2.0. Content and documentation are licensed under Creative Commons Attribution 4.0 International (CC BY 4.0) unless stated otherwise. See [`LICENSE`](LICENSE) for details.

## About LDT4SSC

LDT4SSC (Local Digital Twins for Smart and Sustainable Communities) is a project funded by the Digital Europe Programme under grant agreement number 101226211, developing an interconnected ecosystem of Local Digital Twins across Europe.

Learn more at the [LDT4SSC project website](https://ldt4ssc.eu/) and the [LDT4SSC Knowledge Hub](https://knowledgehub.ldt4ssc.eu/).

## Funding

<img src="https://github.com/ALEX-LDT/.github/raw/main/profile/eu-emblem.png" alt="Co-funded by the European Union" height="60">

Funded by the European Union. Views and opinions expressed are however those of the author(s) only and do not necessarily reflect those of the European Union or Digital Europe Programme. Neither the European Union nor the Digital Europe Programme can be held responsible for them. The LDT4SSC consortium and the European Commission are not responsible for any use that may be made of the information it contains.
