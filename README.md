# cypress-workshop-basics-from-scratch

This is a partial copy of https://github.com/bahmutov/cypress-workshop-basics, but initially with all the Cypress code stripped out so it could be a blank slate for test development learning


## Requirements

- Any computer: Mac, Windows, Linux
- [Node 16+ (LTS)](https://nodejs.org/), see my [Node install video](https://youtu.be/09KbTRLrgWA), and my [Node versions using NVM video](https://youtu.be/CNnCz6StbbY)
- [git](https://git-scm.com)

Check the Node version

```
$ node -v
# for example v18.13.0
$ npm -v
# for example 8.19.3
```

### Clone the repo

In order to get the code and install NPM dependencies, first clone my repo to your local machine.

```bash
git clone git@github.com:Automation-Collaboration/cypress-workshop-basics-from-scratch.git

Cloning into ...
```

### Install NPM dependencies

Change the working folder to the cloned repository folder

```bash
cd cypress-workshop-basics
```

If necessary, install dependencies inside TodoMVC folder.

```bash
cd todomvc
npm install
```

### Quick check ✅

You can test the installation by starting TodoMVC in the first terminal window

```shell
npm start
```

and you should see in the terminal

```text
> json-server --static . data.json --middlewares ./node_modules/json-server-reset


  \{^_^}/ hi!

  Loading data.json
  Loading ./node_modules/json-server-reset
  Done

  Resources
  http://localhost:3000/todos

  Home
  http://localhost:3000
```

If you open your browser and type "localhost:3000" you should see the web application running:

