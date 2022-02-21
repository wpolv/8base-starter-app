I completed the quick start, excluding the fifth point (challenge). Along the way, I encountered some bugs and also found some things that could be improved.

Bug 1. Picture in 2.1 quick start paragraph (building a data model) contains an error. Instead “Allow multiple Users per Note” necessary to use “Allow multiple Notes per Users” relationships. 
Bug 2. Command “8base init . --functions=resolver:myCustomResolver” don't work (i use windows 10). If you try to use this command you get  “Invalid project name: name cannot start with a period” error. 
You need to add a folder name like “8base init folderName --functions=resolver:myCustomResolver”. But if you do so, you need to use “cd folderName” before using the “npm install” command. 
Bug 3.Many  “Delete 'cr' [prettier/prettier]” errors when I start the react frontend via “npm run start” command. If I add the string “"prettier/prettier": [ "error", { "endOfLine": "auto" }, ],” in the .eslintrc.json file, these errors disappear. 

Feature-request 1. Some console commands from quick start guide only work in unix and unix-like os. For example “touch readme.md", or “mkdir 8base-starter-app/client” (in Windows you need to use “mkdir 8base-starter-app\client”). Maybe necessary to add Windows cmd commands in the quick start guide. 
Feature-request 2. CI/CD paragraph contain a guide “how to create and use environments” only. Maybe it would be more logical to rename this to “Environments”. 
