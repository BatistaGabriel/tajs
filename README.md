# Método TAJS - Testes Automatizados com JavaScript

On this repo you are going to follow me along the automated tests with JS course by the most famous and loved Brazilian dev [Erick Wendel](https://br.linkedin.com/in/erickwendel).

Get yourself some tea, and me!

## Content

### Setting .nvmrc file content

In order to follow some best practices on node projects, we are going to use [NVM](https://github.com/nvm-sh/nvm). One of the required things in the project is to have on the root of your project folder a file called `.nvmrc` which should contain the node version that better suits the project. 
This will allow other dev that uses nvm to run your project in the correct version. We can set the content of this file by using the following command:

```bash
node -v > .nvmrc
```

### Setting project engines

Another best practice is to set the engines that your project require, like the .nvmrc file approach this one will indicate to node which engine your project uses and this will taken in consideration when installing libs to the project.
We can set that information after the project creation by running the following command:

```bash
npm pkg set type=module engines.node=$(node -v)
```

## Troubleshooting

## Links

- [Course landing page](https://cursos.erickwendel.com.br/metodo-tajs/matricula)