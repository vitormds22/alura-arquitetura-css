# Curso Alura - Arquitetura CSS

Seguiremos nesse curso o layout do link abaixo para nos auxiliar no desenvolvimento da estilização da página:

https://www.figma.com/file/0gMF5BPgplPYqQA6Om1T1sk9/alura-bootstrap?node-id=0%3A1

## O que aprendi no curso

1. Arquitetura de projetos CSS
      * Utilização de tag para estilização
      * Não amarrar diretamente os estilos às tags, mas sim utilizar classes
      * Sempre bom separar os arquivos css para cada parte da nossa página HTML
2. Atomic Design
      * Ajuda a organizar melhor os componentes;
      * Cada **átomo** é relacionado ao elementos HTML (Input, Label, Button);
      * Cada **molécula** é relacionada à junção dos **átomos**, ou seja, um conjunto de tags;
      * Cada **organismo** é a junção de várias **moléculas**;
      * Cada **template** é a junção de vários **organismos**;
      * As **páginas** são diferentes de **templates**, pois eles são mais abstratos. As **páginas** são mais reais, com imagens e textos condizentes ao projeto final.
3. Metodologia BEM
      * BLOCK ELEMENT MODIFIER
      * É um padrão para nomear as classes com base nos três pilares
      * **Bloco** sempre será o contexto maior das classes -> bloco
      * **Elemento** será separado por underline -> bloco__elemendo
      * **Modificador** será o filho do elemento separado por traço -> bloco__elemendo--modificador
      * Ou até mesmo -> bloco--modificador