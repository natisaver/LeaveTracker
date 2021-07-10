# LeaveTracker
Leave Tracking App for Success
REACT FRONTEND
 ```bash
 npm i react-bootstrap //download the min.css frm bootswatch
 npm i react-router-dom react-router-bootstrap
 npm i axios
 ```
 
 ```bash
 since frontend localhost:3000 & backend on 5000, need proxy in package.json frontend
 "proxy": "http://127.0.0.1:5000",
 ```
 
 to index.html:
 https://cdnjs.com/libraries/font-awesome


Git 
 ```bash
 //1. move .gitignore out of frontend folder
 //2. in frontend folder: rm -rf .git/
 //3. in folder outside frontend, git init
 
 git add .
 git status
 git commit -m "Name of this stage"
 ```

BACKEND (root folder, not /backend)
 ```bash
 //for the entry point put to server.js instead of index.js
 npm init
 npm i express mongoose 
 npm i -D nodemon concurrently
 ```
 
package.json "scripts"
```bash
    "start": "node backend/server",
    "server": "nodemon backend/server",
    "client": "npm start --prefix frontend",
    "dev": "concurrently \"npm run server\" \"npm run client\""
```
