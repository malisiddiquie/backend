# backend project.
# npm init : create the package.json file.
# git init : initialize the local repository with git.
# .gitkeep created for empty folder.
# .gitignore createed, the mentioned files in .gitignore will not be pushed. 
# .gitignore generator: https://mrkandreev.name/snippets/gitignore-generator/
# .env file: envoirnment variable are taken from system not from files because it to be secured.
# src folder created for keeping files such as Index.js, app.js, constant.js
# CommonJS (CJS) & ES Modules (ESM)

# CommonJS is the module system used by Node.js and was the standard for JavaScript modules before ES Modules were introduced. In CommonJS, modules are loaded synchronously, which is suitable for server-side applications. 
# CommonJS syntax 'require()/module.exports'

# We use ES Modules (ESM): ES Modules are the official standard for JavaScript modules, introduced in ECMAScript 2015 (ES6). They are now widely supported in both browsers and Node.js. ES Modules are designed to be more versatile and efficient than CommonJS.
# ES Modules (ESM) Syntax: 'import' / 'export'

# now set the ES Modules (ESM) in package.json so, type: "module"

# Nodemon utility: To restart server automatically (once the file save, the server get restart.)
# Nodemon Installation as Dev Dedpendency so, npm i -D nodemon OR npm install --save-dev nodemon (node_modules created)
# Script: set the command in package.json to run server. ("dev": "nodemon src/index.js") 
# create some folders inside the src folder such as controllers db middlewares models utils
# Prettier :  Prettier is a popular code formatter that helps maintain consistent code style across a project.
# Prettier Installation as Dev Dedpendency so, npm i -D prettier 
# Prettier Configuration: create a file called .prettierrc at root level. (note: at the end rc to be added in file name).
# PrettierignoreL create a file called .prettierignore at root level. (mention files on which pritter not applicable).