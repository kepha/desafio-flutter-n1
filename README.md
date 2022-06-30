# Desafio Flutter - Nível 1

Desenvolver o aplicativo de Pokedex, seguindo os protótipos que se encontram na pasta [*design*](./design/design.xd).

- Os protótipos foram desenhados usando o [Adobe XD](https://www.adobe.com/br/products/xd.html), o qual pode ser baixado gratuitamente
- Os Pokémons devem ser consultados usando a API https://pokeapi.co
- A lista de Pokémons virá da consulta no endpoint */pokemon*. https://pokeapi.co/docs/v2#pokemon
- As cores de fundo usadas nos cards são baseadas no tipo principal do Pokémon, pelo atributo *types* com *slot=1*
- A imagem principal vem do atributo *sprites.front_default*
- A listagem é tratada de forma paginada pela API, https://pokeapi.co/docs/v2#resource-listspagination-section
- Deve ser buscado os 60 primeiros Pokémons, usando o Query Param *?limit=60*
- Os detalhes são consultados no endpoint */pokemon/{id}*
