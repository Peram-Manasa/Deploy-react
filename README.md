create React application  in vs

do the npm start

 install   npm install gh-pages --save-dev
 
push the code into github repo

commands: git init, git add ., git status, gitcimmit, git remote, git push

then go to package.json  above add the json first "homepage":"https://<username>.github.io/<repo name>"

in package.json only write "scripts" add the this two 1. "predeploy":"npm run build", 2. "deploy":"gh-pages -d build"


then go to terminal reun the comad   npm run deploy

 go to repo setting click the pages and we go the link and copy see the output.
