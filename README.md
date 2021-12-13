# typescript-node-setup
a base configuration to node typescript projcts

# setup guide
> setup guite created for document the process
1. `npm init -y`
2. `npm install -D typescript@latest`
3. `tsc --init` add tsconfig.json
4. start with eslint: 
    1. `npm install --save-dev eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin` 
    2. add .eslintrc and .eslintignore
    3. add lint script

# specifications
- using [asdf](https://github.com/asdf-vm/asdf) to manage node version
