# ESLint issue with extends

[![Greenkeeper badge](https://badges.greenkeeper.io/SimenB/eslint-extends-issue.svg)](https://greenkeeper.io/)

Run `npm run print-config` to print the resolved config. If you have `jq` installed, you can run `npm run print-config-jq` to get it pretty printed.

The issue is that the `extends` array only has 7 entries, while there should be many more there.

If you remove an entry in the `.eslintrc` and check the config again, you can see it's still 7 entries, as an earlier missing one was added

