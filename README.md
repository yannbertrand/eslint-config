Not ready to be used as an npm package yet, will make it possible in the future.

# How to use globally

1. Create an `.eslintrc` file in your home directory
2. Insert this configuration inside of it:
```json
{
  "extends": ["@yannbertrand/eslint-config"]
}
```
3. Run `npm install -g eslint babel-eslint https://github.com/yannbertrand/eslint-config.git`
4. Use `eslint` CLI wherever you need

## How to configure VSCode to autofix on save

1. Install the [eslint extension](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
2. Add this config in your settings.json file:
```json
  "eslint.autoFixOnSave": true,
  "eslint.options": {
    "configFile": "/Users/username/.eslintrc"
  }
```
3. Enjoy
