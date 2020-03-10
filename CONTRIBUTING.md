# CONTRIBUTING

This document provides a collection of rules and guidelines that need to be adhered to when working with or contributing to FluidMS.

## Git workflow

### Commit guidelines

For our commit guidelines, we are using [Conventional Commits](https://www.conventionalcommits.org/). Please strictly adhere to these conventions.

Allowed types:
- **build**: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
- **chore**: Tedious tasks like housekeeping etc.
- **ci**: Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs)
- **docs**: Documentation only changes
- **feat**: A new feature
- **fix**: A bug fix
- **perf**: A code change that improves performance
- **refactor**: A code change that neither fixes a bug nor adds a feature
- **release**: Release-specific code changes
- **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- **test**: Adding missing tests or correcting existing tests

_(based on [Angular contribution guidelines](https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md#type))_

#### Give context to your commits

To be able to identify the **WHY** behind a commit at a later point in time, we use the following template for our commit body:

```
<type>[optional scope]: <description> (#<issue number>)

because:
- [relevant context]
- [why you decided to change things]
- [reason you’re doing it now]

this commit:
- [does X]
- [does Y]
- [does Z]
```

— _[Source](https://twitter.com/r00k/status/1175100703829909505)_
