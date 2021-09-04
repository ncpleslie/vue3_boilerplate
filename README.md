# Vue 3 + Typescript + Vite + Automated testing

This template should help get you started developing with Vue 3 and Typescript in Vite.

This boilerplate focuses on automating a11y tests, Chrome's lighthouse, and linting.

## Github Actions

- [a11y](./.github/workflows/a11y.yml) to automate accessibility testing.
    - [Axe by Deque](https://github.com/dequelabs/axe-core-npm)


- [lighthouse](./.github/workflows/lighthouse.yml) to automate SEO, best practices, and accessibility. 
    - [Lighthouse by Google Chrome](https://github.com/GoogleChrome/lighthouse-ci)


- [lint](./.github/workflows/lint.yml) checking. Pretty standard. It's just eslint.
    - [eslint](https://github.com/eslint/eslint)


### License

MIT