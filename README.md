# Setup CI Langs

Set of actions to install and configure different languages and tools.

## Available Languages

| Language | Default Version |
|----------|-----------------|
| NodeJS   | 20              |
| Go       | 1.22.x          |
| Python   | 3.11.x          |
| PKL      | 0.25.3          |

## Action Inputs

### Node

| Input                   | Description             | Default |
|-------------------------|-------------------------|---------|
| node                    | Enable NodeJS           | false   |
| node-working-directory  | Node working directory  |         |
| node-cache-key-suffix   | Node cache key suffix   |         |
| node-version            | Node version            | 20      |

### Go

| Input                   | Description             | Default |
|-------------------------|-------------------------|---------|
| go                      | Enable Go               | true    |
| go-version              | Go version              | 1.22.x  |

### Python

| Input                   | Description             | Default |
|-------------------------|-------------------------|---------|
| python                  | Enable Python           | false   |
| python-version          | Python version          | 3.11.x  |

### PKL

| Input                   | Description             | Default |
|-------------------------|-------------------------|---------|
| pkl                     | Enable PKL              | false   |
| pkl-version             | PKL version             | 0.25.3  |
