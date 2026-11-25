# Recursos e defesa

## Regras gerais de produção

- Toda sala, exceto elevadores e a porta do vault, precisa de energia. Sem energia suficiente, as salas mais distantes da fonte param primeiro. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Power_generator)
- A velocidade de produção depende da **soma** do atributo da sala entre os moradores. Ex.: 4 moradores com Força 5 rendem como 2 com Força 10. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms)
- Tamanho, nível e felicidade dos moradores também alteram o tempo de produção. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms)
- A sala só produz o próximo lote depois que o atual é coletado. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms)

## Energia

| Sala | Atributo | Liberação | Certeza |
|---|---|---|---|
| Power generator | Força (S) | desde o início | `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Power_generator) |
| Nuclear reactor | Força (S) | 60 moradores; custa 1.200 tampinhas (+300 por reator existente) | `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Nuclear_reactor) |

- O Nuclear reactor gera mais energia por ciclo e guarda 4 vezes mais energia que o Power generator, mas custa bem mais para construir e melhorar. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Nuclear_reactor)
- O Nuclear reactor consome água. — `não verificado`, **provavelmente falso** (as páginas da wiki do reator e da usina não citam consumo de nenhum recurso)
  - Observação: o usuário trocou uma usina tripla por um reator triplo (destruiu e construiu). O estoque de água não mudou, e o marcador de consumo mínimo na barra de água também não se moveu. Esse marcador se move quando chega ou nasce um morador. — `testado` · fonte: teste do usuário
  - Leitura do teste: o FAQ explica que o marcador mostra o consumo mínimo em relação ao estoque. Com o estoque igual e o marcador parado, o consumo de água não aumentou. O jogo não mostra o consumo de cada sala, então isso não fica provado direto na tela. · fonte: FAQ (https://github.com/therabidsquirel/The-Fallout-Shelter-FAQ/wiki/Section-3:-Rooms,-Resources,-and-Storage)
  - Evidência contra: o FAQ da comunidade diz que **os moradores** consomem comida e água, e que todas as salas consomem energia, exceto elevadores, salas de energia e Overseer's Office. Não cita nenhuma sala que consuma água. · fonte: FAQ (https://github.com/therabidsquirel/The-Fallout-Shelter-FAQ/wiki/Section-3:-Rooms,-Resources,-and-Storage)
- **Não** dá para transformar a usina (Power generator) em Nuclear reactor. Para ter um reator no lugar da usina, é preciso destruir a usina e construir o reator no espaço livre. — `testado` · fonte: teste do usuário; concorda com a wiki, que trata o reator como sala construída à parte, com custo próprio (https://fallout.fandom.com/wiki/Nuclear_reactor)
  - Esta informação corrige um registro anterior que dizia que o reator era uma troca direta da usina. Ver `erros-comuns.md`.

### Produção e estoque por tamanho e nível

Ver `producao.md`.

## Comida e água

| Sala | Produz | Atributo | Liberação | Certeza |
|---|---|---|---|---|
| Diner | Comida | Agilidade (A) | desde o início | `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms) |
| Garden | Comida | Agilidade (A) | 70 moradores | `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms) |
| Water treatment | Água | Percepção (P) | desde o início | `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Water_treatment) |
| Water purification | Água | Percepção (P) | 80 moradores | `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms) |
| Nuka-Cola bottler | Comida **e** água | Resistência (E) | 100 moradores | `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms) |

## Invasões e incidentes

- A porta do vault é a primeira linha de defesa contra invasões. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms)
- Salas vazias são vulneráveis a infestações. Se ninguém for colocado lá para resolver, a infestação se espalha para as salas vizinhas. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms)
- Dica da wiki: manter salas fundidas e cheias de moradores treinados e equipados nos dois primeiros andares para conter invasores. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms)
- Sala grande e pouco ocupada é mais difícil de limpar em incidentes. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms)

## Overseer's Office

- Só pode existir um por vault. Depois de construído, some do menu de construção até ser destruído. — `testado` · fonte: teste do usuário; `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Overseer%27s_office)
- Libera com 18 moradores, custa 1.000 tampinhas, não recebe moradores e tem tamanho fixo de 2. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Overseer%27s_office)
- Serve para enviar moradores em quests. Nível 2 permite 2 quests ao mesmo tempo (requer 30 moradores, 3.500 tampinhas); nível 3 permite 3 (requer 55 moradores, 15.000 tampinhas). — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Overseer%27s_office)
- Destruir e reconstruir a sala não afeta as quests em andamento. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Overseer%27s_office)
- Quests podem trazer moradores novos. — `testado` · fonte: teste do usuário; `confirmado` · fonte: wiki ("Certain quests" como origem de moradores, https://fallout.fandom.com/wiki/Vault_dwellers_(Fallout_Shelter))
- Com o Overseer's Office construído, quem explora o Wasteland pode achar locais e encontrar sobreviventes, que vêm para o vault como moradores raros. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Vault_dwellers_(Fallout_Shelter))

## Medbay e Science Lab

| Sala | Produz | Atributo | Liberação | Certeza |
|---|---|---|---|---|
| Medbay | Stimpak | Inteligência (I) | 14 moradores | `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Medbay) |
| Science lab | RadAway | Inteligência (I) | 16 moradores | `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Science_lab) |

### Teto de Stimpaks e RadAways

- O jogo começa com capacidade 5 para Stimpak e 5 para RadAway. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms)
- Cada Medbay aumenta o teto de Stimpaks, e cada Science lab o de RadAways, conforme o tamanho: 10 (simples), 20 (dupla), 30 (tripla). — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Medbay, https://fallout.fandom.com/wiki/Science_lab)
- O teto **cresce com a fusão**. — `confirmado` · fonte: wiki
  - Evidência: o FAQ explica que o que conta é a **área total**: cada módulo de sala soma 10, fundido ou não. Uma tripla e três simples dão os mesmos 30. Fundir não dá bônus de estoque. · fonte: FAQ (https://github.com/therabidsquirel/The-Fallout-Shelter-FAQ/wiki/Section-3:-Rooms,-Resources,-and-Storage)
- O teto **cresce com o nível** da sala. — `não verificado`. A fórmula de capacidade da wiki (10 × tamanho) não usa o nível, o que indica que o upgrade **não** muda o teto. Conferir na tela do jogo antes e depois de um upgrade.
  - Evidência contra: o FAQ diz que, para o estoque de Stimpak e RadAway, "largura (e nível) não importam". · fonte: FAQ (https://github.com/therabidsquirel/The-Fallout-Shelter-FAQ/wiki/Section-3:-Rooms,-Resources,-and-Storage)
  - Observação do usuário (sem teste formal): a impressão é que juntar salas aumenta o teto e o upgrade não aumenta. Isso bate com a wiki e com o FAQ. Para virar `testado`, anote o teto antes e depois de um upgrade, sem construir outra sala no meio.
- Para **produzir**, Medbay e Science lab rendem mais como salas duplas do que como triplas. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Medbay); evidência a favor no FAQ

### Uso

- Um Stimpak cura 50% da vida do morador. Não cura dano de radiação; para isso é preciso RadAway. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Stimpak_(Fallout_Shelter))
- Cada morador leva no máximo 25 Stimpaks e 25 RadAways para a exploração. Na exploração, os Stimpaks são usados automaticamente quando a vida cai a 50% ou menos. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Stimpak_(Fallout_Shelter), https://fallout.fandom.com/wiki/Fallout_Shelter)
