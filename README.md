# Repository management working group

The objective for this group is to set out the rules of engagement for CHERI alliance repositories.
Besides setting out the rules, this working group should also make sure that each repository has someone who takes responsibility for it and it has a purpose.
To contact this working group, please use [this email](mailto:wg-repo-mgmt@cheri-alliance.org).

## Creation

If a working group wants a repository they can create one as long as there is no naming clash.
If there is a naming clash, this should be referred to this working group.

If a repository applies to multiple working groups, they can decide this together.
If there is a disagreement between working groups, this should be referred to this working group.

If someone wants to create a repository without an existing working group, please get in contact with this working group.

In all cases, when a repository is created, it should have an initial responsbile working group or person.
For public repositories please open an issue on this repository.
In this issue it should also be clear if this is a fork of an existing repository and the expected lifetime of the project.
Short-term projects can be those where it's a staging ground for upstreaming, while longer-term projects can be those where the CHERI alliance needs to provide longer-term suport.
For private repositories please send an email to this working group.

## License

When creating a repository these are usually based on existing projects with existing licenses.
Projects with well-known open-source licenses should be fine.
If you have any doubt, please contact this working group.

If this is a completely new project, we prefer permissive licenses.
Some examples of those can be found on the [Open Source Initiative popular licenses](https://opensource.org/licenses?categories=popular-strong-community).

## Guidelines for repositories

These are not mandates but are some best practices any active repository should consider:
- Protected main branch.
- Pull requests for contributions including code review.
- Commits should be atomic where any part of history is in a buildable and runnable state.
- Decide and clearly state whether you prefer merging or rebasing flow.
- Define how to manage those with write access.

## Notes for this repository

This repository should use rebasing for contributions.
