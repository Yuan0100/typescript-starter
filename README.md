# Typescript Project Starter

This is a starter template for a Typescript project that uses esbuild for bundling TypeScript to JavaScript.

(This setup refer to [Obsidian sample plugin](https://github.com/obsidianmd/obsidian-sample-plugin).)

## Getting Started

1. Clone this repository
2. Install dependencies with `npm install`
3. Start development server main.ts to main.js with `npm run dev`
4. Start the production server with `npm start`
5. Build the project with `npm run build`


## Available Scripts

In the project directory, you can run:

### `npm run dev`

Starts the development server with esbuild. This command will watch for changes to your .ts files and automatically compile them to .js.

### `npm start`

Starts the production server with nodemon. This command will start your server and automatically restart it when changes are made.

### `npm run build`
Bundles your .ts files to .js files in the dist directory.

### `npm run version`
Bumps the version number in the manifest.json and versions.json files. This command should be used when you are ready to release a new version of your application.

## License

This project is licensed under the MIT License.