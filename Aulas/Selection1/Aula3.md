# Criando prefabs e componentes físicos

Mod 4 -- **01/10/21**

## O que são prefabs

São elementos pré criados que a unit disponibiliza

## Uma cena

conjunto de gameObjects, como se fosse cada fase e para salvar uma cena ele só criou outra e apertou em salvar, mas creio que para salvar é só ir em edit e salvar. Para acessar uma cena é só procurar ela nos Assets e para aparecer essa cena nos arquivos e nas pastas, ela deve estar na pasta Assets [nota] = as unidades x e y da escala estão sendo dadas em metros

## Aplicando gravidade a elementos tri-dimensionais

components -> physics para elementos 3d e physics 2d  para o 2d, mas no momento ele está criando em 3d. components -> physics -> rigidbody = para elementos físicos rígidos e o colisor deve estar ativado.

## Transformando elementos em elementos pré-fabricados

É bom primeiramente colocar isso em uma pasta, para  ele virar uma prefab é só puxar o elemento da hierarquia e colocar na pasta. E quando puxar de volta o elemento para a cena, o nome do elemento ficará azul.

Ao fazer isso, todos os prefabs vão ficar de acordo com o original e todas mudanças são feitas automaticamente.  
A rotação e a posição n surtem efeito nos filhos, porém a escala muda, lembrando que você deve mudar no prefab e não no objeto, mudanças no objeto não serão feitas para todos os prefabs. Para alterarem todos, você deve ir no inspetor e em baixo das tags e dos layers, terá a opção prefabs e apertando apply, todos os prefabs serão mudados, todas as alterações em negrito vão ser aplicadas.

* **nota:** as vezes quando você faz um prefab que é composto por dois elementos, você vai ter que tirar todos os objetos e colocar eles de novo.

* **nota:** quando você cria um objeto que tem outro objeto nele que é parte dele, para que ele não tenha física própria, seja independente do objeto, tem que retirar o componente de gravidade, apertando botão direito no  rigidbody
