# Web-Core-Test

# Getting Started

#### Step 1:

Fork the repository

#### Step 2:

If you haven't already, [configure npm for use with github packages ](https://docs.github.com/en/free-pro-team@latest/packages/using-github-packages-with-your-projects-ecosystem/configuring-npm-for-use-with-github-packages).

#### Step 3:

Edit the `package.json` file to download the web-core branch that you want to test like this:

**Note:** You must have created and pushed the changes you want to test to a new branch on the [Web-Core](https://github.com/farisaziz12/web-core) repository.

```
...
    "dependencies": {
    "web-core": "git@github.com:farisaziz12/web-core.git#branch-name"
  },
...

```

#### Step 4:

Run `npm install`

#### Step 5:

Test your changes to see if they work. I recommend using [Quokka.js](https://quokkajs.com) for quick Javscript testing or simply run index.js using node like this:

`node index.js`
