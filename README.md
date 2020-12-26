# notes-app
This is a note taking app that can add, remove, list all the notes.
The commands are given in the terminal using yargs module.
The notes are saved as JSON objects.

The commands that are used from the terminal are as follows:

node app.js add --title = " Note title " --body = " Note body "
node app.js remove --title = " Note title "
node app.js list
node app.js  read  --title="title of the note that we want to fetch"