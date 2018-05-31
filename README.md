# monorepo-template
[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lernajs.io/)

A simple monorepo template.

## About
- npm client is [Yarn](https://github.com/yarnpkg/yarn)
- multiple packages tool is [lerna](https://github.com/lerna/lerna)

## Getting Started

### Prerequisites
1. Install Yarn
    Read the [Installation Guide](https://yarnpkg.com/en/docs/install).
1. global install lerna
    lerna can will link dependencies in the repo together
    ```.sh
    yarn global add lerna
    ```
    or
    ```.sh
    npm install -g lerna 
    ```

### Installing
```
git clone https://github.com/nitaking/monorepo-template.git
cd monorepo-template
yarn
```

## To make from scratch
[prerequisites](https://github.com/nitaking/monorepo-template#prerequisites) executed.

```
yarn init
lerna init
```
