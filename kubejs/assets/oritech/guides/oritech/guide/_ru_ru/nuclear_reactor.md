---
navigation:
  title: Ядерный реактор
  position: 4
  icon: "oritech:nuclear_reactor_controller"
item_ids:
  - oritech:nuclear_reactor_controller
  - oritech:reactor_wall
  - oritech:reactor_fuel_port
  - oritech:reactor_rod
  - oritech:reactor_double_rod
  - oritech:reactor_quad_rod
  - oritech:reactor_neutron_reflector
  - oritech:reactor_energy_port
---
# <Color id="green">Ядерный реактор</Color>

<Column alignItems="center" fullWidth={true}>
  # <Color id="green">Ядерный реактор</Color>

  <ItemImage id="oritech:nuclear_reactor_controller" scale="2"/>

  <Color id="green">Ядерный реактор</Color> потребляет капсулы <Color id="yellow">урана</Color> или <Color id="light_purple">плутония</Color> для генерации большого количества <Color id="gold">RF</Color> энергии. Выходная мощность зависит от количества топливных стержней и нейтронных отражателей внутри. Реакторы должны быть достаточно охлаждены, иначе они расплавятся.
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

***

<Column alignItems="center" fullWidth={true}>
  ## <Color id="gold">Структура</Color>
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

Реактор строится как **прямоугольная полая коробка** из <Color id="green">Стен реактора</Color>. Важные правила:

- Максимальный размер — **64 блока в каждом направлении**
- <Color id="green">Контроллер реактора</Color> и <Color id="green">Энергетические порты</Color> должны быть размещены где-то на **внешних стенках**, опциональные <Color id="green">Порты красного камня</Color> также могут быть размещены на этих **внешних стенках**.
- <Color id="green">Топливные порты</Color> и <Color id="green">Порты охлаждения</Color> размещаются на **внешнем потолке**, прямо над соответствующими внутренними комплектами оборудования.
- Все остальные компоненты (стержни, трубы, вентиляция, поглотители) размещаются **внутри**.
- Интерьер должен быть **идентичен на каждом вертикальном уровне**; создайте шаблон и масштабируйте высоту по желанию. Выходная мощность, потребление топлива и использование охлаждающей жидкости масштабируются вместе с высотой.

<ItemImage id="minecraft:air" scale="0.25"/>

***

<Column alignItems="center" fullWidth={true}>
  ## <Color id="gold">Компоненты</Color>
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

<Row>
  <ItemImage id="oritech:nuclear_reactor_controller"/>
  ### <Color id="aqua">Контроллер реактора</Color>
</Row>

<Color id="green">Контроллер реактора</Color> — это сердце реактора. Разместите его в любом месте на внешних стенках, затем взаимодействуйте с ним, чтобы собрать или обновить структуру. GUI отображает текущее состояние, температуру компонентов и статистику генерации.

<ItemImage id="minecraft:air" scale="0.25"/>

<Row>
  <ItemImage id="oritech:reactor_wall"/>
  ### <Color id="aqua">Стена реактора</Color>
</Row>

<Color id="green">Стены реактора</Color> образуют прочную внешнюю оболочку реактора. Из них состоит весь каркас: верх, низ и боковые стороны.

<ItemImage id="minecraft:air" scale="0.25"/>

<Row>
  <ItemImage id="oritech:reactor_rod"/>
  ### <Color id="aqua">Топливные стержни</Color>
</Row>

<ItemGrid>
  <ItemIcon id="oritech:reactor_rod"/>
  <ItemIcon id="oritech:reactor_double_rod"/>
  <ItemIcon id="oritech:reactor_quad_rod"/>
</ItemGrid>

<Color id="gold">Топливные стержни</Color> — это внутренние компоненты, которые сжигают топливо. Они бывают <Color id="green">одинарными</Color>, <Color id="yellow">двойными</Color> и <Color id="red">четверными</Color>. Каждый вариант генерирует больше тепла и RF в тик. Каждому комплекту стержней требуется <Color id="green">Топливный порт</Color>, размещенный прямо над ним на внешнем потолке.


<ItemImage id="minecraft:air" scale="0.25"/>

<Row>
  <ItemImage id="oritech:reactor_neutron_reflector"/>
  ### <Color id="aqua">Нейтронный отражатель</Color>
</Row>

<Color id="green">Нейтронные отражатели</Color> лучше всего размещать рядом с топливными стержнями, чтобы отражать нейтроны обратно в стержень, повышая их эффективность без необходимости добавлять еще один стержень. Отличный способ увеличить выходную мощность в компактной компоновке.

<ItemImage id="minecraft:air" scale="0.25"/>

<Row>
  <ItemImage id="oritech:reactor_fuel_port"/>
  ### <Color id="aqua">Топливный порт реактора</Color>
</Row>

<Color id="green">Топливный порт реактора</Color> размещается на **внешнем потолке** прямо над комплектом стержней. Вставляйте <Color id="yellow">Урановые капсулы</Color> или <Color id="light_purple">Плутониевые капсулы</Color> сюда, чтобы стержни продолжали гореть.

<ItemImage id="minecraft:air" scale="0.25"/>

<Row>
  <ItemImage id="oritech:reactor_energy_port"/>
  ### <Color id="aqua">Энергетический порт реактора</Color>
</Row>

<Color id="green">Энергетические порты реактора</Color> размещаются на внешних стенках для вывода сгенерированной RF энергии. Каждый порт может отдавать до <Color id="gold">50,000,000 RF/t</Color>.

<ItemImage id="minecraft:air" scale="0.25"/>

<Row>
  <ItemImage id="oritech:reactor_redstone_port"/>
  ### <Color id="aqua">Порт красного камня реактора</Color>
</Row>

<Color id="green">Порт красного камня реактора</Color> размещается на внешних стенках. Подача сигнала красного камня предотвратит загрузку нового топлива. Любая уже горящая капсула сначала догорит. Нажатие правой кнопкой мыши по порту переключает режим выхода компаратора между <Color id="gold">Энергией</Color>, <Color id="aqua">Количеством активных стержней</Color> и <Color id="red">Температурой</Color>.

<ItemImage id="minecraft:air" scale="0.25"/>

***

<Column alignItems="center" fullWidth={true}>
  ## <Color id="gold">Дополнительная информация</Color>
</Column>

<SubPages icons={true} />
