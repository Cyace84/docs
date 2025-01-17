# Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Installation

```shell
$ yarn
```

### Local Development

```shell
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```shell
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

For emulate prod build:
```shell
$ yarn emul
```

### Deployment `gh-pages`

```shell
$ export SITE_URL=https://%USER%.github.io
$ export SITE_BASE_URL=/docs/
$ git remote add gh-pages git@github.com:%USER%/docs.git
$ yarn deploy-gh-pages
```
