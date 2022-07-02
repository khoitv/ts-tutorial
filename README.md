# ts-tutorial

# Lession 1:
    - Instal extensions: Bracket Pair Colorizer
        + Code Runner
        + JavaScript (ES6) code snippets
        + Prettier - Code formatter
        + Material Icon Theme

        + Jest
        + Jest Runner
        + Jest Snippet

    - Install TS
        + # Locally in your project.
            `npm install -D typescript`
            `npm install -D ts-node`
        + # Or globally with TypeScript.
            `npm install -g typescript`
            `npm install -g ts-node`
        + # Depending on configuration, you may also need these
            `npm install -D tslib @types/node`

    - Create first ts file:
        + Create file `index.ts` with content is `console.log('hello world')`
        + Compile and run ts file with command line:
            `tsc index.ts`: Compile only
            `ts-node index.ts`: Compile and run
    - Try with code runner
# Lession 2:
    - Init project: `npm --init`
    - Install Unit test
        `npm install --save-dev jest typescript ts-jest @types/jest`
        `npx ts-jest config:init`
    - Create function in ts file
    - Import function to test file
    - Write unit test
    - `Ctrl + Shift + P` ==> `Jest: Start All Runners`


