### (Draft proposal)
Keep the number of open issues under 820

Keep the ratio of open issues per all issues under 13%

Have 50 issues labelled [help wanted](https://github.com/ethereum/go-ethereum/labels/help%20wanted) and 50 [good first issue](https://github.com/ethereum/go-ethereum/labels/good%20first%20issue).

Use structured labels of the form `<category>:<label>` or if need be `<category>:<main>/<sub>`, for example `area: plugins/foobuzzer`.

Use the following labels. Areas and statuses depend on the application and workflow.
- area
    - `area: android`
    - `area: clef`
    - `area: network`
    - `area: swarm`
    - `area: whisper`
- type
    - `type: bug`
    - `type: feature`
    - `type: documentation`
    - `type: discussion`
- status
    - `status: PR review`
    - `status: community working on it`
- need
    - `need: more info`
    - `need: steps to reproduce`
    - `need: investigation`
    - `need: decision`

Use these milestones
- [Future](https://github.com/ethereum/go-ethereum/milestone/80) - Maybe implement one day
- [Coming soon](https://github.com/ethereum/go-ethereum/milestone/81) - Not assigned to a specific release, but to be delivered in one of the upcoming releases
- \<next version\> - Next release with a version number
- \<next-next version\> - The version after the next release with a version number
- \<next major release\> - Optional.

It's ok to not set a due date for a milestone, but once you release it, close it. If you have a few issues dangling, consider moving them to the next milestone, and close this one.

Optionally, use a project board to collect issues of a larger effort that has an end state and overarches multiple releases.

* Workflow
    * We have a weekly or bi-weekly triage meeting. This is when we go through the new issues and do one of the following
        * Close it.
        * Assign it to the "Next tasks" milestone which doesn't have an end date.
        * Move it to the Backlog milestone.
        * Change its status to "Needs more information" or "Needs discussion".