# Style guide for JavaScript using Eslint + Prettier + Airbnb style

## Install Eslint and Prettier plugins on VSCode

## Add plugins configuration to settings.json

`{ "eslint.autoFixOnSave": true, "editor.formatOnSave": true, "[javascript]": { "editor.formatOnSave": false } }`

## Init project

`npm init`

## Install dependencies as dev dependencies

`npm install -D prettier`

`npx install-peerdeps --dev eslint-config-airbnb`

## Create .eslintrc and copy this code to the file

`{ "extends": "airbnb" }`
