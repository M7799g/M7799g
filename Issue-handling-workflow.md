### (Draft proposal)

* Based on
    * [How We Use GitHub Issues To Organize a Project](http://www.ianbicking.org/blog/2014/03/use-github-issues-to-organize-a-project.html)
    * [Issues · facebook/react](https://github.com/facebook/react/issues)
* Labels
    * Type
        * Error / Bug
        * Enhancement
    * Status
        * needs_more_info
        * in_progress
        * pr_review
        * needs_discussion
    * Component
        * Whisper
        * Swarm
        * Clef
        * Android
        * ...
* Milestones
    * \<current\>
    * [Next tasks](https://github.com/ethereum/go-ethereum/milestone/81)
    * [Backlog](https://github.com/ethereum/go-ethereum/milestone/80)
* Projects -- We use projects for a larger chunk of work with a specific outcome. A project can overarch multiple releases (its issues may be in multiple milestones), but it has an end.
* Workflow
    * We have a weekly or bi-weekly triage meeting. This is when we go through the new issues and do one of the following
        * Close it.
        * Assign it to the "Next tasks" milestone which doesn't have an end date.
        * Move it to the Backlog milestone.
        * Change its status to "Needs more information" or "Needs discussion".
