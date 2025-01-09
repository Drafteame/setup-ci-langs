# Setup CI Langs

Set of actions to install and configure different languages and tools.

## Available Languages

| Language | Default Version | Comments                           |
|----------|-----------------|------------------------------------|
| NodeJS   | 18              |                                    |
| Go       | 1.22.x          |                                    |
| Python   | 3.11.x          | Install poetry when enabled        |
| PKL      | 0.25.3          |                                    |
| GIT      | 2.9.5           | Always try to install if not found |

## Action Inputs

### General
| Input      | Description             | Default |
|------------|-------------------------|---------|
| enable-all | Enable all languages    | false   |

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
| python-version          | Python version          | 3.12.x  |
| python-poetry-version   | Poetry version          | 1.8.3   |

### PKL

| Input                   | Description             | Default |
|-------------------------|-------------------------|---------|
| pkl                     | Enable PKL              | false   |
| pkl-version             | PKL version             | 0.26.0  |
