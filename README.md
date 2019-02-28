workshop-base-template
===

> === DELETE BELOW THIS LINE ==============

## Information for the Author

This repository should be used as a basic template for building new workshops.

The primary `README.md` file in each branch should contain an overview of the topics
being covered in that module. The `master` branch should provide a wholistic overview
of the topics covered by the entire workshop.

The `master` branch `README.md` file should serve as an appropriate landing page
for complete newcomers to the repository / workshop. 
Expect that other people will link to this repository / workshop, and they will
most likely land on this page.

Keep summaries short --- one or two paragraphs is fine.
Detailed discussion of architectural topics should be done in each module
or potentially in a standalone page linked from the module's `README.md`.

### Structure

To keep the workshop as clean as possible, segregate each module into its own working branch.

```
[REPOSITORY]
  |- master            :: High-level description of the workshop.
  |- module-01         :: Each module should have a base branch. 
  |  |- feature/xxx    :: Module base branches should have their own working branches.
  |  |- bug/xxx
  |  |- chore/xxx 
  |  |- ...
  |
  |- module-02         :: Module base branches should be treated as master for that module.
  |  |- ...
  |
  |- ...
```

> === DELETE ABOVE THIS LINE =================

## Prerequisites

Provide a list of prerequisites that are required to successfully complete your workshop. 
This should include things like:

- setting up an AWS account
- installing and configuring tools (e.g. AWS CLI, Node.js, Docker runtime)
- etc.

If there are specific skills or technologies students need to have existing knowledge of,
they should also go in here.

Feel free to add a subsection for each prerequisite if you need to add in more detail.

## Modules

A workshop consists of multiple modules. 
Each module should cover a single, cohesive topic and take between **30** and **60** minutes for all students to complete.
Consider the least experienced students who are likely to take this workshop when scoping your modules.

Provide a numbered list of your modules, and link to their respective branches.
To link to a branch, use:

```
[a link to a module branch](/:org:/:repo:/tree/:branch:)
```

where `:org`, `:repo:`, and `:branch:` are replaced by their corresponding values.

1. [Example Module](/team-siklab/workshop-base-template/tree/module-01)
2.
