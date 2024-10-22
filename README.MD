# Wookie Movies

This repository contains 2 folders:

- `build-no-bug`: The application working correctly.
- `build-with-bug`: The application with a bug.

## How to run

To run the application, you need to serve the content of `build-*` as a static site.

You can achieve this using the [`serve`](https://www.npmjs.com/package/serve) npm package:

### Install the package

```
npm install -g serve
```

### Serve the build as a static site

```
serve build-no-bug
```

or

```
serve build-with-bug
```

You can then access the site at http://localhost:3000/.
