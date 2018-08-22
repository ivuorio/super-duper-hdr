# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. 

## Getting started

1. Fork this repository. This creates a new repository. Let's assume it's https://github.com/EXAMPLE/super-duper-hdr.
2. Clone the forked repository. Your local repository should now have git@github.com:EXAMPLE/super-duper-hdr.git as origin.
Run `git remote add upstream git@github.com:mapehe/super-duper-hdr.git`. You should now have two remotes: origin and upstream.
3. Proceed to the "Making changes" section.

## Making changes

1. Keep the master branch up to date with upstream by running `git pull upstream master` when your local repo is behind.
2. Always make changes to a branch other than master. Run `git checkout -b [branch name]` to create one.
3. Write code, commit often. When done, fix any errors in `git diff master --name-only -- "*.py" | xargs -r flake8`.
4. When the changes are production-ready run `git rebase -i master` (make sure you are in a branch that contains your changes)
and squeeze the changes to a single commit.
5. Write a commit message with a title no longer than 50 characters, leave a blank line and include explanatory text as needed,
wrapped at 72 characters or so.
6. Proceed to the "Pull request process" section.

## Pull Request Process

1. Push your single commit that contains your changes to a remote branch other than the master branch via `git push origin [branch name]`.
2. Create a pull request with a message that explains the changes. Provide a link to the related issue if there is one.
3. The maintainers will be in touch with you.

