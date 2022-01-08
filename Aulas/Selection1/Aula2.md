# Criando e manipulando Game Objects

Mod 3 -- **27/08/22**

## Criando um elemento

Para criar elementos tridimensionais, em GameObjects na interface da unity e lá dá para adicionar, elementos bi dimensionais, objetos de audio, luz, camera e elementos 3, primitivas que a unity disponibiliza. Outro jeito muito bom de criar um elemento é na hierarquia mesmo usando o create

## E os elementos criados, possuem atributos, como

* **position** = que é a posição como o nome já diz...

* **mash filter** = seleciona qual a  malha que o elemento tá exibindo;

* **box colíder** = que é o colisor do elemento;

* **mash renderer** = faz com que esse elemento seja renderizado na tela;

Ferramentas interessantes do lado esquerdo superior para manipular os objetos, não tenho o nome certo para essas ferramentas, então vou apelida-lás na ordem.

**ferramenta de movimentação da tela** = movimenta a tela  
**movimentação de objetos** = movimenta os objetos  
**rotação de objetos** = rotaciona objetos  
**redimensionamento de objetos** = faz escalar os objetos no eixo definido  
**redimensionalisar elementos 2d** = ela faz o que o nome diz  

Na **"rotação de objetos"** e nas **"movimentações"**, tem como escolher global ou local para definir os eixos dos objetos (global) ela não muda independente da orientação do elemento

> z para frente, y para cima e x para o lado

E na **Local** o xyz vai depender da orientação do elemento.

## Atalhos de teclado

* tem um atalho para duplicar selecionando e usando **ctrl+d**

* e um para deletar selecionando e usando **delete**

* usando a tecla **f** selecionando um elemento, dá para fazer a camera focar nele ou selecionando o elemento, ir em  GameObjects e align view to sleeted;

* selecionando ctrl, tem como você selecionar vários objetos

## Alinhando a camera

* Para alinhar a camera com a sua visão, um jeito muito interessante é ir em GameObjects e depois align  with view selecionando a camera;

* Outra coisa interessante é que para a câmera seguir um objeto ela deve estar parenteada com o objeto. filha dele na hierarquia.

Quando um componente é resetado, na área do inspector os valores padrões são resetados na engrenagem de cada componente no inspetor..

Para criar um chão simples por exemplo, se criou um cubo e resetou as posições dele, após criar um cubo e escalar os componentes dele em z e em x, aumentando a profundidade e largura do chão

prefabs de vários gameobjects já pré fabricados
