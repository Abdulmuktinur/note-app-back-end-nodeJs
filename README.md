# Practice Project Dicoding Build Web service using Node.Js
# Note App Back-end

Build RESTful API for Note Apps Back-end using NodeJs.
  - Save Notes (Create)
  - View Notes (Read)
  - Edit Notes (Update)
  - Delete Notes (Delete)

Front-end cek in link : http://notesapp-v1.dicodingacademy.com/.

### Structure Project

notes-app-back-end
├── node_modules
├── src
│ ├── handler.js
│ ├── notes.js
│ ├── routes.js
│ └── server.js
├── .eslintrc.json
├── package-lock.json
└── package.json

### Details

- server.js : load code for create, config, and run server HTTP using Hapi.
- routes.js : load code config routing sercer like determine path, method, and handler used.
- handler.js : load all functin handler used in file routes.
- notes.js : load data notes saved in object array form.

All file javaScript which we create will save in folder src. this matter intends to separate from file configuration project such as .eslintrc.json, package.json, package-lock.json, and node_modules.
