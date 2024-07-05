# Questionnaire for projects intending to join the OpenRail Association

## What is the project's name?

Capella Collaboration Manager

## Describe the project. What does the project do, why is it valuable, where does it come from?

Many complex systems are developed across organizations, requiring a platform
where users can collaborate to standardize systems.
[Capella](https://mbse-capella.org/) is an open-source tool for Model Based
Systems Engineering using the ARCADIA method. Capella Collaboration Manager
makes Capella available via browser streaming without any complex installation
for users and takes care of the modelling project lifecycle. It allows users to
collaborate on models in real-time and to automate tasks around models.

More information is available in the README of the project:
https://github.com/DSD-DBS/capella-collab-manager

## Who are the maintainers of the project (these will be the primary contacts for the OpenRail Association)?

- Moritz Weber (moritz.weber@deutschebahn.com)
- Viktor Kravchenko (viktor.kravchenko@deutschebahn.com)
- Dominik Lammers (dominik.lammers@deutschebahn.com)
- Jamil Raichouni (jamil.raichouni@deutschebahn.com)

## Which organizations are sponsoring/contributing to the project?

DB InfraGO AG

## Where is the code hosted?

It's currently hosted on GitHub. The main application can be found here:

- https://github.com/DSD-DBS/capella-collab-manager

Another repository is available which provides Docker images for the available
tools in the Capella Collaboration Manager:

- https://github.com/DSD-DBS/capella-dockerimages

## Which exact repositories do you intend to transfer to the GitHub organization of the OpenRail Association?

- https://github.com/DSD-DBS/capella-collab-manager
- https://github.com/DSD-DBS/capella-dockerimages

## What is the project's main license?

Apache 2.0
(https://github.com/DSD-DBS/capella-collab-manager/blob/main/LICENSES/Apache-2.0.txt)

## What other licenses does the project use, e.g. for included 3rd party code?

CC0 1.0
(https://github.com/DSD-DBS/capella-collab-manager/blob/main/LICENSES/CC0-1.0.txt)

A full analysis of the dependencies installed via package managers (npm, pip,
apt) has yet to be carried out. The project has interfaces to other tools with
proprietary licenses (TeamForCapella and pure::variants). Those components are
optional and the repository only uses the interfaces.

## Are any trademarks associated with the project?

No

## Does the project have a web site? Where is it? Are you ok with moving it to be hosted by the OpenRail Association?

Only the documentation, but we would like to have a static website in the
future.

## What are the communication channels the project uses (such as mailing lists, Slack, IRC, etc.)?

- GitHub Issues
- Email (set@deutschebahn.com)

## What is the project's leadership team and decision-making process?

Project leadership is currently shared between Viktor Kravchenko and Moritz
Weber. Decisions are made together with other contributors.

## How is it decided if and when a pull request is merged?

The pull request have to fullfill our
[Pull Request Acceptance Criteria](https://dsd-dbs.github.io/capella-collab-manager/development/pull_requests/).
When the criteria are met, the pull request is reviewed and merged if it fits
the project strategy.

## How can someone become a committer or a maintainer to/of the project?

Contributions are possible via forks and pull requests. Maintainers with rights
in the repository are initially reserved for members of the Systems Engineering
Toolchain department of DB InfraGO. Potentially, this can be expanded, but only
with good knowledge of the project and regular contributions.

## How is development of the project planned and organized? Is this transparent to the public?

We have a GitHub Project Board where we plan our work. The board is not yet
public. We plan to make it public in the future.

## What is the project's roadmap?

No public roadmap available.

## What other organizations in the world should be interested in this project?

Any organization that needs to develop complex and safety-critical systems.

## Why would this project be a good candidate for inclusion in the OpenRail Association?

The project is already widely used in the railway sector via Europe’s Rail
Joint Undertaking. Many infrastructure companies face the same challenges. It
makes sense to work together rather than developing systems individually in
each country.

## Are there competing products or projects? If there are please explain how the proposed projects differentiates.

[Eclipse SysON](https://mbse-syson.org/) will be an alternative, but is still
in development.

The tools that run in the Capella Collaboration Manager have competing
products, but those are not Open Source and often do not have open interfaces.

## What standards does the project implement or rely on? How are they related to other existing standards?

- [RFC 6749 (Oauth 2.0 authorization framework)](https://datatracker.ietf.org/doc/html/rfc6749)

## What is the tech stack of the project? Name the major programming languages and frameworks which are used.

- [Angular](https://angular.dev/) (Frontend)
- [Python](https://www.python.org/) + [FastAPI](https://fastapi.tiangolo.com/)
  (Backend)
- [Docker](https://www.docker.com/) + [Kubernetes](https://kubernetes.io/) +
  [Helm](https://helm.sh/) (Deployment)
- [MkDocs Material](https://squidfunk.github.io/mkdocs-material/)
  (Documentation)
- [Grafana](https://grafana.com/) + [Prometheus](Prometheus) (Monitoring)
- [Grafana Loki](https://grafana.com/oss/loki/) (Logging)
- [OpenAPI Generator](https://openapi-generator.tech/) for frontend API client
  generation
- [Storybook](https://storybook.js.org/) as visual testing framework

## What is the project's plan for growing in maturity if accepted within the OpenRail Association?

A neutral ground allows more companies to contribute to or use the project.

## Concluding statements

By sending this questionnaire you confirm that the project will adhere to the
[code of conduct](CODE_OF_CONDUCT.md) of the OpenRail Association.

By sending this questionnaire you confirm that the project intends to be
incubated in the OpenRail Association and plans to meet the maturity criteria
set out by the OpenRail Association for incubated projects.
