# MultiCode Builder

A small starter version of a multi-language programming builder.

## What it does

- Build a program using simple blocks.
- Store the program as a language-independent list of steps.
- Generate equivalent code for Python, JavaScript, or Java.
- Edit variables, output, conditions, and math blocks.
- Load example programs.
- Copy generated code.
- Run completely locally with Vite.

## Run in Visual Studio Code

1. Install Node.js (18+ recommended).
2. Open this folder in Visual Studio Code.
3. Open the integrated terminal.
4. Run:

   npm install

5. Start the development server:

   npm run dev

6. Open the local URL shown by Vite.

## Project structure

- `src/main.jsx` - application logic, program model, and language generators.
- `src/styles.css` - user interface styling.
- `index.html` - HTML entry point.
- `vite.config.js` - Vite configuration.

## Next improvements

1. Replace the simple step list with a real AST.
2. Add a parser so users can paste code into the app.
3. Add code execution in a sandbox.
4. Add TypeScript, C#, C++, and Go.
5. Add save/load project files.
6. Add tests that verify each language produces the same result.
