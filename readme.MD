# MVP — Análise de Dados e Boas Práticas

## Sobre o Projeto

Este projeto é uma análise exploratória do mercado de jogos da Steam, a maior plataforma de distribuição digital de games do mundo. Com mais de **27 mil títulos** no dataset, o objetivo é entender o que realmente faz um jogo se destacar em um ambiente tão competitivo.

A pergunta central é simples: **o que influencia o sucesso de um jogo na Steam?** Para responder, investigamos quatro hipóteses sobre preço, gênero, modo multiplayer e tempo de mercado.

## Dataset

Os dados vêm do [Steam Store Games](https://www.kaggle.com/datasets/nikdavis/steam-store-games), um dataset público com informações de jogos disponíveis na plataforma Steam — incluindo preço, avaliações de usuários, gêneros, categorias, estimativa de proprietários e data de lançamento.

## O que foi analisado

### H1 — Preço garante qualidade?
Testamos se jogos mais caros recebem avaliações melhores. A resposta curta: **não**. A correlação entre preço e taxa de aprovação é praticamente nula. Jogos baratos e gratuitos podem ser tão bem avaliados quanto títulos premium.

### H2 — Gêneros de nicho são mais bem avaliados?
Comparamos a satisfação dos jogadores entre gêneros populares (como Indie e Action) e gêneros mais específicos (como Simulation e RPG). Gêneros saturados tendem a ter notas medianas menores, enquanto nichos técnicos mantêm uma reputação mais alta.

### H3 — Multiplayer atrai mais jogadores?
Jogos com suporte a multiplayer possuem, em média, uma base de proprietários **mais de 4 vezes maior** do que jogos apenas single-player. O efeito de rede — onde cada novo jogador torna o jogo mais atrativo para outros — explica bem esse resultado.

### H4 — Jogos antigos acumulam mais credibilidade?
Títulos com mais tempo de mercado acumulam significativamente mais avaliações e proprietários. Essa "prova social" funciona como uma barreira competitiva natural para novos entrantes.