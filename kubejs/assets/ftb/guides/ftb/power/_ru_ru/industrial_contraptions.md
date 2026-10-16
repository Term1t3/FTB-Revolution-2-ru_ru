---
navigation:
  parent: index.md
  title: Industrial Contraptions
  position: 20
  icon: ftbic:basic_generator
---
<Column alignItems="center" fullWidth={true}>
  # <Color id="light_purple">Industrial Contraptions</Color>

  <ItemImage id="ftbic:basic_generator" scale="2"/>

  Industrial Contraptions использует FE напрямую. Его генераторы подают FE в кабели любого мода, а машины принимают FE с любой стороны, поэтому Выпрямители энергии больше не нужны. Генераторы, солнечные панели, кабели и буферы машин до четырех раз мощнее стандартных.
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

***

<Column alignItems="center" fullWidth={true}>
  ## <Color id="gold">Генераторы</Color>
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

| Генератор | Выход |
|---|:---:|
| <ItemImage id="ftbic:basic_generator"/> Базовый генератор | 320 FE/t (80) |
| <ItemImage id="ftbic:geothermal_generator"/> Геотермальный генератор | 320 FE/t (160) |
| <ItemImage id="ftbic:wind_mill"/> Ветряк | 9.6 – 104 FE/t (2.4 до 52) |
| <ItemImage id="ftbic:lv_solar_panel"/> LV Солнечная панель | 32 FE/t (8) |
| <ItemImage id="ftbic:mv_solar_panel"/> MV Солнечная панель | 256 FE/t (64) |
| <ItemImage id="ftbic:hv_solar_panel"/> HV Солнечная панель | 2,048 FE/t (512) |
| <ItemImage id="ftbic:ev_solar_panel"/> EV Солнечная панель | 16,384 FE/t (4,096) |

Ветряк по-прежнему ничего не производит ниже y64 и максимум на y320, с бонусом во время дождя или грозы.

<ItemImage id="minecraft:air" scale="0.25"/>

<Row>
  <ItemImage id="ftbic:nuclear_reactor"/>
  ### <Color id="aqua">Ядерный реактор</Color>
</Row>

* Выходная мощность в **четыре раза** выше стандартной.
* Водяное охлаждение в **пять раз** эффективнее (множитель 10, было 2).
* Внутренний буфер в два раза больше.
