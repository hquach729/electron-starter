> - Setup

```
mkdir my-electron-app && cd my-electron-app
yarn init

entry point should be main.js.
author and description can be any value, but are necessary for app packaging.

{
  "name": "my-electron-app",
  "version": "1.0.0",
  "description": "Hello World!",
  "main": "main.js",
  "author": "Jane Doe",
  "license": "MIT"
}

Change the stupid main branch to master
hint:   git config --global init.defaultBranch <name>

echo "# electron-starter" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/hquach729/electron-starter.git
git push -u origin master

yarn add --dev electron

```
