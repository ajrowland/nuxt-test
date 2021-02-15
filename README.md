# Nuxt test repo

## Purpose

Is there an issue with AsyncData when hitting a page directly via an extendedRoute in static mode?

The data seems to be undefined. It's okay if navigating to the page by a `<nuxt-link />`.

Only affects static generation.

This doesn't seem to be an issue for v2.14.7 or earlier.

## To test

```bash
# Install and run test solution
$ npm i
$ npm run generate
$ npm run start

# Visit http://localhost:3000 and follow links with developer tools console open.

# Downgrade Nuxt and try again
$ npm i nuxt@2.14.7
$ npm run generate
$ npm start

# No error in console.
```
