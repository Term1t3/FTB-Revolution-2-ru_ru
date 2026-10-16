---
navigation:
  title: Враждебные нейронные сети
  icon: hostilenetworks:deep_learner
  position: 0
item_ids:
  - hostilenetworks:deep_learner
  - hostilenetworks:blank_data_model
  - hostilenetworks:sim_chamber
  - hostilenetworks:prediction_matrix
---

<Column alignItems="center" fullWidth={true}>
  # <Color id="gold">Враждебные нейронные сети</Color>

  <ItemImage id="hostilenetworks:deep_learner" scale="2"/>

  Обучите Модель данных тому, как сражается моб или как формируется руда, а затем позвольте Центру данных превратить это знание в добычу и руду.
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

***

<Column alignItems="center" fullWidth={true}>
  ## <Color id="gold">Цикл</Color>
</Column>

1. Нажмите правой кнопкой мыши по мобу или рудному блоку с <ItemLink id="hostilenetworks:blank_data_model"/>, чтобы настроить её. Только мобы и руды с моделями могут быть настроены; [Модели данных](data_models.md) перечисляет те, которые добавляет эта сборка.
2. Поместите модель в <ItemLink id="hostilenetworks:deep_learner"/> (4 слота). Обучающее устройство ведет счет, пока находится в вашем основном инвентаре, во второй руке или в слоте Curio.
3. Убейте моба или добудьте руду без Шелкового касания. Каждое убийство или добытый блок добавляют данные в каждую подходящую модель в обучающем устройстве.
4. Как только модель достигнет уровня <Color id="green">Базовый</Color> (6 данных), <ItemLink id="hostilenetworks:sim_chamber"/> сможет обучить её дальше без сражений. Камеры отказываются принимать Ошибочные (Faulty) модели.
5. Как только модель достигнет уровня <Color id="gold">Самоосознание</Color>, переместите её в [Центр данных](data_center.md). Именно оттуда поступают ресурсы.

<ItemImage id="minecraft:air" scale="0.25"/>

***

<Column alignItems="center" fullWidth={true}>
  ## <Color id="gold">Уровни моделей</Color>
</Column>

| Уровень | Требуемые данные | Данные за убийство или руду |
|---|:---:|:---:|
| <Color id="dark_gray">Ошибочный</Color> | 0 | 1 |
| <Color id="green">Базовый</Color> | 6 | 4 |
| <Color id="blue">Продвинутый</Color> | 54 | 10 |
| <Color id="light_purple">Высший</Color> | 354 | 18 |
| <Color id="gold">Самоосознание</Color> | 1,254 | максимум |

Боссы следуют той же таблице, что и любой другой моб. Подсказка модели показывает, сколько еще убийств ей нужно.

<ItemImage id="minecraft:air" scale="0.25"/>

***

<Column alignItems="center" fullWidth={true}>
  ## <Color id="gold">Камера моделирования</Color>
</Column>

<Row>
  <ItemImage id="hostilenetworks:sim_chamber"/>
  ### <Color id="aqua">Только обучение</Color>
</Row>

В FTB Evolution 2 камера работает в режиме <Color id="aqua">Обучения</Color> и не может быть переключена. Каждый 15-секундный цикл использует одну <ItemLink id="hostilenetworks:prediction_matrix"/>, добавляет 1 значение данных к модели и ничего не производит. Энергия за тик — это стоимость моделирования модели плюс 20%.

Обучение идет медленно: Базовой модели нужно еще 1248 циклов, около 5.2 часов, чтобы стать Самоосознанной. Убивайте или добывайте с помощью Deep Learner, чтобы достичь этого быстрее. Камера останавливается, когда модель становится Самоосознанной.

> <Color id="yellow">Примечание</Color>: Фабрикатор добычи (Loot Fabricator) и Директива изготовления (Fabrication Directive) в этой сборке отключены. Центр данных сам выбирает свои выходы.
