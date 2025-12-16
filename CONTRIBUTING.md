# Contributing and Getting Involved

👍🎉 First off, thank you for your interest in the AI Alliance initiatives! 🎉👍

### Direct links:

* Receive our [newsletter](https://share.hsforms.com/2Pz_f9vVHRZailCMJ3kmOFQqmmqo)
* [Join](https://www.aialliance.org/join) the AI Alliance
  * Know the specific work group you want to join? [Go here](https://share.hsforms.com/12dRIKDc5SSGUENOtAstjMgqmmqo)
* [Submit a project](https://events.thealliance.ai/aia-project) for us to support or adopt (defined below).
* [Submit a use case](https://qmmqo.share.hsforms.com/2qlmffVx9R8iVNad39JmDPg) for your domain. Help us help you build it!

## Introduction

Here we discuss guidelines you should know if you want to contribute a new project for us to support or adopt or you want to help with an existing project. 

> We welcome feedback and improvements for these guidelines. Use a [pull request](https://github.com/The-AI-Alliance/community/pulls), start a [discussion](https://github.com/orgs/The-AI-Alliance/discussions), or send us [email](mailto:contact@thealliance.ai).

### Two Kinds of Projects

First, we have a flexible governance model for projects, reflected in two types:

* **Core** projects live in the [`The-AI-Alliance`](https://github.com/The-AI-Alliance/) GitHub organization. They are wholly owned by the Alliance and maintained by Alliance members.
* **Supported** projects meet needs that are important to the Alliance, but they are owned and managed elsewhere by Alliance members, with contributions from other Alliance collaborators.

The best way to find out about all the existing projects is to browse `The-AI-Alliance` GitHub organization [README](https://github.com/The-AI-Alliance/) and corresponding [website](https://the-ai-alliance.github.io/). See also the Alliance website [Our Work](https://thealliance.ai/our-work) page, which is the best place to find out about non-coding projects, such as those for education and policy initiatives. 

## What Should I Know Before I Contribute to the Alliance?

We welcome contributions to Alliance projects. Each project repo or website provides specific details about getting involved. Of course, all of them accept pull requests, discussions, etc.

However, we ask that all contributors accept certain agreements and conditions, discussed here. See also the [AI Alliance governance](https://thealliance.ai/governance) for more general information about AI Alliance policies.

### The AI Alliance Code of Conduct

All projects and activities adhere to our [Code of Conduct](https://github.com/The-AI-Alliance/community/blob/main/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. If you observe unacceptable behavior, follow the instructions in the document to report it.

### Developer Certificate of Origin

The AI Alliance utilizes the Linux Foundation’s [Developer Certificate of Origin](https://developercertificate.org/) (DCO) on a per-commit basis to enable contributions to Core Projects. The DCO is your way of affirming to us that your contribution is legally yours to contribute, but it does not require you to give away ownership of the contribution - your IP remains yours and others' IP remains theirs.

Using DCO is discussed in more detail [below](#legal).

### AI Alliance Competition Law Guidelines

The AI Alliance and its members are committed to compliance with applicable antitrust and competition laws. See the [AI Alliance Competition Law Guidelines](https://ai-alliance.cdn.prismic.io/ai-alliance/ZnNNb5m069VX15Z1_AIAllianceCompetitionLawGuidelines.pdf) for details.

## Contributing New Projects or Use Cases

Do you have a project you think the AI Alliance might be interested in? [Submit a project](https://events.thealliance.ai/aia-project) to let us know.

Tell us about your [key domain-specific use cases](https://qmmqo.share.hsforms.com/2qlmffVx9R8iVNad39JmDPg). Help us help you build it and learn how best to apply AI to your domain!

## Processes for Contributing to Existing Projects

For individual contributions to AI Alliance projects, we follow normal _GitOps_ practices. We ask that all work in a particular repo be contributed as a pull request where it will be built and tested automatically (for code changes), reviewed by committers, and merged when accepted. You can skip the rest of this section if this is familiar to you, but be sure to understand our DCO requirement in the [Legal](#legal) section, which is a less common practice.

### Creating a Contribution

As an example, let's use the [`trust-safety-user-guide`](https://github.com/The-AI-Alliance/trust-safety-user-guide) repo.

Before you start working on a contribution to this guide review the [open issues](https://github.com/The-AI-Alliance/trust-safety-user-guide/issues) and [open pull requests](https://github.com/The-AI-Alliance/trust-safety-user-guide/pulls) to see if your contribution or enhancements are already proposed. You might instead be able to join forces with the people already working on these items. If you are unsure about how to contribute an idea, [open an issue](https://github.com/The-AI-Alliance/trust-safety-user-guide/issues) first to discuss your proposal idea with the maintainers.

> **Note:** Review the [Legal](#legal) section below before making any commits to a repo or fork of one.

To contribute to this repo, you'll use the *Fork and Pull* model common in many open source repositories. You can follow this process in a local terminal or in the GitHub web UI.

- For details on the local process, check out the [GitHub flow](https://docs.github.com/en/get-started/using-github/github-flow) documentation from GitHub.
- For details on contributing using the GitHub webpage UI, see [Contributing using the GH UI](docs/contributing_via_GH_UI.md).

When your contribution is ready, you can create a pull request (PR). In general, we follow the standard [GitHub pull request](https://help.github.com/en/articles/about-pull-requests) process. Follow the template to provide details about your pull request to the maintainers. Before submitting pull requests, run any tests or formatting constraints locally that are defined for the repository, if any. For example, does the repo have a `make test` command for running the unit tests?

### Submitting Your Contribution

When submitting your PR, give it a title and description which are as clear and detailed as possible.

### Pull Request Review

After submitting a pull request, maintainers will review it and may make suggestions to fix before merging. It will be easier for your pull request to receive reviews if you consider the criteria the reviewers follow while working. Remember to:

- Run tests (if any) locally and ensure that they pass.
- Ensure your contribution is in the proper format, if defined, e.g., documentation conventions.
- Break large changes into a logical series of smaller patches, which are easy to understand individually and combine to solve a broader issue.
- Follow the project's coding and documentation conventions.

For a list of the maintainers, see the [MAINTAINERS.md](https://github.com/The-AI-Alliance/community/blob/main/MAINTAINERS.md) page.

### Submitting Bug Reports

To submit a new bug report, raise an issue in the appropriate repository before creating a pull request. This ensures that the issue is properly tracked. To fix an existing bug, assign yourself a bug from the issues page of the desired repository. Then, submit a pull request for review.

Bugs are tracked as GitHub issues in the corresponding repo. Many repos also have GitHub projects (overloaded word...) associated with them that provide a dashboard view of work planned, in progress, etc.

## Legal

We have tried to make it as easy as possible to make contributions, including how we handle the legal "necessities" of contribution.

### "Developer Certificate of Origin"

As mentioned previously, we follow the [Developer's Certificate of Origin 1.1 (DCO)][DCO] process to manage code contributions, which is the same approach that [the Linux Kernel community uses][Linux-DCO]. 

We ask that all developers include a sign-off statement in the commit message. Here is an example `Signed-off-by` line, which indicates that the submitter accepts the DCO:

```text
Signed-off-by: John Doe <john.doe@example.com>
```

Fortunately, this is easy to do; it will be included automatically in a git commit using the `-s` flag, as in the following example:

```shell
git commit -s -m 'bug fix' ...
```

> **Tips:** 
>
> * If a commit is created that did not include the `-s` option, the original commit message can be edited by using the `git commit -s --amend` command. A "force push" must be done afterward to add the amended commit to a PR. See this [StackOverflow post](https://stackoverflow.com/questions/13043357/git-sign-off-previous-commits) for more information.
> * Consider creating a git _alias_ that permanently adds the `-s` flag to all commits. For example, here is how to define an alias for this purpose, `cs`:
> 
> ```shell
> git config --global alias.cs "commit -s"
> ...
> git cs -m 'bug fix' ...
> ```
> 
> The alias will be added to your `~/.gitconfig` file.

If you don't want to make this a global alias, omit `--global` and run the command in each repo's root directory where you want to use it. The alias will be added to the `.git/config` file for your local repo clone.

### Licenses

Unless specifically stated otherwise, all Alliance projects are
distributed under a suitable "open" license. We use the following guidelines:

| Purpose | License | Website | SPDX License Identifier |
| :------ | :------ | :------ | :---------------------- |
| Code and Model Weights | [Apache License, Version 2.0](LICENSE.Apache-2.0) | [link](http://www.apache.org/licenses/LICENSE-2.0) | [link](https://spdx.org/licenses/Apache-2.0) |
| Documentation and similar materials | [The Creative Commons License, Version 4.0 - `CC BY 4.0`](LICENSE.CC-BY-4.0) | [link](https://chooser-beta.creativecommons.org/) | [link](https://spdx.org/licenses/CC-BY-4.0.html) |
| Data | [CDLA Permissive 2.0](LICENSE.CDLA-2.0) | [link](https://cdla.dev/permissive-2-0/) | [link](https://spdx.org/licenses/CDLA-Permissive-2.0.html) |

The AI Alliance leaves open the possibility of additional terms concerning safe and responsible use for certain elements in special core projects. For example, some model weights may be open for use, except for harmful purposes. Any decision to use any such additional terms for a core project must be made by the AI Alliance Steering Committee and will be clearly identified in the core project's repository.

> **NOTE:** We discuss various open licenses for data extensively in the [Open Trusted Data Initiative](https://the-ai-alliance.github.io/open-trusted-data-initiative/), specifically [here](https://the-ai-alliance.github.io/open-trusted-data-initiative/dataset-requirements/#yaml-metadata-block) and [here](https://the-ai-alliance.github.io/open-trusted-data-initiative/catalog/#more-about-the-licenses).

[DCO]: https://developercertificate.org/
[Linux-DCO]: https://docs.kernel.org/process/submitting-patches.html#sign-your-work-the-developer-s-certificate-of-origin
