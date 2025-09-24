# Project Overview

Welcome to this repository! This is repository stores the source code for the web application "Telepathy".

## Install Dependencies for Development

### Client
- Install dependencies within `package.json`: 
``` bash
cd client
npm install
```
- Run client server: 
``` bash
npm run dev
```

### Server:
- Install <a href="https://github.com/air-verse/air">Air - Live reload for Go apps</a>
- Install dependecies within `go.mod`:
``` bash
cd server
go mod download
```

- Run backend server: 
``` bash
air
```
