# Embers

# Request Support

If you have a question about this project, how to use it, or just need clarification about something:

- Open an Issue at <https://github.com/lyricwulf/embers/issues>
- Provide as much context as you can about what you're running into.

Once it's filed:

- The project team will [label the issue](#label-issues).
- Someone will try to have a response soon.
- If you or the maintainers don't respond to an issue for 30 days, the [issue will be closed](#clean-up-issues-and-prs). If you want to come back to it, reply (once, please), and we'll reopen the existing issue. Please avoid filing new issues as extensions of one you already made.

# Report an Issue

If you run into an issue with the project:

- Open an Issue at <https://github.com/lyricwulf/kb/issues>

Once it's filed:

- The project team will [label the issue](#label-issues).
- If you or the maintainers don't respond to an issue for 30 days, the [issue will be closed](#clean-up-issues-and-prs). If you want to come back to it, reply (once, please), and we'll reopen the existing issue. Please avoid filing new issues as extensions of one you already made.
- `critical` issues may be left open, depending on perceived immediacy and severity, even past the 30 day deadline.

# Request a Feature

If the project doesn't include something you need or want:

- Open an Issue at <https://github.com/lyricwulf/kb/issues>
- Please try and be clear about why existing docs do not work.

Once it's filed:

- The project team will [label the issue](#label-issues).
- The project team will evaluate the edit request, possibly asking you more questions to understand its purpose and any relevant requirements. If the issue is closed, the team will convey their reasoning and suggest an alternative path forward.
- If the edit request is accepted, it will be marked for implementation with `edit-accepted`, which can then be done by either by a core team member or by anyone in the community who wants to [contribute edits](#contribute-edits).

Note: The team is unlikely to be able to accept every single edit request that is filed. Please understand if they need to say no.

# Label Issues

[Needs Collaborator](#join-the-project-team): Issue Tracker

One of the most important tasks in handling issues is labeling them usefully and accurately. All other tasks involving issues ultimately rely on the issue being classified in such a way that relevant parties looking to do their own tasks can find them quickly and easily.

In order to label issues, [open up the list of unlabeled issues](https://github.com/lyricwulf/kb/issues?q=is%3Aopen+is%3Aissue+no%3Alabel) and, **from newest to oldest**, read through each one and apply issue labels according to the table below. If you're unsure about what label to apply, skip the issue and try the next one: don't feel obligated to label each and every issue yourself!

Label           | Apply When                                                                                                                                                                                                                                                                                                    | Notes
--------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
`bug`           | Cases where something behaves in a way it wasn't intended.                                                                                                                                                                                                                                      | If something surprises the _user_ but does not go against the way the project is designed, it should use the `enhancement` label.
`critical`      | Added to `bug` issues if the problem described makes the project completely unusable in a common situation.                                                                                                                                                                                                       |
`documentation` | Added to issues that affect any of the documentation for the project.                                                                                                                                                                                                                        | Can be combined with other labels, such as `bug` or `enhancement`.
`duplicate`     | Added to issues or PRs that refer to the exact same issue as another one that's been previously labeled.                                                                                                                                                                                                      | Duplicate issues should be marked and closed right away, with a message referencing the issue it's a duplicate of (with `#123`)
`enhancement`   | Added to [edit requests](#request-a-edit), PRs, or documentation issues that are purely additive: the project behaves as expected, but a feature is being requested or suggested.                                                                                                                         |
`help wanted`   | Applied by [Committers](#join-the-project-team) to issues and PRs that they would like to get outside help for. Generally, this means it's lower priority for the maintainer team to itself implement, but that the community is encouraged to pick up if they so desire                                      | Never applied on first-pass labeling.
`in-progress`   | Applied by [Committers](#join-the-project-team) to PRs that are pending some work before they're ready for review.                                                                                                                                                                                            | The original PR submitter should @mention the team member that applied the label once the PR is complete.
`performance`   | This issue or PR is directly related to improving performance.                                                                                                                                                                                                                                                |
`refactor`      | Added to issues or PRs that deal with cleaning up or modifying the project for the betterment of it.                                                                                                                                                                                                          |
`support`       | This issue is either asking a question about how to use the project, clarifying the project features, or possibly reporting a `bug` but does not have enough detail yet to determine whether it would count as such.                                                                                |
`wont-add`      | Labelers may apply this label to issues that clearly have nothing at all to do with the project or are otherwise entirely outside of its scope/sphere of influence. [Committers](#join-the-project-team) may apply this label and close an issue or PR if they decide to pass on an otherwise relevant issue. | The issue or PR should be closed as soon as the label is applied, and a clear explanation provided of why the label was used. Contributors are free to contest the labeling, but the decision ultimately falls on committers as to whether to accept something or not.
