# Council Data Project Governance

The official version of this document, along with a list of individuals and institutions in the roles defined in the governance section below, is contained in the [CDP Governance Repository](https://github.com/CouncilDataProject/governance).

## The Project

The Council Data Project (CDP) is an open-source software project. The goal of CDP is to develop open-source software, and to deploy open and public websites that provide enhanced transparency to the data produced by local governments.

All software developed by CDP is released under the [MIT](./LICENSE) open-source license and hosted in public GitHub repositories under the [CDP GitHub organization](https://github.com/CouncilDataProject).

Our actively maintained tools are:

- [cookiecutter-cdp-deployment](https://github.com/CouncilDataProject/cookiecutter-cdp-deployment).
- [cdp-backend](https://github.com/CouncilDataProject/cdp-backend)
- [cdp-frontend](https://github.com/CouncilDataProject/cdp-frontend)
- [cdp-scrapers](https://github.com/CouncilDataProject/cdp-scrapers)
- [cdp-design](https://github.com/CouncilDataProject/cdp-design)

You can find a list of active CDP instances on our website: [councildataproject.org](https://councildataproject.org)

CDP started as a research project between Jackson Maxfield Brown and Nic Weber at the [University of Washington Information School (iSchool)](https://ischool.uw.edu/) and the UW Information School informally serve's as CDP's fiscal sponsor for any grants received. In the future, we plan to transition CDP to an external fiscal sponsor that may hold project trademarks and other intellectual property, help manage project donations and acts as a parent legal entity. The UW Information School is the only legal entity that currently has a relationship with CDP.

## Governance

This section describes the governance and leadership model of CDP.

The foundations of CDP governance are:

- Openness & Transparency
- Active Contribution
- Institutional Neutrality

## CDP Roles

#### Leadership and Decision Making

CDP is currently a small open-source project, and in general all CDP decisions are made through consensus among Core Contributors with input from the Community. As with most small projects this informal decision making is a viable model for the short term.

More formally though, CDP's leadership resembles Python and Linux as having a "Benevolent Dictator For Life" or [BDFL](https://en.wikipedia.org/wiki/Benevolent_dictator_for_life). For the sake of transparency in decision making, this document formally codifies Jackson Maxfield Brown as CDP's BDFL. The BDFL can, but should rarely choose to, override the Core Contributors and make a final decision on a matter of contention. This model can be revised over time, but for a small open-source project with little disagreement we believe the BDFL model is appropriate.

As CDP grows it will undoubtedly face more legal and financial decisions. We don't see a need for a more formal governance model at this time. Moving forward CDP leadership should consist of a BDFL and Steering Council that can help make fiscal and governance decisions for the sustainability of CDP. This governance document is really just an attempt to formalize what we are already doing to run CDP, rather than a change in any formal direction of the project. This document will be modified, and this governance model will mature as CDP matures (see the [Maintenance of Governance Documents](#maintenance-of-governance-documents) section below).

#### Contributors

CDP is developed by a team of distributed developers, called **Contributors**. Contributors are individuals who have contributed code, documentation, designs or other work to one or more CDP repositories. Anyone can be a Contributor. Contributors can be affiliated with any legal entity or none. Contributors participate in CDP by submitting, reviewing, and discussing GitHub Pull Requests and Issues and participating in open and public CDP discussions on GitHub, Slack, and any chat rooms or related in-person meetings. The foundation of CDP participation is openness and transparency.

The following links point to contributer graphs as maintained by GitHub, however not all contribution is done in code and as such these graphs are an incomplete set:

- [councildataproject.github.io](https://github.com/CouncilDataProject/councildataproject.github.io/graphs/contributors)
- [cookiecutter-cdp-deployment](https://github.com/CouncilDataProject/cookiecutter-cdp-deployment/graphs/contributors)
- [cdp-backend](https://github.com/CouncilDataProject/cdp-backend/graphs/contributors)
- [cdp-frontend](https://github.com/CouncilDataProject/cdp-frontend/graphs/contributors)
- [cdp-scrapers](https://github.com/CouncilDataProject/cdp-scrapers/graphs/contributors)
- [cdp-design](https://github.com/CouncilDataProject/cdp-design/graphs/contributors)

#### Core Contributors

CDP is sustained through the dedicated work of a small set of **Core Contributors**. A Core Contributor is anyone that has received write access to a CDP repository, and / or actively maintains one or more aspect of the CDP infrastructure. Anyone can become a Core Contributor. To be given Core Contributor status the BDFL simply has to add the person's name and area of contribution to this governance document, and then grants the proper credentials for that person in the GitHub Organization.

The Core Contributors for CDP are currently:

- **Organization Wide**

  - [Brian Ledbetter](https://github.com/BrianL3)
  - [Hawk Ticehurst](https://github.com/hawkticehurst)
  - [Isaac Na](https://github.com/isaacna)
  - [Jackson Maxfield Brown](https://github.com/JacksonMaxfield)
  - [Nic Weber](https://github.com/nniiicc/)
  - [Sarah Liu](https://github.com/sarahjliu)
  - [To Huynh](https://github.com/tohuynh)

- **Repository Specific**

  - [cdp-scrapers](https://github.com/CouncilDataProject/cdp-scrapers)

    - [Sung Cho](https://github.com/dphoria)

#### Community

The **CDP Community** consists of all Contributors and Users of the Project. Contributors work on behalf of and are responsible to the larger CDP Community and we strive to keep the barrier between Contributors and Users as low as possible.

### Communications

Unless specifically required, all CDP discussions and activities will occur in public and done in collaboration and discussion with CDP Core Contributors and Community. Anyone can join any of the communication platforms for CDP.

Most of CDP's communication happens through Slack or GitHub.

- **Slack**: To join the CDP Slack go to [councildataproject.slack.com](councildataproject.slack.com)

### Credit and Acknowledgement

CDP is a volunteer organization and we seek, above all, to be transparent about who receives credit for their contribution to the success of CDP. Major contributors will always be listed on our organization website: [councildataproject.org](councildataproject.org).

To cite this work in a scholarly publication please use the following citation:
`Council Data Project Contributors (2021). Council Data Project: Transparency and accessibility in council action. Videos, transcripts, voting records, and legislation -- all searchable under a single website. [Computer software]. GitHub. https://github.com/CouncilDataProject`

or bibtex:

```
@software{cdp,
  author = {{Council Data Project Contributors}},
  title = {Council Data Project: Transparency and accessibility in council action. Videos, transcripts, voting records, and legislation -- all searchable under a single website.},
  url = {https://github.com/CouncilDataProject},
  version = {3.0.0},
  date = {2021-8-01},
}
```

### Financial Contributions

We do not currently have a model of fiscal sponsorship. We are actively pursuing a number of research grants through the University of Washington, and will keep the Community informed of any updates in this area of CDP's sustainability. All current finances are handled by BDFL and Core Contributors.

### Conflict of Interest

Core Contributors will be employed by a wide range of companies, universities and non-profit organizations. Because of this, it is possible that there will be conflict of interests. Such conflict of interests include, but are not limited to:

- Financial interests, such as investments, employment, or contracting work, outside of CDP that may influence their work on CDP.
- Access to proprietary information of their employer that could potentially leak into their work with the CDP.
- An issue where the person privately gains an advantage from CDP resources, but CDP has no gain or suffers a disadvantage.

All CDP Contributors should disclose any conflict of interest they may have prior to contribution.

### Maintenance of Governance Documents

Changes to the governance documents are submitted via a GitHub pull request to CDP's governance documents GitHub repository at [https://github.com/CouncilDataProject/governance](https://github.com/CouncilDataProject/governance). There is no formal consensus or decision making stated or implied in this governance document.

The BDFL and all Core Contributors will have editing rights to this document.
