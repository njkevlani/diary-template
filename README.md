# diary-template

A template to write and read diary using bash, git, (neo)vim and hugo.

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

Setup this repo as upstream remote (needed one time).

```shell
git remote add upstream https://github.com/njkevlani/diary-template
```

To fetch the latest changes added to the template, use the following steps.

```shell
git fetch upstream
git merge upstream/main
```

# Encryption

> [!NOTE]
> Not necessary, but highly recommended that you use <https://github.com/AGWA/git-crypt>
> to encrypt the content of your diary.

Steps to setup encryption are:

```shell
git-crypt init
git-crypt add-gpg-user <email-for-gpg>
```

Check out git-crypt repo for other ways to encrypt repo.
