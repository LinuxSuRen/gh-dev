A [gh](https://github.com/cli/cli) extension with some enhancement features.

## Installation

```shell
gh extension install linuxsuren/gh-dev
```

## Usage

The command format is: `gh dev sub-command`.

### Open in browser

You could run this command in a git repository directory:

```shell
gh dev open
```

This command supports the following platform:

* Linux
* macOS
* WSL (Windows Subsystem Linux)

### Clone GitHub repository from a mirror

It is helpful when you try to clone a BIG repository. The following command will clone into directory `kubernetes/kubernetes`.

```shell
gh dev clone kubernetes/kubernetes
```

### Checkout to a MR in a Gitlab repository

```shell
gh dev mrCheckout 1 # or gh dev mrCo 1
```

## Thanks

This project is inspired from [gh-gp](https://github.com/gitpod-io/gh-gp).
