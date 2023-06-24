# Typescript repository template

Repository template for Typescript with configs and tools I like:

- [eslint](https://eslint.org/) + [prettier](https://prettier.io/) with default settings running on pre-commit (thanks to [lint-staged](https://github.com/okonet/lint-staged) and [husky](https://typicode.github.io/husky/)).
- Continuous integration using [Github Actions](https://github.com/features/actions)
- Minimal support for old versions. The assumption is something like [swc](https://swc.rs/) or [vite](https://vitejs.dev/) will handle that if needed.

The `main` branch of this repo is pretty minimal and doesn't try to be opinionated towards frontend or backend projects. Some day there might be something more specific in a branch :)
