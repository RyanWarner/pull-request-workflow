### Pull Request Github Flow for Non Developers


# Why?

- The logic and flow that happens in a Git Pull Request is valuable across multiple disciplines, and in life.
- Asking for peer review makes you and your reviewer better at what they do.
- Version control provides the history and evolution of a project or document.
- Keep you responsible for your changes. People know who to contact about specific pieces.
- Helps you better understand the developers you work with. Language, thought process, etc.
- Everyone involved gets notified (automatically) when changes are proposed or commented on or adopted via Github Slack integration.
- Useful skills to have.

## Install Git

[git-scm.com/downloads](http://git-scm.com/downloads)

[image 1]

## Configuration

Taken from [https://help.github.com/articles/set-up-git/](https://help.github.com/articles/set-up-git/).

1. Open Terminal
2. `git config --global user.name "YOUR NAME"`
3. `git config --global user.email "YOUR EMAIL ADDRESS"`

## Authentication

[https://help.github.com/articles/caching-your-github-password-in-git/](https://help.github.com/articles/caching-your-github-password-in-git/)

## Creating a Repository

1. Login to Github
2. Create new repository

[image]

## Cloning a Repository

`git clone git@github...`

## Creating a Branch

`git checkout -b YOUR_BRANCH`

## Writing Markdown

[Markdown Syntax](http://daringfireball.net/projects/markdown/syntax)

[Images](https://help.github.com/articles/adding-images-to-wikis/)

[MacDown](http://macdown.uranusjr.com/)

## Committing Changes

`git add .`

`git commit -am "description of changes"`

## Pushing Changes

`git push origin YOUR_BRANCH`

## Creating a Pull Request

"Here are some changes that I think are ready to be adopted, can you review them?"

[images detailing steps of creating a pr]

## Merging a Pull Request

After your proposed changes are approved by your peers, it is your responsibility to merge those changes.