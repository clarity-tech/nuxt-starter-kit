# Nuxt 3 Minimal Typescript and Tailwind Starter Kit

We recommend to look at the [documentation](https://v3.nuxtjs.org).

<div align="center">
<img src="https://www.claritytech.io/logo.png" height="80px" title="Nuxt Starter Kit Broilerplate template" />
</div>
<br />

<div align="center"><strong>Nuxt.js 3 + Tailwind starter for Typescript lovers</strong></div>

_Nuxt Starter Kit_ is an opinionated boilerplate based off of [Nuxt3](https://v3.nuxtjs.org/)(beta), with all the essentials you would want ready, up and running when starting a Nuxt project to play and experiment with.
<br/>

<div align="center">
  <img src="https://img.shields.io/static/v1?label=PRs&message=welcome&style=flat-square&color=navy&labelColor=1c64f2" alt="PRs welcome!" />

  <img alt="License" src="https://img.shields.io/github/license/clarity-tech/nuxt-starter-kit?style=flat-square&color=navy&labelColor=1c64f2">

  <a href="https://twitter.com/intent/follow?screen_name=msonowal">
    <img src="https://img.shields.io/twitter/follow/msonowal?style=flat-square&color=navy&labelColor=1c64f2" alt="Follow @msonowal" />
  </a>
</div>
<br/>

Out of the box you get all the `essentials`

- **Typescript** as the Nuxt Module setup
- **Tailwind Module** via Nuxt Tailwind Module for zero configuration start and view config via `http://localhost:3000/_tailwind/`
- **editorconfig** for Consistent styling
- **ESLint** for static code analysis (added but it's currently failing due to [#171](https://github.com/nuxt/eslint-config/issues/171)) and
- **Prettier** for code formatting

and more...

**Note**:

🚧 Nuxt 3 is currently in beta and is not yet production ready.

But we will make sure the broilerplate updated with latest updates and conventions when required

## Quick Start

The best way to start with this template is to click "__Use this template__" above, create your own copy and work with it
or clone directly to your machine
```bash
git clone git@github.com:clarity-tech/nuxt-starter-kit.git
```

## Setup

Make sure to install the dependencies

```bash
yarn install
```

### Development

To start the project locally, run:

```bash
yarn dev
```

which kickstarts the nuxt3 development and build server `nuxi`. Open `http://localhost:3000` with your browser to see the result.

## Production

Build the application for production:

```bash
yarn build
```

Checkout the [deployment documentation](https://v3.nuxtjs.org/docs/deployment).

Check `package.json` for the full list of commands available at your disposal.

````

## Known Issues just for code linting in development

- [ESLint](https://github.com/nuxt/eslint-config/issues/171) - Once the issue is resolved you can add
```json
        "*.+(js|ts|vue)": [
            "yarn run lint"
        ],
````

in `package.json` under the `lint-staged` section for linting on commits

## License

MIT
