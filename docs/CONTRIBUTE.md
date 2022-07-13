# Contributing to the GCT Documentation

MkDocs is a static site generator used to build documentation for the [Gravity Creator Technologies GitHub Page](https://github.com/gravitycreatortechnologies/docs).

The following sections will give you instructions on how to properly make changes to the documentation. If you have questions, please reach out to the any of the [codeowners](https://github.com/gravitycreatortechnologies/docs/.github/CODEOWNERS).

## Prerequisites

Using MkDocs is relativeliy simple and all team members are encouraged to participate in contributing documentation. There is, however, a certain level of technical detail contributors need to be aware of before proceding. Not understanding these prerequisites may cause lost time and headaches down the road. You do not have to be an expert at these concepts, but before continuing forward, please have an understanding of the following:

### Git Basics

- [Learning resource on Git](https://try.github.io/)
- [How to clone a repository](https://help.github.com/articles/cloning-a-repository/)
- [How to create a branch](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging)
- [How to commit changes](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository)
- [How to push changes to Github](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/)
- [How to pull changes in Github](https://git-scm.com/docs/git-pull)

### MkDocs Basics

- [How to write documentation in markdown](https://guides.github.com/features/mastering-markdown/)
- [Adding new pages to MkDocs with navigation](https://www.mkdocs.org/#adding-pages)
- [How to serve MkDocs locally and see your changes](https://www.mkdocs.org/#getting-started)

### GitHub Basics

- [How to create a pull request](https://help.github.com/articles/creating-a-pull-request/)
- [Assigning a Pull Request to a Reviewer](https://help.github.com/articles/assigning-issues-and-pull-requests-to-other-github-users/)

In addition, you have the ability utilize either the [Github Desktop](https://desktop.github.com/) or [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line) to interact with the doucmentation. If you are a beginner at using Github or Git, please consider utilizing the Github GUI.

- [Download Github Desktop here](https://desktop.github.com/)
- [Download Git CLI here](https://git-scm.com/downloads)

You will also need access to the [gravitycreatortechnologies/docs](https://github.com/gravitycreatortechnologies/docs) repository with write permissions.

## Git and GitHub Setup

Once you've completed the prerequisites, please follow the instructions to create and submit changes to the documentation.

### Git CLI Instructions

1. Clone the repository in your directory of choice:

`$ git clone git@github.com:gravitycreatortechnologies/docs.git`

2. Change your directory to the location of mkdocs:

`$ cd mkdocs`

3. Create a new feature branch to begin development:

`$ git checkout -b my-cool-feature`

4. At this stage, you're ready to start making changes and adding to the documenation. When you're ready to submit your changes for approval, please push your request:

`git push origin my-cool-feature`

### GitHub Desktop Instructions

1.  [Clone the repository in your directory of choice.](https://help.github.com/desktop/guides/contributing-to-projects/cloning-a-repository-from-github-to-github-desktop/).

2.  [Create a new feature branch to begin development](https://help.github.com/desktop/guides/contributing-to-projects/creating-a-branch-for-your-work/).

3.  In your file explorer, navigate the the `docs` folder inside the repository you just cloned. This is the location of the documenation you will be changing. You can use any text editor or IDE you wish to make your changes. At this stage, you're ready to start making changes and adding to the documenation.

4.  When you're ready to submit your changes for approval, [please commit your changes and push your changes to Github.](https://help.github.com/desktop/guides/contributing-to-projects/committing-and-reviewing-changes-to-your-project/).

## MkDocs Local Development Setup

**The current setup assumes you're working on a Mac and have Python/Pip (Version 2 or 3) [installed](https://www.python.org/downloads/).**

The following steps can only be completed inside of a terminal via command line. These steps are necessary to be able to view the documenation locally on your system utilizing `mkdocs serve`. While not necessary for small changes, we highly recommend you install these tools to be able to see your changes in your own local environment before pushing to production.

To install MkDocs locally, follow these steps:

1. Install the MkDocs python library:

`$ pip install mkdocs` or `$ pip3 install mkdocs`

2. Install the `material` theme:

`$ pip3 install mkdocs-material` or `$ pip install mkdocs-material`

3. Build and view your changes:

`$ mkdocs serve`

In your web browser, navigate to `http://localhost:8000` to view the local version of the documenation.

If you leave the mkdocs server running in your terminal, the content will be live reloaded in your browser as you make changes to the documentation.

When adding documentation follow the [MkDocs documentation style guidelines](https://www.mkdocs.org/user-guide/styling-your-docs/).

## Merging Changes on Github

Once your changes are pushed, you will now need to merge your changes via a pull request. Please utilize the following steps:

Go to the docs repository and [open a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).

Per our policy, your pull request needs to be reviewed before being merged. When creating a pull request, please assign a relevant team member or manager affected by the documenation change.

Once assigned, your pull request will be approved and then can be merged.

Once this pull request is approved and merged, your changes will be live on the [Gravity Creator Technologies GitHub Page](https://pages.github.com/gravitycreatortechnologies/docs).
