---
navigation:
  title: Центр данных
  icon: hostilenetworks:data_center
  position: 1
  parent: index.md
item_ids:
  - hostilenetworks:data_center
  - hostilenetworks:data_center_io_port
---

<Column alignItems="center" fullWidth={true}>
  # <Color id="gold">Центр данных</Color>

  <ItemImage id="hostilenetworks:data_center" scale="2"/>

  Запускает до 25 Самоосознанных моделей данных одновременно и является единственным местом в этой сборке, где модели данных производят предметы.
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

***

<Column alignItems="center" fullWidth={true}>
  ## <Color id="gold">Оболочка</Color>
</Column>

<Column alignItems="center" fullWidth={true}>
  <GameScene zoom="2" interactive={true} background="#333333">
    <ImportStructure src="data_center.nbt"/>
    <IsometricCamera yaw="-45" pitch="30"/>
    <BoxAnnotation min="1 1 1" max="6 6 6" color="#ff5555">
      Внутреннее пространство 5x5x5 должно быть пустым (воздух).
    </BoxAnnotation>
    <BlockAnnotation x="3" y="1" z="6" color="#ffaa00">
      Контроллер, повернут **наружу** оболочки.
    </BlockAnnotation>
    <BlockAnnotation x="5" y="1" z="6" color="#55ffff">
      Порты ввода/вывода (IO) опциональны и могут заменить любой блок стены или потолка.
    </BlockAnnotation>
  </GameScene>
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

* Оболочка имеет размер 7x7x7. Пол — <ItemLink id="minecraft:obsidian"/> (что угодно из тега obsidian).
* Стены и потолок — <ItemLink id="minecraft:black_stained_glass"/> или <ItemLink id="hostilenetworks:data_center_io_port"/>.
* <ItemLink id="hostilenetworks:data_center"/> заменяет блок стены в первом ряду над полом, повернут наружу. Любая позиция вдоль этой стены подходит, включая углы.
* Когда оболочка собрана неверно, экран контроллера перечисляет недостающие блоки с их координатами.

<ItemImage id="minecraft:air" scale="0.25"/>

***

<Column alignItems="center" fullWidth={true}>
  ## <Color id="gold">Запуск моделей</Color>
</Column>

* Поместите Самоосознанные модели в сетку 5x5. Модели низших уровней не принимаются.
* Поместите <ItemLink id="hostilenetworks:prediction_matrix"/> в четыре входных слота. Каждая модель использует одну за цикл.
* <Color id="red">Нажмите правой кнопкой мыши по слоту модели, чтобы выбрать, что она производит.</Color> Модель, для которой ничего не выбрано, не работает. <Color id="aqua">Фиксированный</Color> (Fixed) повторяет один выпад; <Color id="aqua">Очередь</Color> (Queue) проходит по списку.
* Цикл длится 15 секунд. Он дает <Color id="green">Обобщенное предсказание</Color> модели плюс один выбранный предмет в выходной буфер на 16 слотов.
* Энергия за тик для каждой модели — это стоимость моделирования плюс 25%. Буфер вмещает 20,000,000 FE.

<ItemImage id="minecraft:air" scale="0.25"/>

***

<Column alignItems="center" fullWidth={true}>
  ## <Color id="gold">Порты ввода/вывода (IO)</Color>
</Column>

<Row>
  <ItemImage id="hostilenetworks:data_center_io_port"/>
  ### <Color id="aqua">Порт ввода/вывода Центра данных</Color>
</Row>

Контроллер принимает энергию и предметы сам по себе. Порты позволяют трубам и кабелям подключаться к Центру данных с других сторон оболочки. Нажмите правой кнопкой мыши по порту, чтобы переключить его режим.

| Режим | К чему подключается |
|---|---|
| <Color id="aqua">Энергия</Color> | Энергетический буфер |
| <Color id="aqua">Модели</Color> | Сетка моделей 5x5 |
| <Color id="aqua">Входы</Color> | Четыре входных слота |
| <Color id="aqua">Выходы</Color> | Выходной буфер, только экстракция |

Каждый порт может находиться в одном режиме за раз. Используйте столько, сколько вам нужно.
