# After-Party project tracking

This document describes how we track issues for the After-Party tracking on the project board is at <https://github.com/orgs/sanger-tol/projects/3>.

# Standard fields

### Status

Our workflow has three main steps:

- _Todo_: This item hasn't been started.
- _In progress_: This is actively being worked on.
- _Done_: This has been completed.

with the addition of:

- _Triage_: This item first needs to be confirmed or refined. _Triage_ is optional, but would typically be used before _Todo_.
- _Blocked_: This item is waiting on another one and can't be worked on.

### Priority

We follow a simple model with three priority levels:

- High: This item is absolutely needed for Production. Approximately equivalent to a _must_ requirement.
- Medium: We want to implement this item and we'll move onto it as soon as we've got time. Approximately equivalent to a _should_ requirement.
- Low: Other items we _could_ implement. We're unlikely to work on it in the short term.

### Type

We use the default issue types from GitHub:

- Bug
- Feature
- Task

### Labels

Most issues are expected to be about the code (software), but we have those two labels for non-code issues:

- https://github.com/sanger-tol/.github/labels/documentation : Improvements or additions to documentation
- https://github.com/sanger-tol/.github/labels/testing : Code testing

These labels are used to indicate why an issue is closed early:

- https://github.com/sanger-tol/.github/labels/duplicate : This issue or pull request already exists
- https://github.com/sanger-tol/.github/labels/invalid : This doesn't seem right
- https://github.com/sanger-tol/.github/labels/wontfix : This will not be worked on

External contributors can look for these labels:

- https://github.com/sanger-tol/.github/labels/good%20first%20issue : Good for newcomers. Used for well-defined, isolated tasks that don't require too much prior knowledge about the pipeline.
- https://github.com/sanger-tol/.github/labels/help%20wanted : Open to anyone interested. Used for tasks that don't clash with other internal developments, and for tasks that would benefit from community input.

Finally:

- https://github.com/sanger-tol/.github/labels/maintain : Tasks to keep pipelines up to date
- https://github.com/sanger-tol/.github/labels/question : Further information is requested
- https://github.com/sanger-tol/.github/labels/user%20request : Requests made by users and public

## Guidelines

Labels should follow the following rules:

1. All issues with https://github.com/sanger-tol/.github/labels/duplicate, https://github.com/sanger-tol/.github/labels/invalid, or https://github.com/sanger-tol/.github/labels/wontfix label, should be _Done_.
2. All issues in _Triage_ should have the https://github.com/sanger-tol/.github/labels/question label.
3. No _High_ priority issues should have the https://github.com/sanger-tol/.github/labels/help%20wanted label. This is to ensure we don't clash.
4. All issues with the https://github.com/sanger-tol/.github/labels/good%20first%20issue label should have https://github.com/sanger-tol/.github/labels/help%20wanted too.
