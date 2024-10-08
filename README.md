
# Aprendendo Flask com a API Rick and Morty

Este repositório contém um projeto de aplicação web desenvolvida com Flask, que utiliza a API Rick and Morty para exibir informações sobre personagens, episódios e locais. O projeto faz parte do Bootcamp da WoMakersCode e utiliza Bootstrap para a estilização das páginas.

## Estrutura do Projeto

### Arquivos e Funções

- **`app.py`**: Arquivo principal da aplicação Flask. Define as rotas e a lógica para interagir com a API Rick and Morty.
  - `/`: Exibe uma lista de personagens.
  - `/profile/<id>`: Mostra os detalhes de um personagem específico.
  - `/lista`: Retorna uma lista simplificada de personagens em formato JSON.
  - `/episodes`: Retorna uma lista de episódios em formato JSON.
  - `/episodes/<id>`: Mostra os detalhes de um episódio específico.
  - `/locations`: Exibe uma lista de locais.
  - `/locations/<id>`: Mostra os detalhes de um local específico.

- **`templates/`**: Diretório que contém os templates HTML utilizados pela aplicação.
  - **`layout.html`**: Layout base que inclui a estrutura principal da página e a barra de navegação. Todos os outros templates estendem este layout.
  - **`characters.html`**: Exibe a lista de personagens, com opções para visualizar detalhes de cada personagem.
  - **`profile.html`**: Mostra informações detalhadas sobre um personagem específico, como status, espécie, gênero, origem e localização.
  - **`episodes.html`**: Exibe a lista de episódios, com opções para visualizar detalhes de cada episódio.
  - **`episode.html`**: Mostra informações detalhadas sobre um episódio específico, incluindo a lista de personagens que aparecem nele.
  - **`locations.html`**: Exibe a lista de locais, com opções para visualizar detalhes de cada local.
  - **`location.html`**: Mostra informações detalhadas sobre um local específico, incluindo a lista de residentes.

