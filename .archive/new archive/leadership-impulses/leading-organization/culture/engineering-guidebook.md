# The Engineering Guidebook [LIVING DOCUMENT]

The Engineering Guidebook gathers in a single document all of the opinions, best practices, structural elements, and business operations of your engineering team.

## Software Engineering

### Choice of programming languages

Application engineering:
Machine Learning: python

### Opinions/requirements around CI/CD

* we run pylint with every build and break the build if there are conflicts
* we run all unit tests with every build and break the build

### Standards for naming (casing in code, casing in contracts)

#### python

* we recommend [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html) which based on [PEP8](https://peps.python.org/pep-0008/#introduction)|

### How to use source control

* we recommend [trunk based development](https://trunkbaseddevelopment.com)
* we recommend [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) (please use [commitizen](https://github.com/KnisterPeter/vscode-commitizen) or similar tool)

### Testing

* Every class has a unit test
* Ideally we follow the pattern of Test Driven Development and Pair programming

### Architecture Documentation

* Graphical documentation follows [C4 Standard](https://c4model.com)

### Future chapters

* Standards for data processing, protection, backup, security
* Standard patterns for frontend and backend authentication and authorization
* Wire protocol standards (REST, gRPC, GraphQL, etc.)
* Universal requirements (Do we support mobile, responsive, translation?)
* Certification frameworks and related training (e.g., PCI, SOC2, GDPR)
* Other coding logistics: accessing private repos, linting, static code analysis, commit message format/style.

## Engineering Process

### Opinions on cadence/ceremonies (Agile, Kanban, retrospectives)

* We follow KanBan
* Ceremonies
  * Planning
  * Daily
  * Demo
  * Retros
* Cadence = 2 weeks
* WIP limit = 3 items

### Opinions on technical documentation/specification requirements

* UX/ UI concepts are documented in FIGMA
* Conceptboard is no means for persistent documentation
* Requirements are collected in code.siemens.com

### Opinions on how to use the ticketing system (What's an epic? Do we use story points?)

* We use code.siemens.com as our ticketing system
* Discussion are done via code.siemens.com (no EMail!)

### Architecture Decisions

* Architecture decisions are recorded in a folder in the respective project
* Architecture decisions relevant for the enterprise level are brought up to the architectural board and recorded in the enterprise architecture repository. Either in the engineering guidebook or in the architectural decsision registry.
* Architecture decision records follow [MADR](https://github.com/adr/madr/tree/develop/template) ([Explanation of MADR](https://ozimmer.ch/practices/2022/11/22/MADRTemplatePrimer.html))

### Any metrics the team as a whole cares about (Are you measuring cycle time?)

* Mood Marbles in the team
* Lifetime of branches

### Bugs

* Reported as ticket
* Prioritized in the Daily

### Future topics

* How are production incidents handled (PagerDuty? RCA documents?)
* How new technology gets incorporated into the stack
* Process around bugs, tech debt.

## People Management

### Future topics

* Expectations for how performance reviews are conducted, how individuals are evaluated/promoted
* Expectations for contribution to onboarding/hiring processes.

