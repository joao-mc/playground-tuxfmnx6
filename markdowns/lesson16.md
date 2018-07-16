
---
### Processamento com Sinalizador de Parada.
---
+ Esse tipo de processamento é representado pela estrutura ```While```
+ Sinalizador de parada é um valor, em geral externo ao programa, que faz com que a condição da estrutura seja Falsa. 
+ É necessário definir uma variável sinalizador, para ser usada no comando de leitura dos dados (***scanf***).
+ O comando de leitura deve ser colocado antes da estrutura ```While``` e repeti-lo antes do final da estrutura.
![while](/markdowns/while2.png)

+ O exemplo a seguir lê uma sequência de números inteiros positivos. O programa termina quando for lido um valor negativo.

@[IDE]({"stubs": ["./www/ExemploEntrada"],"command": "sh /project/target/www/Sinal.sh"
})

