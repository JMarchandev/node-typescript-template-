# TypeScript Node Template

Just a simple template of an empty Node.js project with TypeScript preconfigured.

## Description

This project serves as a starting point for building Node.js applications using TypeScript. It provides a basic structure and preconfigured scripts to help you get started quickly.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/JMarchandev/node-typescript-template
   ```

2. Navigate to the project directory:

   ```shell
   cd typescript-node-template
   ```

3. Install the dependencies:

   ```shell
   npm install
   ```

## Usage

The project includes several predefined scripts that you can use:

- `start`: Builds the project and starts the application.
- `dev`: Starts the application in development mode using [nodemon](https://nodemon.io/) for automatic restarts on file changes.
- `build`: Transpiles the TypeScript code to JavaScript and outputs the compiled files in the `build` directory.
- `test`: Executes the tests (placeholder script).

To run a script, use the following command:

```shell
npm run <script-name>
```

## Project Structure

The main files and directories in this template are:

- `src`: Contains the source code files.
- `build`: Contains the compiled JavaScript files (generated after running the `build` script).
- `test`: Directory for placing tests.

## Dependencies

The project utilizes the following devDependencies:

- `@types/node`: TypeScript type definitions for Node.js.
- `nodemon`: Utility that automatically restarts the application on file changes during development.
- `rimraf`: Cross-platform tool for removing directories.
- `ts-node`: TypeScript execution and REPL for Node.js.
- `typescript`: TypeScript compiler.

## License

This project is licensed under the ISC License. For more information, see the [LICENSE](LICENSE) file.

## Author

This project was created by JMarchandev. Feel free to reach out to me if you have any questions or suggestions.
