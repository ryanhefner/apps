# Page location example
This example shows how an app with a page location can be built. It creates a simple dashboard with information about your content and implements routing with `react-router-dom`.

## How to use

Execute create-contentful-app with npm, npx or yarn to bootstrap the example:

```bash
# npx
npx create-contentful-app --example page-location

# npm
npm init contentful-app -- --example page-location

# Yarn
yarn create contentful-app --example page-location
```

## How to use

Install it and run:

```bash
npm install
npm start
# or
yarn
yarn start
```

To test, you can create an app definition in your Contentful organization settings pointing to `http://localhost:1234` and registering both the `app-config` and `page` locations.

[Read the docs](https://www.contentful.com/developers/docs/extensibility/app-framework/) for more information.
