---
navigation:
  title: Ускоритель частиц
  position: 3
  icon: "oritech:particle_accelerator"
item_ids:
  - oritech:particle_accelerator
  - oritech:accelerator_ring
  - oritech:accelerator_motor
---
# <Color id="aqua">Ускоритель частиц</Color>

<Column alignItems="center" fullWidth={true}>
  # <Color id="aqua">Ускоритель частиц</Color>

  <GameScene zoom="2.5" interactive={true}>
    <ImportStructure src="oritech:assets/basic_accelerator.nbt"/>
    <IsometricCamera yaw="225" pitch="30"/>
    <DiamondAnnotation pos="0.5 0.5 1.5" color="#ff6d6d">
    Для каждой установки требуется 2 Ускорителя частиц. Используются для вставки предметов для ускорения.
    </DiamondAnnotation>
    <DiamondAnnotation pos="5.5 0.5 2.5" color="#ff6d6d">
    Линейный мотор помещается внутри кольца ускорителя. При подаче питания он ускорит частицу.
    </DiamondAnnotation>
    <DiamondAnnotation pos="2.5 0.5 4.5" color="#ff6d6d">
    Направляющие кольца помогают направить частицу по кругу. После размещения их можно нажать правой кнопкой мыши, чтобы изменить угол входа.
    </DiamondAnnotation>
  </GameScene>
  #### *Базовая установка ускорителя частиц*
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

***

<Column alignItems="center" fullWidth={true}>
  ## <Color id="gold">Компоненты</Color>
</Column>

<ItemImage id="minecraft:air" scale="0.25"/>

<Row>
  <ItemImage id="oritech:particle_accelerator"/>
  ### <Color id="aqua">Ускоритель частиц</Color>
</Row>

<Color id="aqua">Ускоритель частиц</Color> — это основной механизм в любой установке ускорителя. Сюда предметы будут вставляться в кольцо ускорения частиц. Базовая установка требует как минимум 2 <Color id="aqua">Ускорителя частиц</Color>, оба прикрепленных к <Color id="green">Направляющему кольцу ускорителя частиц</Color>.

<ItemImage id="minecraft:air" scale="0.25"/>

<Row>
  <ItemImage id="oritech:accelerator_ring"/>
  ### <Color id="aqua">Направляющее кольцо ускорителя</Color>
</Row>

<Color id="green">Направляющие кольца ускорителя частиц</Color> используются для направления частицы по кругу. После размещения их можно нажать правой кнопкой мыши, чтобы изменить угол входа. Вам захочется использовать их, чтобы направлять частицу по кругу, но в зависимости от вашей настройки может потребоваться больше колец.

<ItemImage id="minecraft:air" scale="0.25"/>

<Row>
  <ItemImage id="oritech:accelerator_motor"/>
  ### <Color id="aqua">Линейный мотор</Color>
</Row>

<Color id="green">Линейный мотор ускорителя частиц</Color> используется для ускорения частиц по кольцу. Они должны быть запитаны. Хотя требуется только 1, наличие большего количества ускорит частицу быстрее.
