# Podcast Menager

O dominio será os podcasts e as funçõe encima

### Descrição
Um app ao estilo netflix, onde possa centralizar diferentes podcasts separados por categoria

### Domínio 
Podcasts feitos em video

### Features
- Listar os episódios em sessões de categorias
    - [saúde, fitness, mentalidade, humor]
- Filtrar episódios por nome de podcast

### Como
Primeiro voce decide o que quer cozinhar, para depois decidir os ingredientes que vai utilizar.
#### Feature:
- Listar os episódios podcasts em sessões de categorias
### Como vou implementar:
Vou retornar em uma api rest(json) o nome do podcast, nome do episódio, imagem de capa, link

```js
[
    {
        podcastName: "flow",
        episode: "RAFAEL GRATTA - Flow #408",
        videoId: "Z38tcbrvFow",
        cover: "https://i.ytimg.com/vi/Z38tcbrvFow/hqdefault.jpg"
        link: "https://www.youtube.com/watch?v=Z38tcbrvFow"
        categories: ["saúde", "neurociencia", "psicologia"]
    },
    {
        podcastName: "flow",
        episode: "GUSTAVO FERRAREZI + RATO BORRACHUDO - Flow #409",
        videoId: "eoBS45Tufgw"
        cover: "https://i.ytimg.com/vi/eoBS45Tufgw/hqdefault.jpg"
        link: "https://www.youtube.com/watch?v=eoBS45Tufgw"
        categories: ["saúde", "humor", "teorias","futebol"]
    }

]

```