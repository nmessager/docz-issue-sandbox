# docz-issue-sandbox

### Active link in sidebar does not work

To reproduce the problem
```
cd ko-0.13.7-yarn
yarn install
npm start
```
The menu is broken.

To solve the problem you have to remove
```
"webpack": "^4.28.4",
"webpack-bundle-analyzer": "^3.0.3",
"webpack-cli": "^3.2.1",
"webpack-dev-server": "^3.1.14"
```
why ? I need webpack in my dependencies.
