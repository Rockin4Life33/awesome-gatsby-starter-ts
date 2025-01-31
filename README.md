# @south-paw/awesome-gatsby-starter-ts

👌 A TypeScript starter for GatsbyJS with a preconfigured MDX, Storybook and ESLint environment

[![Netlify Status][netlify-master-status-img]][netlify-master-status]

> Prefer JavaScript? No worries, try [awesome-gatsby-starter](https://github.com/South-Paw/awesome-gatsby-starter)

## Features

- [Gatsby MDX](https://www.gatsbyjs.org/packages/gatsby-plugin-mdx/) for creation of pages with Markdown + JSX
- [Storybook](https://storybook.js.org/) with the Storybook Docs addon and support for components that use Gatsby components such as Link and StaticQuery
- [styled-components](https://www.styled-components.com/) for CSS-in-JS
- [ESLint](https://eslint.org/) with [Airbnb TypeScript](https://www.npmjs.com/package/eslint-config-airbnb-typescript)
- [Prettier](https://prettier.io/) integrated into ESLint
- A few example components and pages with stories and simple site structure

## Getting started

Install this starter (assuming you have [`gatsby-cli`](https://www.npmjs.com/package/gatsby-cli) installed) by running the following command:

```bash
gatsby new your-projects-name https://github.com/South-Paw/awesome-gastby-starter-ts
```

## Development

Install [`Node.js`](https://nodejs.org/) and [`Yarn`](https://yarnpkg.com).

Open the project directory in your CLI and run the `yarn` command to install dependencies.

After that you can run any of following commands

```bash
# local development (localhost:8000)
yarn start

# storybook development (localhost:9000)
yarn start:storybook

# run tsc and eslint on project
yarn lint

# build site for deployment (/public)
yarn build

# build storybook for deployment (/public/storybook)
yarn build:storybook

# local gatsby serve of /public
yarn serve

# clean build artifacts (/.cache and /public)
yarn clean
```

## Issues and Bugs

If you manage to find any, please report them [here](https://github.com/South-Paw/awesome-gatsby-starter-ts/issues) so they can be squashed.

## License

MIT, see the [LICENSE](https://github.com/South-Paw/awesome-gatsby-starter-ts/blob/master/LICENSE) file.

[netlify-master-status-img]: https://api.netlify.com/api/v1/badges/18f2589a-c443-4e19-b18a-8aa175175171/deploy-status
[netlify-master-status]: https://app.netlify.com/sites/awesome-gatsby-starter-ts/deploys
