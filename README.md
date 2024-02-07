# express-remix

![GitHub](https://img.shields.io/github/license/pascalallen/express-remix)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/pascalallen/express-remix)

express-remix is a containerized SDK offering a Node.js and Express server, and a React and React Remix client. This project is by-design minimal for rapid development.

## Prerequisites

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## Development Environment Setup

### Clone Repository

```bash
cd <projects-parent-directory> && git clone https://github.com/pascalallen/express-remix.git
```

### Install JavaScript Dependencies

```bash
bin/yarn ci
```

## Build app with React Remix

```bash
bin/node npx remix build
```

## Bring up Express server

```bash
bin/up
```

## Watch for React changes

```bash
bin/yarn serve
```

You will find the site running at [http://localhost:8080/](http://localhost:8080/)

### Take Down Environment

```bash
bin/down
```
