# Notes Node App
This application runs on node version 8 and up. This app uses the File System module to write data.

All notes are saved to a notes-data.json file.

## How to use
- Run `npm install` to install all dependencies
- Run `node app.js --help` to list all commands

### Commands
1. add - adds a note
    - example: `node app.js add --t="Note title" --b="Note body"`
2. read - lists a note
    - example: `node app.js read --t="Note title"`
3. remove - removes a note
    - example: `node app.js remove --t="Note title"`
4. list - lists all notes
    - example: `node app.js list`