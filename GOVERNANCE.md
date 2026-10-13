# Lind Project Governance

Lind uses a flattened maintainer model. Maintainers share responsibility for the health and direction of the project. Individual maintainers may have primary areas of expertise, but project ownership is collective.

The current list of maintainers and their focus areas is kept in [MAINTAINER.md](MAINTAINER.md).

## Project Roles

### Users

These are individuals who 1) want to learn more about the Lind Project; or 2) are existing users of Lind and its tools who wish to follow the Project's progress. They may have questions, comments, or suggestions that can be communicated via Slack, GitHub, or during community calls and events.

### Contributors

These are individuals who wish to contribute code or ideas to Lind projects. Contributors submit code and ideas through GitHub or through participation in Lind's community calls.

### Maintainers

These are individuals who can merge submitted PRs into the primary codebase. A PR must be approved by at least one maintainer who is not its author before it can be merged. Maintainers also adhere to the following:

- They are an active Lind contributor. This includes, but is not limited to, regular attendance of Lind community meetings and subprojects relevant to the components they maintain.
- They respond to PR review requests in a timely manner. Generally, a response is expected within 3 days of the PR being submitted.

They ensure that code changes they approve:

- Meet the coding conventions required by the Project. This includes ensuring the code is sufficiently well tested, follows the appropriate standards, and, of course, does not break the build.
- Are consistent with the goals and direction of the Project. 

Once a PR has the requisite approvals, the last approving maintainer is responsible for merging the change (however, the PR's author must ensure the change is merge-ready).

## Decision making

Routine changes are accepted through pull-request review. A pull request requires approval from at least one maintainer who is not its author. Security-sensitive or substantial architectural changes must be approved by at least two maintainers.

Maintainers seek consensus for major decisions. If consensus cannot be reached after reasonable discussion, a simple majority of active maintainers decides the matter. A tie means the proposal does not pass, and discussion continues until a majority forms. A maintainer with a direct conflict of interest should abstain.

## Becoming a maintainer

Contributors may be nominated after demonstrating sustained, high-quality participation in the project. Relevant participation includes code, reviews, documentation, issue triage, testing, design work, and community support.

A nomination must be approved by a majority of active maintainers. The decision and its rationale should be recorded publicly whenever appropriate.

## Inactive and emeritus maintainers

A maintainer who expects to be unavailable for an extended period may move to emeritus status. Emeritus maintainers retain recognition for their contributions but are not counted in active project decisions.

Maintainer status may be reviewed after six months without project participation. Before changing a maintainer's status, the project will attempt to contact them privately.

## Removing a maintainer

A maintainer may be removed for sustained inactivity (see above) or for cause, such as a violation of the [Code of Conduct](CODE_OF_CONDUCT.md) or repeated actions contrary to the Project's goals. Removal for cause requires approval from a majority of active maintainers, and the maintainer in question does not vote. The project will attempt to raise concerns with the maintainer privately before initiating removal.

## Specification development

Lind specifications are developed under the [Community Specification License 1.0](COMMUNITY_SPECIFICATION_LICENSE.md), within the bounds set by [SCOPE.md](SCOPE.md). This section is the governance policy referenced by that license.

**Draft.** Participants may submit issues and pull requests to any Lind-Project repository at any point. They are reviewed and merged following [CONTRIBUTING.md](CONTRIBUTING.md). Each updated version of a Lind specification following the merging of a pull request is a "Draft Specification".

**Approval.** Once the maintainers believe a Draft Specification has achieved its objectives, they may progress it to "Approved Specification" status:

- The maintainers announce that version of the Draft Specification as a candidate for "Approved Specification" status on the project's community channels (see [COMMUNITY.md](COMMUNITY.md)) and start a two-week review period.
- During the review period, participants may raise any issues regarding the Draft Specification. Such issues are considered and resolved in the ordinary course.
- The maintainers may extend the review period, but will not shorten it to less than two weeks.
- After the review period, and upon approval by a majority of active maintainers, the Draft Specification becomes an "Approved Specification".

**Publication.** The maintainers publish each Approved Specification in a publicly accessible location, together with the terms under which it is made available.

**Submission to standards bodies.** No Draft Specification or Approved Specification may be submitted to another standards development organization without approval from a majority of active maintainers. The Contributors that developed that specification agree to grant the copyright rights necessary to make those submissions.

**Non-confidentiality.** Information disclosed in connection with any project activity, including meetings, contributions, and submissions, is not confidential, regardless of any markings or statements to the contrary.

## Contact

Maintainers can be reached through GitHub issues and discussions. Sensitive security matters should be reported through the process described in [SECURITY.md](SECURITY.md).
