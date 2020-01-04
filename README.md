## Eslint 
```json
{
  "parserOptions": {
    "ecmaVersion": 2019,
    "sourceType": "module",
    "ecmaFeatures": {
      "jsx": true
    }
  },
  "extends": ["eslint:recommended"],
  "rules": {
    "strict": ["error", "never"]
  },
  "env": {
    "browser": true
  }
}
```

`parserOptions`: we override this option to supporting linting
for ES6. 


## Prettier

`eslint-config-prettier` Turns off all rules that are unnecessary or might conflict with Prettier

## TypeScript
eslint is not the tool for type checking and tsc is used to do the type checking and
use babel to transform typescript. There are couple packages for that
```
@typescript-eslint/eslint-plugin 
@typescript-eslint/parser
```

`plugin:@typescript-eslint/eslint-recommended`: remove unnecessary lint rule for TypeScript
`eslint-config-prettier/@typescript-eslint`: remove unnecessary lint rule for TypeScript
`plugin:@typescript-eslint/recommended`: remove unnecessary lint rule for TypeScript




