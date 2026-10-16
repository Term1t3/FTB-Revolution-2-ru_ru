---
navigation:
  title: Изменения в генерации энергии
  position: 0
  icon: powah:energy_cell_nitro
---


<Column alignItems="center" fullWidth={true}>
  # <Color id="gold">Изменения в генерации энергии</Color>

  <ItemImage id="powah:energy_cell_nitro" scale="2"/>

  FTB Evolution 2 перебалансирует энергию во всех технических модах, чтобы ни один генератор не делал остальные бесполезными. В этом руководстве перечислены изменения. Всё, что здесь не указано, работает так, как описано в моде.
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

> <Color id="yellow">Значения указаны как значения сборки (стандартное значение).</Color> FE и RF — это одно и то же.

<ItemImage id="minecraft:air" scale="0.25"/>

***

<Column alignItems="center" fullWidth={true}>
  ## <Color id="gold">Основные правила</Color>
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

* **Лава дает 10,000 FE за ведро** в Генераторе лавы Oritech, Тепловом генераторе Energized Power и Магматоре Powah.
* **Вода не является охлаждающей жидкостью реактора.** Тепловые генераторы и реакторы Powah работают на Индустриальном хладагенте, который создается путем сбрасывания Сухого льда в источник воды.
* **Существует только один вид пара.** Реакторы Colossal Reactors производят пар Oritech, и его используют как их турбины, так и Паровой двигатель Oritech.
* **Industrial Contraptions работает на FE.** Его генераторы и машины подключаются к кабелям любого другого мода, Выпрямитель энергии не нужен.
* **Некоторые ранние генераторы удалены**, поэтому линия электропередач каждого мода начинается там, где этого требует сборка.

<ItemImage id="minecraft:air" scale="0.25"/>

***

<Column alignItems="center" fullWidth={true}>
  ## <Color id="gold">Поиск генераторов</Color>
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

Ищите `$generator` в JEI, чтобы увидеть все блоки в сборке, производящие энергию, и `$energystorage` для тех, что её хранят.

<ItemImage id="minecraft:air" scale="0.25"/>

***

<Column alignItems="center" fullWidth={true}>
  ## <Color id="gold">Страницы</Color>
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

<SubPages icons={true} />
