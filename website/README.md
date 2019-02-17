This website was created with [Docusaurus](https://docusaurus.io/).

1. Clone the repo.

1. Make sure all the dependencies for the website are installed:

```sh
# Install dependencies
$ yarn
```
1. Run your dev server:

```sh
# Start the site
$ yarn start
```

1. Make your changes, commit them and push them up to the remote.

1. Publish the changes with this:

```
GIT_USER=<GIT_USER> \
  CURRENT_BRANCH=master \
  USE_SSH=true \
  yarn run publish-gh-pages # or `npm run publish-gh-pages`
```
