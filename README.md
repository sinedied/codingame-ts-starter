# :muscle: codingame-ts-starter

> Typescript starter template for CodinGame challenges

**Features**
- [TypeScript](https://www.typescriptlang.org)
- Module bundling and minification with [Parcel](https://parceljs.org)
- Testing with [Jest](https://jestjs.io)
- Code formatting with [Prettier](https://prettier.io)
- [VSCode](https://code.visualstudio.com) integrations

## Installation

1. `git clone` this repo
2. Run `npm install` in the project folder

You also need [CodinGame Sync](https://www.codingame.com/blog/new-feature-codingame-sync-use-your-own-code-editor-on-codingame/) to synchronize your local code with the CodinGame editor.

## Usage

Run either `npm start` or `npm run build` to generate the output file, then start the CodinGame Sync tool and choose to sync the `dist/index.js` file.

### Commands

- `npm start`: build your code in watch mode (it will automatically recompile on change).
  Note that in this mode code size optimizations are NOT performed, use `npm run build` for that.
- `npm run build`: build your code once, with tree-shaking and minification
- `npm run test`: run unit tests once
- `npm run test:watch`: run unit tests in watch mode
- `npm run prettify`: reformat all your code automatically

### VSCode integrations

All NPM scripts are mapped to VSCode tasks, and the build shortcut is mapped to the `npm run build` command.

A launch configuration is also ready-to-use to debug your tests with breakpoints support within VSCode.
