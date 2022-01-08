# Variáveis em "C#"

Mod 6 -- **08/01/22**

Nessa aula, ele foi um pouco mais a fundo no que é uma variável de fato e me ensinou coisas que eu realmente não sabia:

A stack da memória ram, ela é definida em duas colunas, uma com o nome e outra com o valor, então quando definimos uma variável, ela vai percorrer a stack procurando o primeiro stack vazio possível para adicionar seu valor e essa stack tem um path, geralmente em hexadecimal que é usado para referenciarmos a esse espaço, esse path vai vai ser o na realidade o nome da nossa variável, e esse path não é substituído pelo nome, nós que só adicionamos um atalho para ele criando um atalho com o nome.

* **nota** = assim como no java, só podemos criar variáveis no escopo da classe e nos escopos "filhos"

* **Como criar variáveis**

>(tipo de acesso :Opcional) + (tipo da variável :Obrigatório) + (nome : obrigatório) = (valor :opcional)

~~~C#
public string name = "Um nome ai"; 
~~~

* tipos de acesso:

  * public = todos tem acesso, fora ou dentro da classe

* Tipos de variável

  * Int = um inteiro, exemplo 1
  
  * float = número com virgula

  * string = texto

  * bool = boolean, true ou false

## Adicionando script para gameObjects

Podemos simplesmente arrastar para o inspetor.
