Contributing
=========

* [Prerequisites](#prerequisites)
* [Useful commands](#useful_commands)
* [Commits](#commits)

## Prerequisites

You need NodeJS installed in order to contribute to this project.

Instead of installing NodeJS, you can use docker and put these scripts in your $PATH :

### npm

```bash
#!/bin/bash
# npm
docker run \
    --rm \
    -it \
    -u $(id -u):$(id -g) \
    -v "$(pwd)":/app \
    --workdir /app \
    node \
    npm $@
```

### node

```bash
#!/bin/bash
# node
docker run \
    --rm \
    -u $(id -u):$(id -g) \
    -v "$(pwd)":/app \
    --workdir /app \
    node \
    node $@
```

## Useful commands

### Installation

```bash
npm i;
```

### Tests

```bash
npm run test;
```

### Code coverage

```bash
npm run cover;
```

### Lint

```bash
npm run lint;
```

## Commits

Before committing any piece of code, make sure you added/modified the corresponding tests.

Some pre-commit hooks are here to make sure that :
* Every test passes ([Tests](#tests))
* Every piece of code is tested ([Coverage](#coverage))
* The code is written in a consistent way ([Lint](#lint))
