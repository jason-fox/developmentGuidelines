# External Contributions Guidelines

These Guidelines enable specifically external contributions coming from the community (i.e. people who are not part of
the regular staff assigned to each FIWARE Generic Enabler project). They have been inspired on real experience gained
while working in the Mozilla Open Source Community. See [joshmatthews.net](http://www.joshmatthews.net/deck.js/mentor/)
and [Mozilla Mentoring](https://wiki.mozilla.org/Contribute/Coding/Mentoring).

A **public backlog** including potential work items (bug, features, documentation, test cases, ...) to be externally
contributed (_welcome contributions_) **MUST** be available.

A work item is a good candidate to become a _welcome contribution_ if:

-   Should be fixed.

-   It is not time-sensitive or blocking.

-   It has clear steps to reproduce.

-   It is well understood.

_Welcome contribution work items_ **MUST** have a mentor assigned (who will typically be a member of the regular FIWARE
Generic Enabler staff). The Mentor's role includes:

-   Ensure that the right contributor is assigned.

-   Understand how it can be done and will provide guidance on the best way to approach the problem.

-   Answer questions, review changes, and make the process as easy as possible by **reacting promptly**.

-   Make sure that a task is progressing. If nothing is heard from a contributor for a reasonable period of time the
    mentor might unassign the task.

-   After a successful contribution, recognize the contributor and propose new work items to be accomplished, as now a
    mentor should have a good sense of the contributor's capabilities.

The public backlog **MUST** provide a mechanism to allow assignment of work items to external contributors. Contributors
who already come with a _proposed patch_ **MUST** be given preference. Assignment will be subject to approval by FIWARE
Generic Enabler owners, particularly mentors. GitHub users activity profile **MAY** be used in order to assess the
skills of the potential contributor.

For those projects using GitHub as a public backlog, work items will be 'GitHub issues' tagged as 'Welcome
Contributions'. The assignment process will consist of a comment made by the contributor on the corresponding GitHub
issue, indicating the intent to fix the issue. A mentor can decide to acknowledge the request by actually assigning the
issue. Nonetheless, the Mentor will have the final assignment decision depending on the proved skills of the requester.

_Spontaneous contributions_ (i.e. contributions not associated with any welcome contributions published by the FIWARE
Generic Enabler owners) **MAY** be accepted if the FIWARE Generic Enabler development staff consider them valuable.

Contributions **MUST** follow the standard FIWARE [Development Lifecycle](development.md#Development_Lifecycle) and the
advice given by mentors. The contributor's role includes:

-   Regular communication (at least once a week) with the mentor; the mentor needs confidence that the task is moving in
    a good direction.

-   Respect the mentor's guidance, particularly with regards to patch submission and reviews.

Credits **MUST** be given to external contributors. A _CREDITS_ file **MUST** be present at the root directory of the
FIWARE Generic Enabler code repository. The format of that file SHOULD use some of the following alternatives (it's up
to each FIWARE Generic Enabler team to chose which option they prefer):

-   One line per contributor to the project. An example can be found
    [here](https://github.com/nodejs/node/blob/master/AUTHORS).

-   A short list of major contributors and a link to the contributors graph in the GitHub repository. An example can be
    found [here](https://github.com/Kotti/Kotti/blob/master/AUTHORS.txt)

-   A list of contributors and the detail of their particular contributions. An examples can be found
    [here](https://github.com/sinatra/sinatra/blob/master/AUTHORS.md).

The public **backlog organization** for _Welcome Contributions_ **SHOULD** be as follows:

-   All the work items which are suitable for external contributions (_Welcome Contributions_) will be tagged as
    _'mentored'_.

-   A good Welcome Contribution requires:

    -   A clear description of the problem, and steps to reproduce (if applicable).
    -   A broad description of what an acceptable solution to the problem would look like.
    -   Clear steps that should be taken for the fix - including links to the lines of code to be tweaked.
    -   Identification of any relevant automated tests, as well as instructions for adding any new tests.
    -   Links to relevant documentation (eg. if running automated tests, link to the page and even give the full
        command).

-   Every _Welcome Contribution_ will have a category which will denote its difficulty and importance level:
    -   **Entry**. Entry level work items are typically low complexity tasks such as those which have to do with simple
        (one liner) bug fixing. It includes an extremely narrow scope, clear hardware and platform requirements, and
        prompt reviewer followup. They are aimed at making a new contributor familiar with the development environment
        and workflow.
    -   **Intermediate**. These are less trivial tasks and are focused on actually providing a solution to an issue
        identified. Few if any of these will be good starting points for new contributors. Actually, they are aimed at
        those contributors who have completed successfully at least one or two entry level work items.
    -   **Advanced**. These are work items which difficulty is high or that have been brought up as important issues by
        the priority-triage processes. Previous experience in the project will be a must in order to be commissioned to
        the task.

*   Repositories which are open to contributions GitHub **SHOULD** comply with the GitHub recommended community
    standards checklist by having a `CONTRIBUTING.md` - see the associated
    [Git Hub Article](https://help.github.com/articles/setting-guidelines-for-repository-contributors/).

*   Repositories which are open to contributions GitHub **MAY** require a pull request template - see associated
    [Git Hub Article](https://help.github.com/articles/creating-a-pull-request-template-for-your-repository/).
*   Presence of a `CODE_OF_CONDUCT.md` **MAY** also be useful - see associated
    [Git Hub Article](https://help.github.com/articles/adding-a-code-of-conduct-to-your-project/). It should noted that
    FIWARE members should have already signed the
    [FIWARE Code of Conduct](https://www.fiware.org/foundation/code-of-conduct/).
*   Repositories which are open to contributions GitHub **SHOULD** automate code formatting (e.g. Go fmt,
    prettier/ESLint for Node.js, Jacobe or Checkstyle for Java, etc.).

## Recognitions

Apart from the presence on the credits file, different recognitions can be given to external contributors. Some ideas,
coming from the GitHub Open Source Guides can be found [here](https://opensource.guide/).

The greater recognition that can be made to a contributor is promotion to the 'active contributor' role (see
[here](https://docs.google.com/spreadsheets/d/183li2rrkTM4fPpgYWUc3czL5pB9MdbyFJXnCXE3-Mjo/edit?usp=sharing)). These
decision **MUST** be made by the FIWARE Generic Enablers owners taking into account the number, quality and
sustainability in time of the contributions provided.
