# Produção e capacidade por tamanho e nível

Números de cada sala conforme o tamanho (simples, dupla, tripla) e o nível (1, 2, 3).

Regras de leitura:

- **Produção** é a quantidade de recurso entregue a cada ciclo, ou seja, a cada coleta. A wiki chama de "Output" e não dá a unidade; esta é a leitura mais provável, já que a sala produz um lote e espera a coleta (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms).
- **O tempo de cada ciclo** depende dos moradores. Ver "Tempo de ciclo" no fim do arquivo.
- **Estoque** é quanto a sala soma ao limite do recurso no vault.
- Os nomes entre parênteses são os nomes que a sala recebe em cada nível.

## Living room (moradia)

| Nível | Simples | Dupla | Tripla |
|---|---|---|---|
| 1 | 8 | 18 | 28 |
| 2 (Residence) | 10 | 22 | 34 |
| 3 (Barracks) | 12 | 26 | 40 |

Quantos moradores **moram** no vault. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Living_room)

- Não confunda com os 2, 4 e 6 moradores que podem **ficar dentro** da sala: isso é outra coisa. Ver `erros-comuns.md`.
- A capacidade total do vault é a soma dos Living rooms, até o limite de 200 moradores. — soma: `não verificado` (a wiki dá os valores por sala, mas não diz se existe capacidade extra fora dos Living rooms); limite de 200: `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms)
- Exemplo: 2 Living rooms duplos no nível 3 + 1 triplo no nível 3 = 26 + 26 + 40 = **92 moradores**, se a soma valer.

## Energia

Produção / estoque:

| Sala e nível | Simples | Dupla | Tripla |
|---|---|---|---|
| Power generator nível 1 | 10 / 50 | 21 / 100 | 44 / 150 |
| Power generator nível 2 (Power station) | 12 / 75 | 25 / 150 | 52 / 225 |
| Power generator nível 3 (Power plant) | 15 / 100 | 31 / 200 | 66 / 300 |
| Nuclear reactor nível 1 | 13 / 200 | 27 / 400 | 57 / 600 |
| Nuclear reactor nível 2 (Advanced reactor) | 15 / 300 | 32 / 600 | 68 / 900 |
| Nuclear reactor nível 3 (Super reactor) | 19 / 400 | 40 / 800 | 85 / 1200 |

`confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Power_generator, https://fallout.fandom.com/wiki/Nuclear_reactor)

## Comida

Produção / estoque:

| Sala e nível | Simples | Dupla | Tripla |
|---|---|---|---|
| Diner nível 1 | 8 / 50 | 18 / 100 | 28 / 150 |
| Diner nível 2 (Restaurant) | 10 / 75 | 22 / 150 | 34 / 225 |
| Diner nível 3 (Cafeteria) | 12 / 100 | 26 / 200 | 40 / 300 |
| Garden nível 1 | 10 / 50 | 22 / 100 | 35 / 150 |
| Garden nível 2 (Greenhouse) | 12 / 75 | 27 / 150 | 46 / 225 |
| Garden nível 3 (Hydroponics) | 15 / 100 | 31 / 200 | 55 / 300 |

`confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Diner_(Fallout_Shelter), https://fallout.fandom.com/wiki/Garden_(Fallout_Shelter))

## Água

Produção / estoque:

| Sala e nível | Simples | Dupla | Tripla |
|---|---|---|---|
| Water treatment nível 1 | 8 / 50 | 18 / 100 | 28 / 150 |
| Water treatment nível 2 (Station) | 10 / 75 | 22 / 150 | 34 / 225 |
| Water treatment nível 3 (Plant) | 12 / 100 | 26 / 200 | 40 / 300 |
| Water purification nível 1 | 10 / 50 | 22 / 100 | 35 / 150 |
| Water purification nível 2 (Purification station) | 12 / 75 | 27 / 150 | 46 / 225 |
| Water purification nível 3 (Super water purification) | 15 / 100 | 33 / 200 | 55 / 300 |

`confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Water_treatment, https://fallout.fandom.com/wiki/Water_purification)

Nota: na wiki, a dupla de nível 3 rende 31 no Garden e 33 na Water purification, apesar de as outras células serem iguais. Pode ser erro de digitação da wiki. — `não verificado`

## Nuka-Cola bottler (comida **e** água)

Produção / estoque, valendo para comida e para água ao mesmo tempo:

| Nível | Simples | Dupla | Tripla |
|---|---|---|---|
| 1 (Nuka-Cola bottler) | 10 / 50 | 22 / 100 | 35 / 150 |
| 2 (Nuka-Cola station) | 12 / 75 | 27 / 150 | 46 / 225 |
| 3 (Nuka-Cola plant) | 15 / 100 | 33 / 200 | 55 / 300 |

Produz a mesma quantidade de comida e de água que um Garden e uma Water purification juntos. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Nuka-Cola_bottler)

## Storage room (itens)

Capacidade de itens guardados:

| Nível | Simples | Dupla | Tripla |
|---|---|---|---|
| 1 | 10 | 20 | 30 |
| 2 (Depot) | 15 | 35 | 75 |
| 3 (Warehouse) | 25 | 55 | 125 |

`confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Storage_room)

Os saltos da tripla (30 → 75 → 125) são irregulares em relação às outras colunas. Vale conferir na tela do jogo antes de confiar. — `não verificado`

## Medbay e Science lab

| Item | Simples | Dupla | Tripla |
|---|---|---|---|
| Produção (Stimpak ou RadAway por ciclo) | 1 | 3 | 4 |
| Estoque | 10 | 20 | 30 |

`confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Medbay, https://fallout.fandom.com/wiki/Science_lab)

- A wiki traz também uma linha "Upgrade Bonus" com 1, 3 e 4, sem explicar o que é. Por isso **não** registro quanto o upgrade aumenta a produção. — `não verificado`
- Estoque por nível: ver `recursos-e-defesa.md`.

## Radio studio

Não produz recurso. Cada upgrade aumenta a chance de atrair moradores e o bônus de felicidade. A wiki não dá números. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Radio_studio)

## Tempo de ciclo

Cada sala tem uma "reserva" escondida. Todo segundo, cada morador soma à reserva o valor do atributo da sala, com o bônus de felicidade do vault. Quando a reserva enche, o recurso fica pronto. — `confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms)

| Sala | Reserva (pontos) | Tempo base |
|---|---|---|
| Power generator | 1320 | 22min |
| Nuclear reactor | 1800 | 30min |
| Diner | 960 | 16min |
| Water treatment | 960 | 16min |
| Garden | 1200 | 20min |
| Water purification | 1200 | 20min |
| Nuka-Cola bottler | 1200 | 20min |
| Medbay | 2400 | 40min |
| Science lab | 2400 | 40min |

`confirmado` · fonte: wiki (https://fallout.fandom.com/wiki/Fallout_Shelter_rooms)

- A reserva dobra na dupla e triplica na tripla. — `confirmado` · fonte: wiki
- O upgrade parece não mudar a reserva. A wiki usa "seems", então fica `não verificado`.
- Exemplo: um morador com Força 5 numa Power generator simples enche 1320 pontos em 1320 ÷ 5 = 264 segundos, cerca de 4,4 minutos sem contar a felicidade. A wiki arredonda para "4 minutos".
