# Web-Core-Test

# Getting Started

#### Step 1:

Fork the repository

#### Step 2:

Edit the `package.json` file to download the web-core branch that you want to test like this:

**Note:** You must have created and pushed the changes you want to test to a new branch on the [Web-Core](https://github.com/farisaziz12/web-core) repository.

```
...
    "dependencies": {
    "web-core": "git@github.com:farisaziz12/web-core.git#branch-name"
  },
...

```

#### Step 3:

Run `npm install`

#### Step 4:

Test your changes to see if they work. I recommend using [Quokka.js](https://quokkajs.com) for quick Javscript testing or simply run index.js using node like this:

`node index.js`
