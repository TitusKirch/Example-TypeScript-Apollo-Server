# Example TypeScript Apollo Server

[![GitHub](https://img.shields.io/github/license/TitusKirch/Example-TypeScript-Apollo-Server)](https://github.com/TitusKirch/Example-TypeScript-Apollo-Server/LICENSE)
[![CI](https://github.com/TitusKirch/Example-TypeScript-Apollo-Server/actions/workflows/ci.yml/badge.svg)](https://github.com/TitusKirch/Example-TypeScript-Apollo-Server/actions/workflows/ci.yml)

A simple example project for Apollo Server in Typescript including ESlinkt and VSC-Config.

The following tutorials helped with the creation:
- [How to build an Apollo GraphQL server with TypeScript and Webpack Hot Module Replacement](https://medium.com/free-code-camp/build-an-apollo-graphql-server-with-typescript-and-webpack-hot-module-replacement-hmr-3c339d05184f)
- [How to set up Eslint with Typescript in VS Code](https://thesoreon.com/blog/how-to-set-up-eslint-with-typescript-in-vs-code)

## Setup
After downloading the project run `cp .env.example .ev` and configure the `.env` file. Then run `npm install` and the project is ready to use.

## Commands
|Command|Aliases|Description|
|---|---|---|
|`npm run build:production`|`npm run build`| Builds the app with the production settings. |
|`npm run build:dev`|`npm run build:development`| Builds the app with the development settings. |
|`npm run start`| - | Starts the app with the `.env` file. |
|`npm run eslint`| - | Run ESLint to check the code style. |