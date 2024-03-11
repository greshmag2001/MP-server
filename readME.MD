
            JSON - deployable JSON file using node js
            ----------------------------------

        1. create a folder for json
        2.using command : npm init -y to create package.json file
        3.add the start command as 'node index.js' in script of package.json file
        4.create .gitignore file, add node_modules inside that file
        5.install json-server to run json file: npm i json-server / npm i json-server@0.17.4
        6.create db.json file
        7.add resources in db.json file to store data
        8.create index.js file
            -import json-server
            -create server using json-server
            -create a middleware
            -create a path for db.json
            -define PORT
            -listen server in the given port
        9.to run json file using json-server: using command 'npx json-server db.json' / node index.js
        

