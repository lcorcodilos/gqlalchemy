# How to contribute to GQLAlchemy?

## Code of Conduct

Everyone participating in this project is governed by the [Code of
Conduct](https://github.com/memgraph/memgraph/blob/master/CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code. Please report
unacceptable behavior to <tech@memgraph.com>.

## Reporting Bugs

This section guides you through submitting a bug report for **GQLAlchemy**.
Following these guidelines helps maintainers and the community understand your
report, reproduce the behavior, and find related reports.

Before creating a bug report, please check out [GitHub
Issues](https://github.com/memgraph/gqlalchemy/issues), as you might find out
that you don't need to create one. When you are creating a bug report, please
**include as many details** as possible. Fill out [the required
template](https://github.com/memgraph/gqlalchemy/blob/main/.github/ISSUE_TEMPLATE/bug_report.md),
so we can get all the needed information to resolve the issue.

> **Note:** If you find a **Closed** issue that seems like it is the same thing
> that you're experiencing, open a new issue and include a link to the original
> issue in the body of your new one.

## The codebase and branches

### Branch `main`

The base branch of the project is the **`main`** branch. Whenever there is a change on the `main` branch, a new release of GQLAlchemy is created in the [GitHub repository](https://github.com/memgraph/gqlalchemy/releases) and on [PyPI](https://pypi.org/project/GQLAlchemy/). 

### Branch `develop`

The **`develop`** branch is where new releases of GQLAlchemy are developed. You can track the progress of each release through [GitHub Projects](https://github.com/memgraph/gqlalchemy/projects?type=beta). When the release is finished, the `develop` branch will be merged into `main` and the newly updated `main` branch will be used to create a new release. 

## Contributing new features or bug fixes

Please send a GitHub [Pull
Request](https://github.com/memgraph/gqlalchemy/pulls) with a clear list of what
you've done. Make sure all of your commits are atomic (one feature per commit).

There are two main types of contributions:
1. **Critical bug fixes**
2. **New features or low priority bug fixes**

Critical bug fixes should be applied to the `main` branch because a patch release will be created and published once the bug is fixed. Non-critical bug fixes and features can be added to the `develop` branch and will be included in the next planned release.

In order for a pull request to be merged, a review by two code owners is required and the tests need to pass remotely.

## Contact 

If you need help with contributing to the GQLAlchemy project, join our [Discord server](https://discord.gg/memgraph). 
