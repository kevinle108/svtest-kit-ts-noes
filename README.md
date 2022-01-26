Test Runner: Vitest
SvelteKit - Typescript - No ES Linting

Text below was taken from: 
https://github.com/nickbreaton/vitest-svelte-kit/tree/a2e7638003afe56322b149323dd96bf783445f08/examples/svelte-kit-demo-app,
https://jsrepos.com/lib/nickbreaton-vitest-svelte-kit

# SvelteKit Demo App with Vitest

## Additional Dependencies

After this project was created with `npm create svelte@next svelte-kit-demo-app`, the following dependecies were installed:

-   `@testing-library/svelte`
-   `jsdom`
-   `vitest`
-   `vitest-svelte-kit`

## Configuration

1. The file `vitest.config.js` was created to set up Vitest with SvelteKit.
2. The existing `svelte.config.js` was modified to set up Vitest with jsdom.

## Test Files

An example test file was added at `src/routes/about.test.ts`.

## Running

### Vitest

```sh
npm test
```

### SvelteKit

```sh
npm run dev
```