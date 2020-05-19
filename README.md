# Issue

- https://github.com/webpack-contrib/copy-webpack-plugin/issues/491
- https://github.com/webpack-contrib/copy-webpack-plugin/issues/492

## How Do We Reproduce?

1. npm install
2. npm start
3. the app is visible
4. make changes in the app
5. the app is not visible

## Dependencies

Check it out:

`npm list | grep copy-webpack-plugin`

```bash
λ npm list | grep copy-webpack-plugin
poc-flexible-web-application-architecture@1.0.0 C:\Users\user\Workspace\copy-webpack-plugin-v6
| +-- copy-webpack-plugin@6.0.1
npm ERR! peer dep missing: chromedriver@>=70, required by @leanup/cli@1.0.0-rc.228
npm ERR! peer dep missing: geckodriver@>=1, required by @leanup/cli@1.0.0-rc.228
npm ERR! peer dep missing: graphql@>=14, required by @leanup/cli@1.0.0-rc.228
npm ERR! peer dep missing: graphql@^0.9.0 || ^0.10.0 || ^0.11.0 || ^0.12.0 || ^0.13.0 || ^14.0.0, required by graphql-tag@2.10.3
npm ERR! peer dep missing: graphql@^0.12.0 || ^0.13.0 || ^14.0.0, required by eslint-plugin-graphql@3.1.1
npm ERR! peer dep missing: graphql@^0.11.0 || ^0.12.0 || ^0.13.0 || ^14.0.0, required by graphql-config@2.2.2
npm ERR! peer dep missing: graphql@^0.11.0 || ^0.12.0 || ^0.13.0 || ^14.0.0, required by graphql-import@0.7.1
```

`npm list | grep html-webpack-plugin`

```bash
λ npm list | grep html-webpack
| +-- html-webpack-plugin@4.3.0
npm ERR! peer dep missing: chromedriver@>=70, required by @leanup/cli@1.0.0-rc.228
npm ERR! peer dep missing: geckodriver@>=1, required by @leanup/cli@1.0.0-rc.228
npm ERR! peer dep missing: graphql@>=14, required by @leanup/cli@1.0.0-rc.228
npm ERR! peer dep missing: graphql@^0.9.0 || ^0.10.0 || ^0.11.0 || ^0.12.0 || ^0.13.0 || ^14.0.0, required by graphql-tag@2.10.3
npm ERR! peer dep missing: graphql@^0.12.0 || ^0.13.0 || ^14.0.0, required by eslint-plugin-graphql@3.1.1
npm ERR! peer dep missing: graphql@^0.11.0 || ^0.12.0 || ^0.13.0 || ^14.0.0, required by graphql-config@2.2.2
npm ERR! peer dep missing: graphql@^0.11.0 || ^0.12.0 || ^0.13.0 || ^14.0.0, required by graphql-import@0.7.1
```
