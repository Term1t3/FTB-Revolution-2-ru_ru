---
navigation:
  parent: index.md
  title: Хладагент, пар и топливо
  position: 15
  icon: powah:dry_ice
---
<Column alignItems="center" fullWidth={true}>
  # <Color id="light_purple">Хладагент, пар и топливо</Color>

  <ItemImage id="powah:dry_ice" scale="2"/>
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

***

<Column alignItems="center" fullWidth={true}>
  ## <Color id="gold">Хладагент и нагрев</Color>
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

<Row>
  <ItemImage id="ftb:industrial_coolant_bucket"/>
  ### <Color id="aqua">Индустриальный хладагент</Color>
</Row>

Индустриальный хладагент заменяет воду везде, где реактору требуется охлаждение. Сбросьте **Сухой лед** в спокойный блок источника воды, и он превратится в Индустриальный хладагент.

* **Powah:** единственный жидкий хладагент для Тепловых генераторов и Реакторов. Вода не работает.
* **Colossal Reactors:** работает как теплоотвод внутри реактора. См. [Colossal Reactors](colossal_reactors.md).

<ItemImage id="minecraft:air" scale="0.25"/>

<Row>
  <ItemImage id="auroral:shimmering_ice"/>
  ### <Color id="aqua">Твердые хладагенты Powah</Color>
</Row>

Обычные твердые хладагенты всё ещё работают: снежки, блоки снега, лед, плотный лед, синий лед и Сухой лед. Сборка добавляет один новый:

| Хладагент | Количество | Температура |
|---|:---:|:---:|
| <ItemImage id="auroral:shimmering_ice"/> Мерцающий лед | 712 | -32 |

<ItemImage id="minecraft:air" scale="0.25"/>

<Row>
  <ItemImage id="powah:blazing_crystal_block"/>
  ### <Color id="aqua">Источники тепла Powah</Color>
</Row>

Тепловые генераторы под этими блоками работают горячее или холоднее, чем раньше:

| Блок | Тепло |
|---|:---:|
| <ItemImage id="powah:blazing_crystal_block"/> Блок пылающего кристалла | 1,500 (2,800) |
| <ItemImage id="oritech:manhattan_module"/> Модуль «Манхэттен» | 4,000 (новый) |
| <ItemImage id="ftbic:nuke"/> Ядерная бомба | 4,000 (новая) |
| <ItemImage id="justdirethings:coalblock_t4"/> Блок эклипса | 3,000 (новый) |

Магма-блоки и лава прежние.

<ItemImage id="minecraft:air" scale="0.25"/>

***

<Column alignItems="center" fullWidth={true}>
  ## <Color id="gold">Пар</Color>
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

Пар Oritech — это единственный пар в сборке. Охлаждаемые водой Colossal Reactors производят его, турбины Colossal Reactors сжигают его, и паровой двигатель Oritech сжигает его. Свободно передавайте пар из одного мода в другой.

<ItemImage id="minecraft:air" scale="0.25"/>

***

<Column alignItems="center" fullWidth={true}>
  ## <Color id="gold">Топливо</Color>
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

<Row>
  <ItemImage id="minecraft:lava_bucket"/>
  ### <Color id="aqua">Лава</Color>
</Row>

Ведро лавы дает **10,000 FE** в каждом генераторе, использующем её как топливо:

* Генератор лавы Oritech: 10,000 (76,800)
* Тепловой генератор Energized Power: 10,000 (50,000)
* Магматор Powah: 10,000 (стандарт)
