# Snnipets - VSCode

São shortcuts de palavras que agilizam e facilitam no desenvolvimento. 

Entensions => snnipets + linguagem
Javascript (ES6) code snnipets
- **imp =>** para realizar importações
- **rqr =>** para utilizar require
- **met =>** para criar um método
- **sto =>** para criar um método setTimeout()
- **sti =>** para criar um método setInterval()
- **clg =>** para criar um console.log()

## Criar um snnipet personalizado
- ctrl + shift + p
- user snnipets + escolher linguagem

      "Nome do snnipet": {

          "prefix": "log", atalho

          "body": [ o que vai ser criado

              "console.log('$1');",

              "$2"

         ],

         "description": "Log output to console" descrição

     }




> ${1: texto} => insere o texto dentro do console com foco

> $2 => cria outro console.log()
