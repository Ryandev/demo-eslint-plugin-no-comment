# Example eslint-plugin-no-comment
Demo usage of eslint rule no-comment showing installation & usage
See plugin for more info [eslint-no-comment](https://github.com/Ryandev/eslint-plugin-no-comment)


### Usage
`yarn install && yarn lint`
After which you will see:
```
ryan@macbook % yarn lint                      
yarn run v1.22.19
$ eslint .

demo-eslint-plugin-no-comment/index.js
  6:1  error  Invalid comment type. Remove, or replace '//' with '/*'  no-comment/no-comment-line

✖ 1 problem (1 error, 0 warnings)

error Command failed with exit code 1.
```

