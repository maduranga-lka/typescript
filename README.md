# typescript

## Install typescript
npm -g install typescript  

## Init work folder
Go inside the workfolder and execute npm init  

## Install lite server

"main": "app.js",
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
        "start": "lite-server"
    },  
    
Add start attribute in package.json file and execute npm install lite-server --save-dev  

# Setup ts compiler
tsc --init  
This makes tsconfig.json. by giving only tsc command in the work folder we can compile all the available ts files.


