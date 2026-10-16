---
navigation:
  parent: index.md
  title: Colossal Reactors
  position: 50
  icon: colossal_reactors:reactor_controller
---
<Column alignItems="center" fullWidth={true}>
  # <Color id="light_purple">Colossal Reactors</Color>

  <ItemImage id="colossal_reactors:reactor_controller" scale="2"/>

  Реакторы производят меньше пара, турбины получают из него гораздо больше энергии, а некоторые входы и выходы были изменены.
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

***

<Column alignItems="center" fullWidth={true}>
  ## <Color id="gold">Пар и хладагент</Color>
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

<Row>
  <ItemImage id="oritech:still_steam_bucket"/>
  ### <Color id="aqua">Водяное охлаждение производит пар Oritech</Color>
</Row>

Активно охлаждаемый реактор, работающий на воде, производит пар Oritech. Турбины Colossal Reactors принимают пар Oritech, как и Паровой двигатель Oritech, поэтому любой из них может использовать выработку реактора.

* Реактор с водяным охлаждением производит на 20% меньше пара: 0.8 мБ на 1 мБ воды (стандарт 1.0).

<ItemImage id="minecraft:air" scale="0.25"/>

<Row>
  <ItemImage id="colossal_reactors:turbine_controller"/>
  ### <Color id="aqua">Турбины</Color>
</Row>

* Турбина производит 120 RF на 1 мБ пара (стандарт 4), до учета коэффициентов катушек и лопастей.
* Подходит любой пар, включая пар от генератора Oritech, оснащенного аддоном Парового котла.

<ItemImage id="minecraft:air" scale="0.25"/>

<Row>
  <ItemImage id="ftb:industrial_coolant_bucket"/>
  ### <Color id="aqua">Индустриальный хладагент как теплоотвод</Color>
</Row>

Блоки источника индустриального хладагента работают как теплоотвод внутри реактора:

| Теплоотвод | Топливная эффективность | Энергия | Перегрев |
|---|:---:|:---:|:---:|
| <ItemImage id="minecraft:water_bucket"/> Вода | 1.0 | 1.0 | 1.0 |
| <ItemImage id="ftb:industrial_coolant_bucket"/> Инд. хладагент | 1.75 | 2.15 | 3.2 |

Это лучшая топливная эффективность среди жидкостей и больше энергии, чем от расплавленного Эндера. Создается путем сбрасывания Сухого льда в спокойный источник воды.

<ItemImage id="minecraft:air" scale="0.25"/>

***

<Column alignItems="center" fullWidth={true}>
  ## <Color id="gold">Топливо</Color>
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

<Row>
  <ItemImage id="colossal_reactors:red_cake"/>
  ### <Color id="aqua">Красный кекс</Color>
</Row>

Красный кекс больше не является топливом для реактора. Уран, Азурит и другое топливо без изменений.
