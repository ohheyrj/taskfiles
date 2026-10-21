# taskfiles

A collection of reusable [Task](https://taskfile.dev) files that can be shared across projects.

## Layout

| Directory | Description |
|-----------|-------------|
| `github/` | Tasks for working with GitHub |

## Usage

Include a taskfile from this repo in your project's `Taskfile.yml` using [remote taskfiles](https://taskfile.dev/experiments/remote-taskfiles/):

```yaml
version: '3'

includes:
  github: https://raw.githubusercontent.com/ohheyrj/taskfiles/main/github/Taskfile.yml
```

Then list the available tasks:

```sh
task --list
```

## Requirements

- [Task](https://taskfile.dev/installation/) v3
