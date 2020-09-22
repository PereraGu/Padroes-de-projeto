# Markdown

###### A. Pattern Name and Classification: 
É um padrão proposto para tratar um problema de design que ocorre em sistemas orientados a objetos. Dentre eles padrão composite e estrutural.

###### B. Intent: 
Responsável por separar a construção de um objeto complexo de sua representação para que o mesmo processo de construção possa criar diferentes representações. Relalizando assim a modificação da estrutura de um objeto.

###### C. Motivation: 
Explica um problema típico e específico, a motivação deixa claro que esse problema é generalizado. Pode incluir diagramas de classe ou diagramas de objetos, juntamente com uma descrição textual.

###### D. Applicability: 
É uma lista de condições que devem ser seguidas para a utilização correta da padronização. Essa lista deve conter o objetivo a ser alcançado, aspectos do programa e restrições. Pode fazer uso de grafos para representar sua estrutura.

###### E. Structure: 
Responsável por descrever os padrões em forma de diagramas de classe e diagramas de objetos. Os nomes apresentados nesses diagramas fazem parte dos citados nos exemplos específicos presentes na motivação.



###### F. Participants: 
Descrição das classes presentes na sessão de estrutura. A lista deve conter as responsabilidade e objetivos de cada classe do projeto.

###### G. Sample Code: 
É o código essencial para demonstrar um problema típico, presente geralmente na motivação. O código demonstra em detalhes o padrão aplicado.

## Composite

O Composite é um padrão de projeto estrutural que possibilita que objetos em uma estrutura semelhante a uma árvore, possibilitando assim trabalhar como se tivéssemos um único objeto. É principalmente utilizado para resolver problemas que necessitam de uma estrutura de árvore. Sua maior vantagem é sua capacidade de executar métodos repetitivos na estrutura do projeto e assim resumir o resultado dos problemas. Seu formato de árvore serve para representar uma estrutura hierárquica no projeto e a divisão de cada componente. Essa estrutura possui quatro elementos principais, folha, cliente, composite e componente. Na folha podemos observar os elementos da árvore e suas funções, o cliente é responsável por se comunicar com os as demais estruturas da árvore através dos componentes, os componentes por sua vez fazem a descrição dos elementos da árvore, dividido em funções e o composite fica responsável por executar essas funções e retornar seus resultados ao cliente.
