# nodets-canil

`npm init`
`tsc --init`
`npm install express mustache-express dotenv`
`npm install --save-dev @types/express @types/mustache-express @types/node`

### IN LINUX TO INSTALL PACKAGES GLOBALLY
`mkdir ~/.npm-global`
`npm config set prefix '~/.npm-global'`
`export PATH=~/.npm-global/bin:$PATH ### Add this to the end of the file ~/.profile`
`source ~/.profile`

### Global packages needed
`npm i -g nodemon typescript ts-node`

### Installing
`npm install`

### Run
`npm run start-dev`


### If it doesn't run in linux:
`npm cache clean --force`
`rm -rf node_modules`

### delete package-lock.json and run everything again
`npm install`
`npm run start-dev`