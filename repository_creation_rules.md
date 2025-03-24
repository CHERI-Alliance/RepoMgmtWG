# CHERI alliance repository creation rules

The objective for this document is to set out the rules of engagement for CHERI alliance repositories.
If you any of these rules are unclear you can contact the repository working group at [this email](mailto:wg-repo-mgmt@cheri-alliance.org).

## Creation

If a working group wants a repository they can create one as long as there is no naming clash.
If there is a naming clash, this should be referred to the repository management working group.
If a repository applies to multiple working groups, they can decide this together.
If there is a disagreement between working groups, this should be referred to the repository management working group.
If someone wants to create a repository without an existing working group, please contact the repository management working group.

When creating a new repository that is similar to one that already exists, this should be discussed with the existing working group or person responsible for the already existing repository.
On a general note, we prefer maintaining branches on an existing repository unless there is a good reason not to.

In all cases, when a repository is created, it should have an initial responsible working group or person.
For public repositories please open an issue on this repository.
In this issue it should also be clear if this is a fork of an existing repository and the expected lifetime of the project.
Short-term projects can be those where it's a staging ground for upstreaming, while longer-term projects can be those where the CHERI alliance sees a need to support the community or fill a gap.
For private repositories please send an email to the repository management working group.

## License

When creating a repository these are usually based on existing projects with existing licenses.
Projects with well-known open-source licenses like those defined by the [OSI](https://opensource.org/licenses?categories=popular-strong-community) should be fine.
If you have any doubt, please contact the repository management working group.

If this is a completely new project, we prefer [permissive licenses](https://en.wikipedia.org/wiki/Permissive_software_license).

## Guidelines for repositories

These are not mandates but are some best practices any active repository should consider:
- Protected main branch.
- Pull requests for contributions including code review.
- Commits should be atomic where any part of history is in a buildable and runnable state.
- Decide and clearly state whether you prefer merging or rebasing flow.
- Define how to manage those with write access.
- Have a meaningful one-line description in the "About" section.
