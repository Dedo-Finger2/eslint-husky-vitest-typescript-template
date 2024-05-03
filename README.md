# ESLint, Husky, Vitest, Prettier, Typescript project template
> Uma maneira rápida de começar um projeto typescript usando boas práticas de programação.

![](https://img.shields.io/badge/eslint-3A33D1?style=for-the-badge&logo=eslint&logoColor=white)
![](https://img.shields.io/badge/prettier-1A2C34?style=for-the-badge&logo=prettier&logoColor=F7BA3E)
![](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![](https://img.shields.io/badge/vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)

![Logo](https://i.imgur.com/fuc7vSu.png)

Este repositório é um template que pode ser usado para obter uma rápida estrutura de pastas para seus projetos Typescript, possuindo já de cara:
- **ESLint** configurado para concertar problemas de linting. 
- **Husky** com o hook dde pre-commit para garantir que as regras do ESLint sejam aplicadas, garantindo assim um padrão no seu código.
- **Vitest** para execução de testes criados no projeto, parando o commit caso os testes falhem.
- **Prettier** organizando e formatando seu código mesmo sem usar a extensão no seu editor de código.

## Instalação

```sh
npm install 
```

## Configuração

Os arquivos: `.lintstagedrc.json`, `.prettierrc.json` e `.eslintrc.json` podem ser configurados a vontade para fazer com que sigam as prátias comuns do seu time / empresa.

- .lintstagedrc.json > Configuração dos comandos que serão executados assim que um commmit for feito.
- .prettierrc.json > Regras do prettier que vão formatar seu código.
- .eslintrc.json > Regras do eslint que vão ditar quais regras de linting seu código vai seguir.

## Histórico de lançamento

* V0.1
    * Configuração inicial;
    * pre-commit hook;
    * npm update depois de um npm install;
    * README.Me.
