# Atributos e treino

## Salas de treino

| Atributo | Sala | Moradores para liberar | Certeza |
|---|---|---|---|
| Força (S) | Weight room | 24 | `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Weight_room) |
| Percepção (P) | Armory | 28 | `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Armory) |
| Resistência (E) | Fitness room | 35 | `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fitness_room) |
| Inteligência (I) | Classroom | 30 | `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Classroom) |
| Agilidade (A) | Athletics room | 26 | `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Athletics_room) |
| Carisma (C) | Lounge | 40 | `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Lounge) |
| Sorte (L) | Game room | 45 | `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Game_room) |

O nome correto da sala de Agilidade é **Athletics room** (com "s"). Ver `erros-comuns.md`.

## Regras de treino

- Salas de treino fundem até 3. A fusão aumenta a capacidade: 2, 4 e 6 moradores. — `testado` · fonte: teste do usuário; `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms)
- O upgrade de nível da sala de treino só muda a velocidade, não a capacidade. — `testado` · fonte: teste do usuário; `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Weight_room)
- Mais moradores treinando na mesma sala deixam o treino de todos um pouco mais rápido. A fusão em si não acelera; ela acelera indiretamente por caber mais gente. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Weight_room)
- Cada atributo treina até no máximo 10. Ao chegar a 10, aparece "Max Level Reached". — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Vault_dwellers_(Fallout_Shelter))
- Ao ganhar um ponto, aparece um ícone sobre o morador. É preciso tocar nele para o próximo ponto começar a treinar. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Vault_dwellers_(Fallout_Shelter))
- Tirar o morador da sala no meio do treino não perde o progresso parcial. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms)
- Roupas que aumentam atributos acima de 10 não aparecem na barra S.P.E.C.I.A.L., mas aumentam a produção. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms)

### Fórmula da wiki

Pontos por segundo = (1 + 0,02 × (D − 1)) × (1 + 0,05 × (T − 1)) × (1 + H)

- D = moradores treinando na sala (1 a 6)
- T = nível da sala (1 a 3)
- H = bônus de felicidade do vault (0,01 a 0,1)

Ou seja, cada nível de sala acelera cerca de 5%, e cada morador extra acelera cerca de 2%. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms)

## Tabela de tempos medidos no vault do usuário

Tempo para ganhar **um ponto**, por nível da sala. — `testado` · fonte: teste do usuário

| Ponto | Sala nível 1 | Sala nível 2 | Sala nível 3 |
|---|---|---|---|
| 1 → 2 | 26min | 25min | 24min |
| 2 → 3 | 1h20 | 1h16 | 1h13 |
| 3 → 4 | 2h40 | 2h32 | 2h26 |
| 4 → 5 | 4h27 | 4h14 | 4h03 |
| 5 → 6 | 6h41 | 6h22 | 6h05 |
| 6 → 7 | 9h21 | 8h55 | 8h31 |
| 7 → 8 | 12h28 | 11h53 | 11h21 |
| 8 → 9 | 16h02 | 15h17 | 14h36 |
| 9 → 10 | 20h03 | 19h06 | 18h15 |

Ocupação da sala e felicidade do vault no momento da medição: **não informadas**. Pela fórmula acima, esses dois fatores mudam o tempo. Por isso os valores podem variar em outro vault.

## Tempos base da wiki (sem bônus)

| Ponto | Tempo base |
|---|---|
| 1 → 2 | 30min |
| 2 → 3 | 1h30 |
| 3 → 4 | 3h00 |
| 4 → 5 | 5h00 |
| 5 → 6 | 7h30 |
| 6 → 7 | 10h30 |
| 7 → 8 | 14h00 |
| 8 → 9 | 18h00 |
| 9 → 10 | 22h30 |

`confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms)

Os tempos medidos pelo usuário são menores que os tempos base porque incluem bônus de felicidade e de ocupação.

## Efeito da Sorte (L)

| Efeito | Certeza |
|---|---|
| Aumenta a chance de sucesso do Rush | `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Luck) |
| Aumenta a quantidade de energia, comida e água obtida das salas | `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Luck) |
| Aumenta a chance de achar itens na exploração do Wasteland | `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Luck) |
| Aumenta a chance de ganhar tampinhas ao coletar recursos das salas | `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Luck) |
| Aumenta as tampinhas ganhas na exploração do Wasteland | `não verificado` (a seção de Fallout Shelter da wiki fala em itens, não em tampinhas) |
| Aumenta a chance de acerto crítico em combate | `não verificado` (a seção de Fallout Shelter da wiki não cita crítico; esse efeito aparece em outros jogos da série) |
