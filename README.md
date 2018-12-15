## Important Note

This repository is SLAC National Accelerator's develop fork of GridLAB-D (see https://github.com/gridlab-d/gridlab-d).  Only SLAC projects may contribute to this fork.  Changes made in this fork will be migrated back to PNNL's official repository at PNNL's discretion.

# SLAC Workflow

## Projects

SLAC has a number of active projects making contributions to the SLAC development fork.  Project are encouraged to use the `master` branch. Project may use a sub-master branch named `project-master`, which can be used to consolidate PRs from multiple project-specific branches.

## Issues

Issues may be contributed by project team members at any time.  The author of the issues should specify the label, originating project, milestone, and an initial assignment if possible. Please provide any detail and supporting data necessary to reproduce the issue.

## Branches

Branches are created to address a single issue.  A comment should be added to the issue to indicate which branch is being used to address it.  If the branch is addressing multiple issues, pick one issue to use as the primary issue, and have all the other issues refer to the primary issue as well.

Branches are named using the lead developer and topic, e.g., `username/topic`. Commits and pushes of the branch should be made as soon as work is initiated in order to facilitate review and discussion. Once the branch is started, discussion should take on the PR page and the issue should only be used to add new information relating to the issue not captured in the PR record.

## Pull Request

A pull request should be opened as soon as work on the branch is pushed.  Initially the PR should have a the same title as the primary issue it is intended to address. The title should include a prefix tag `[WORKING]` indicating the initial working status.  

When the PR is initially created, the first comment must include the following information:
~~~
This PR addresses issue #XYZ.

The current status of the PR is:
1. list of open questions/problems

The affected wiki page(s) are:
- [[link to page]]
~~~
All discussion regarding the branch must be recorded on the PR, rather than on the issue.  

The following prefix tags are the recognized:

1. `[WORKING]` -- The PR is current work in progress.  A reviewer may be assigned as a courtesy to offer the opportunity to consider the changes while work is still in progress. The PR may be merged, but the PR and the branch must not be deleted while work is in progress. While work is in progress the PR is assigned to the lead.  When the lead determines that the work is complete, the tag is changed to `[REVIEW]` and makes the file reviewer selection(s).  The PR remains assigned to the lead until the review is completed. _NOTE_: the changes must include wiki updates, if any, and the opening PR comment must cite the wiki pages added or changed.

1. `[REVIEW]` -- The PR is ready for final review.  The reviewer is charged with ensuring that the proposed changes address the issue(s) satisfactorily.  If the review is successful, the reviewer makes a comment to that affect and changes the assignment to a developer other than the lead to perform the merge.  If the review is unsuccessful, the review makes any necessary comments, and changes the tag back to `[WORKING]` to indicate that the lead must address the questions. _NOTE_: the review must include review of the wiki pages added or changed, if any.

1. `[HOLD]` -- The PR is on hold pending future resolution by the lead developer.  No further work is expected and the PR should not be merged at this time.



