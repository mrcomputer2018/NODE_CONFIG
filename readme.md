# Configuracao do projeto node

- iniciar projeto
- instalar o typescript
- iniciar o typescript
- editar o tsconfig
- criar a pasta src e o arquivo server.ts
- instalar o express so para ver funcionando e sua tipagem
- instalar o ts-node-dev em desenvolvimento
- criar script DEV
- Alterar o tsconfig

    -"target": "es2017",
    -"lib": ["es6"],  /*Specify a set of bundled library declaration files that describe the target runtime environment.*/
    -"experimentalDecorators": true, /*Enable experimental support for legacy experimental decorators.*/
    -"emitDecoratorMetadata": true,  /*Emit design-type metadata for decorated declarations in source files.*/
    -"outDir": "./dist", /*Specify an output folder for all emitted files.*/
    -"rootDir": "./src", /*Specify the root folder within your source files.*/
    -"allowJs": true, /*Allow JavaScript files to be a part of your program. Use the 'checkJS' option to get errors from these files.*/
    -"removeComments": true, /*Disable emitting comments.*/
    -"typeRoots": [
      "./node_modules/@types/",
      "./src/@types"
    ],   /*Specify multiple folders that act like './node_modules/@types'.*/
    -"resolveJsonModule": true, /*Enable importing .json files.*/

- Adicionar dist para o gitignore
