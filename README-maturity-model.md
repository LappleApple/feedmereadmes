## Notes:
- This is a draft, spun up in about 20 minutes (July 14, 2017). Please feel free to suggest anything.
- An alternative format to follow might be [Apache's maturity model](https://community.apache.org/apache-way/apache-project-maturity-model.html) for how their projects operate.

*****
## README Maturity Model

### Level One: "The Code is the Documentation"
- No/almost no README text of any sort.
- No installation, configuration, running details.
- No developer documentation.
- No complimentary files, such as contributor guidelines.
- No build status information, such that the reader will not gain much insight into the project's current state.
- No indication about average response time to issues and/or pull requests.
- No badges to indicate code coverage or other quality metrics.
- What text is available may be outdated or non-priority.

**Recommendation**: There are occassions where someone may post a personal project or experiment that isn't necessarily something they intend to share or isn't quite ready to share more broadly yet. In these cases, having little to no documentation may be acceptable. We recommend, however, that even in these cases, project owners minimally indicate the nature/status of the project - for example, warning users that this project is experimental/personal and may not be maintained (essentially "use at your own risk").

### Level Two: Bare Minimum README
- Limited information about what the project is and does with minimal details of its purpose.
- Basic installation, configuration, running details for users, but untested and potentially incomplete.
- Basic or no developer documentation.
- A line in the README about contributions, but no dedicated file.
- A line about the project's build status, though it may be outdated; or no build status information.
- A line about the average response time to issues and/or pull requests, though it may be outdated or unclear; or no information on average response time to issues.
- No badges to indicate code coverage or other quality metrics.
- The text is unfrequently updated and may be outdated or inaccurate.

**Recommendation**: Having the bare minimum details indicates to readers that the intent of this project is to share broadly, but the lack of important details can lead to wasted effort and frustration. In this way, the bare minimum can sometimes be worse than no documentation at all. As with level one, we recommend that project owners prominently indicate the nature/status of the project, noting if it is still in early development stages, experimental or a personal project that is not yet intended for production use.

### Level Three: Basic README
- Somewhat detailed information about what the project is and does, but little or no details of its purpose.
- Basic installation, configuration, running details for users, tested and complete.
- Developer documentation and references to a vision or project roadmap to onboard new contributors.
- A dedicated Contributing.md/.rst file with basic information.
- A line about the project's build status, but minimal: "under development" or "stable."
- A line about the average response time to issues and/or pull requests.
- At least one badge to indicate code coverage or other quality metrics.
- The text is updated regularly, but at intervals (monthly or quarterly) such that inaccuracies may exist.

**Recommendation**: A level three project has enough supporting details to begin broadening both adoption and contribution on a small scale. In some cases this is sufficient for a project still in its early phases of development where some level of adoption/contribution is necessary to help the project grow and improve, but the project isn't quite ready for widespread adoption and promotion.

### Level Four: README with purpose
- Detailed information about what the project is and does, along with notes about its features/special attributes and why those exist.
- Basic installation, configuration, running details for users are tested, current and complete, and accompanied with information about commonly made errors/how to resolve them.
- Developer documentation and references to a detailed vision or project roadmap to onboard new contributors.
- A dedicated Contributing.md/.rst file with detailed information about style guidelines, caveats, and pull request size.
- Information about the project's build status includes some context about what aspects of the project remain under development and/or are creating instability.
- Clear information about the average response time to issues and/or pull requests.
- One or more badges to indicate code coverage or other quality metrics.
- The text is updated regularly, but at intervals (monthly or quarterly) such that inaccuracies may exist.

**Recommendation**: A level four project is one that has grown towards a larger community of users and contributors. The supporting information is sufficient to nurture and grow that existing community but may be missing some ingredients necessary to make that last step towards widespread adoption/useage and contribution, particularly within larger corporations that may have more stringent standards for adoption.

### Level Five: Product-oriented README
- Thorough information about what the project is and does, along with details of all its notable features/special attributes and why those exist. The reader will understand why these features and attributes are helpful or meaningful.
- User testimonials and evidence of past performance in real development situations included.
- Basic installation, configuration, running details for users that are tested, current and complete, accompanied with information about commonly made errors/how to resolve them.
- Developer documentation and references to a detailed vision or project roadmap to onboard new contributors; visual aids like diagrams and demos are embedded in the README file.
- A dedicated Contributing.md/.rst file with detailed information about style guidelines, caveats, and pull request size.
- Information about the project's build status includes detailed context about what aspects of the project remain under development and/or are creating instability.
- Clear information about the average response time to issues and/or pull requests.
- One or more badges to indicate code coverage or other quality metrics.
- The text is updated regularly, at frequent intervals (weekly or even daily) such that inaccuracies are unlikely to exist.

**Recommendation**: While we believe every project should aspire to this level of documentation, a level five project is typically one that has already established a broad base of contibutors and users. The level of detail is one that reinforces that the project is production-ready for use by both individuals and companies, and welcomes contributions from both.
