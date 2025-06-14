### VS code Setting
```
Format On Save - on
Default Formatter - Prettier - Code formatter

.prettierrc.json
{
  "semi": false,
  "singleQuote": true,
  "printWidth": 100,
  "tabWidth": 2,
  "trailingComma": "es5",
  "arrowParens": "avoid"
}

# npm 7+, ` extra double-dash is needed:
npm create vite@project_name -- --template react-ts

√ What do you want to lint? · javascript, json, md, css
√ How would you like to use ESLint? · problems
√ What type of modules does your project use? · esm
√ Which framework does your project use? · react
√ Does your project use TypeScript? ·  yes
√ Where does your code run? · browser
√ What flavor of Markdown do you want to lint? · gfm
√ Would you like to install them now? · Yes
√ Which package manager do you want to use? · npm

