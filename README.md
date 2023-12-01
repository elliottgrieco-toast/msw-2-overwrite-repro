# Reproduction

To reproduce: Simply `yarn install` (reproduced with `yarn 1.x`) and notice that the `postinstall` script overwrites the existing `public/mockServiceWorker.js` file.

See issue: https://github.com/mswjs/msw/issues/1904
