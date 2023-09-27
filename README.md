# SpotifyAPInsights
Um repositório para tratar dados da API do Spotify e visualização exploratória para revelar insights musicais.

## 1 - Obtenção de dados
Para obter os dados, é necessário criar uma conta no [Spotify for Developers](https://developer.spotify.com/dashboard/login) e criar um app para obter as credenciais de acesso. Após isso, basta preencher as variáveis de ambiente no arquivo `.env` com as credenciais obtidas, que estará oculto neste respositório por motivos de segurança.

Além disso, criei uma função para obter informações específicas de cada música, como artista, id, popularidade, ano de lançamento e gênero. Depois, criei uma função para obter as features de cada música, como duração, tempo, tom, etc.

## 2 - Análise exploratória
Aqui começamos com uma análise descritiva das variáveis numéricas, prosseguindo a observar a correlação entre as features das músicas. Também comparamos como essas features se comportam para cada gênero musical. E coletamos informações em relação ao tempo de duração de músicas e sua popularidade por ano de lançamento.


## 3 - Referências
As referências utilizadas para a criação desse projeto foram:
- https://developer.spotify.com/documentation/web-api/reference/get-audio-features
-  https://www.youtube.com/watch?v=RHIJpN5a_bk

Para obtenção das features de áudio das músicas e para estruturar uma função que gerasse o dataframe.

## 4 - Link com a visualização do projeto

https://iaracastro.github.io/SpotifyAPInsights/
