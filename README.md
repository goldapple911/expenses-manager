<h1>EXPENSE MANAGER</h1>

# How To Run the Project

## There are two ways to install the project:

### 1. Conventional Way

**_1._** Open Project Folder</br>

**_2._** To install all dependencies open Command Prompt and run

```
npm i
```

**_3._** To install all client dependencies open client folder and again run

```
npm i
```

**_4._** To run the server-

```
npm run server
```

**_5._** To run the client-

```
npm run client
```

**_6._** To run both server and client- Recommended

```
npm run dev
```

### 2. Using Docker

- Install [Docker](https://docs.docker.com/engine/install/), from the given link.

- Once Docker is installed, use the following two commands to run the app in the root dicrectory:
  - `docker-compose build` , This command will build the project
  - `COMPOSE_HTTP_TIMEOUT=200 docker-compose up`, This command will run the container.
- You can open the project on `localhost:3000` on the machine.

Note: If you are using docker-desktop on Windows Or WSL2 i.e Windows Subsystem For Linux, you can use the GUI Options to run the containers
