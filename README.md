# Repository management working group

The objective for this group is to set out the rules of engagement for CHERI alliance repositories.
Besides setting out the rules, this working group should also make sure that each repository has someone who takes responsibility for it.
To contact this working group, please use [this email](mailto:wg-repo-mgmt@cheri-alliance.org).

Each repository for the CHERI alliance should add a line in the [repository table](repotable.md).

The rules set out here are currently in **DRAFT** form.

## Creation

If a working group wants a repository they can create one as long as there is no naming clash.
If there is a naming clash, this should be referred to this working group.

If a repository applies to multiple working groups, they can decide this together.
If there is a disagreement between working groups, this should be referred to this working group.

If someone wants to create a repository without an existing working group, please get in contact with this working group.

In all cases, when a repository is created, it should be added to the repository table, which includes the initial responsible working group or person.
When the responsible working group or person changes, this should also be updated.
To update the table please open a pull request to this repository.

## License

When creating a repository these are usually based on existing projects with existing licenses.
Projects with well-known open-source licenses should be fine.
If you have any doubt, please contact this working group.

If this is a completely new project, we prefer permissive licenses like [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0.html).

## Guidelines for repositories

These are not mandates but are some best practices any active repository should consider:
- Protected main branch.
- Pull requests for contributions including code review.
- Commits should be atomic where any part of history is in a buildable and runnable state.
- Decide an clearly state whether you prefer merging or rebasing flow.

## Notes for this repository

This repository should use rebasing for contributions.
