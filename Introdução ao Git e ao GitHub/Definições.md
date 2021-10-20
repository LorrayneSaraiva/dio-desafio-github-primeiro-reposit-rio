### o que é um sistema distribuído?

um sistema que possui múltiplas cópias de si mesmo em diferentes locais

### O que é o SHA?

Algoritmo de Hash Seguro - Vai pegar o arquivo e embaralhar de uma maneira específica. 

2- Conjunto de funções hash criptográficas projetadas pela NSA

3- É uma forma curta de representar um arquivo 

### objetos Fundamentais do Git:

- BLOBS: contém metadados: tem o tipo do objeto, o tamanho, o conteúdo do arquivo

- Tree (tem relação com o blob): armazena blobs, apontando os tipos de BLOBS diferentes. Contém meta dados: guarda o blob, o sha1, o nome do arquivo

  Obs: se muda o sha da bolha, muda na árvore também

- Commit: "Junta tudo". Aponta para uma árvore, aponta para um parente(o commit usado antes dele), aponta para um autor, para uma mensagem. Também possuem sha1

  Obs: se altera algo no blob, altera na árvore, e altera no commit, e por isso o Git é tão confiável

### O que é Markdown?

é como um arquivo html, de forma "humanizada"; Por exemplo, os "#"equivale ao h1 do html

