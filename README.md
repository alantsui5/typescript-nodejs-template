# TypeScript Node.js Template
This is a simple template to get you started on writing Node.js applications using TypeScript.

## Get started

```bash
# Clone the project
npx degit https://github.com/alantsui5/typescript-nodejs-template.git

# Development
npm run watch

# Production
npm run build
npm start

# Run Code Prettier 
npm run prettier-format

# Run ESLint Linter
npm run lint-and-fix
# or
npm run lint
```

## Why use Prettier
In team collaboration, code style consistency is important for people to communicate. <br />
What Prettier does is format the code to maintain consistent style while increase readability.
Prettier can be customized with `.prettierrc`. <br> The most common two are as follows.
```
{
  "semi": false,
  "singleQuote": true
}
```
`semi` is to choose whether `;` need to be at the back of each line. <br />
`singleQuote` is to use single quote for string, 
`false` value means use double quote for string.

## Why use ESLint
Debugs consumes time and effort, ESLint can help us to automate fixing and identifying of some syntax error and errors caused by dangerous operations. <br />
The modules used in this `.eslintrc` are about typescript, you can change the config so that it fits other projects.
