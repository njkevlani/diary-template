# diary-template

A template to write and read diary using bash, git, (neo)vim and hugo.

> **Note**
> Not necessary, but highly recommended that you use <https://github.com/AGWA/git-crypt>
> to encrypt the content of your diary. Check out its repo for its setup details.

# Workflow

Fork this repo to get started.

## Writing

Use `write` CLI for wring. Check help page for more details on usage.

```shell
./write --help
```

## Reading

```shell
hugo server
```

# Updating template

To fetch the latest changes added to the template, use the following steps.

```shell
git remote add upstream https://github.com/njkevlani/diary-template
git fetch upstream
git merge upstream/main
```
