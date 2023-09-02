# Typescript-starter
This is a ESM package intended to be a boilerplate to work with ES6 modules and Typescript in Node.js, also to work with node workspaces as ESM. Please refer to [local-package](https://github.com/SalamandraDevs/local-package/tree/main) repository to clone it into `./package` directory if you want to have node submodules a.k.a worspaces.

# Quick start
1 - Clone this repo locally.

2 - Create a directory `packages` and cd into it.

3 - Clone into `packages` directory the [local-package](https://github.com/SalamandraDevs/local-package/tree/main) repository.

4 - Run `npm i` into `typescript-start` root directory.

5 - Run `npm run start:all`.

6 - Run `npm run` to see other scripts.


**NOTE:** You can work just with this package and not use workspaces, for do that, you need to delete the `workspaces` option in the `package.json` file, and run the program just with `npm run start`. 
