# Frontend starter styles

> The building blocks of CSS at Springload

## Installation

> Clone the project on your computer, install [Node](https://nodejs.org) and [Yarn](https://yarnpkg.com/lang/en/docs/install/). This project also uses [nvm](https://github.com/creationix/nvm).

From the command-line:

```sh
cd ~/Development/sites/
git clone git@github.com:springload/frontend-starter-styles.git
cd frontend-starter-styles
```

To install our dependencies:

```sh
nvm install
# Then, install all project dependencies.
yarn install
```

## Working on the project

> Everything mentioned in the installation process should already be done.

This is the architectural base for css that we work with at Springload. Build on top of this as you wish, but here are the [css guidlines we follow](https://github.com/springload/frontend-starter-kit/blob/master/docs/css.md).

Should you choose to run any of this project's build tasks, it uses [node-sass](https://github.com/sass/node-sass) by way of [node-sass-chokidar](https://github.com/michaelwayman/node-sass-chokidar), and [PostCSS](https://github.com/postcss/postcss).

```sh
# Make sure you use the right node version.
nvm use
# Start the server and the development tools.
yarn start
# Builds stylesheet for development
yarn build
# Builds stylesheet for production
yarn dist
# Runs linting.
yarn lint
```

## Code linting

The project's code is linted with [Stylelint](https://github.com/stylelint/stylelint).
