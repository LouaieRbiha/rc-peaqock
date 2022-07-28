1- Configure .vscode folder with recommanded settings.json & extensions.json
2- Install eslint with `npm install eslint --save-dev`
3- Start eslint configuration with `npx eslint --init`
4- Install prettier with `npm i prettier eslint-config-prettier eslint-plugin-prettier -D`
5- Create and add configuration for .prettierrc & .prettierignore files.
6- Check Problems section for more information & command to fix them.
7- Force engine version for node & npm with .npmrc file & configuration in package.json.
8- Install husky with `npm install husky lint-staged --save-dev`
9- Install tsc-files with `npm install tsc-files --save-dev` to check the types of staged files only.
10- Add lint-staged configuration file and customize your pipeline.
11- Force husky post installation & sort package.json file
12- Create your pre-commit hook with `npx husky add .husky/pre-commit "npm run lint-staged"`
13- Check .husky folder and pre-commit file configuration
