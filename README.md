# typescript-node-setup
a base configuration to node typescript projcts,

## setup guide
> setup guite created for document the process
1. `npm init -y`
2. `npm install -D typescript@latest`
3. `tsc --init` add tsconfig.json
4. start with eslint: 
    > you can use `eslint --init` to.
    1. `npm install --save-dev eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin` 
    2. add .eslintrc and .eslintignore
    3. add lint script
    4. npm i -D prettier eslint-config-prettier eslint-plugin-prettier 
    5. add eslint configurations and plugins
5. add ts-node-dev and tsconfig-paths
6. add jest:
    1. `npm i jest -D`
    2. `npx jest --init`
    3. `npm i ts-jest -D`
    4. `npm i @types/jest -D`
    5. add jest.config.js

## specifications
- using [asdf](https://github.com/asdf-vm/asdf) to manage node version
