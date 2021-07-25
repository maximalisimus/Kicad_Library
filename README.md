# Kicad_Library

****************************

Kicad and EasyEda Library and 3D Models

Kicad и EasyEda библиотеки, а также 3D Модели

## Оглавление

1. [Библиотеки](#Библиотеки)
2. [Настройки](#Настройки)
3. [About](#About)

[:arrow_up:Библиотеки](#Библиотеки)

Данные библиотеки специально сделаны для **Kicad**.

**3D Модели сохранены в нескольких форматах:**
* .stl
* .wrl
* .stp and .step

На сайте **EasyEda** преимущественно используются модели в формате **wrl**.

В **Kicad** можно использовать 3D модели 2 форматов: **stp** и **wrl**.

[:arrow_up:Настройки](#Настройки)

После запуска программы **Kicad**, откройте **меню** -> **Настройки** -> **Настройки путей** и добавте нижеуказанную строку.

Например, так:
```
Имя                Путь
KICAD_LIBRARY     /home/mikl/git_ssh/Kicad_Library/Shadow-Lib/
```

А далее, в **менеджере библиотек компонентов** и **менеджере библиотек посад.мест** добавьте в список глобальных библиотек для каждой библиотеки следующие строки.

Таблица **менеджера библиотек компонентов**:
```
Использовать       Уникальное имя      Путь библиотеки                                       Тип плагина             Параметры        Описание
✓                  S-Trans-Coils       ${KICAD_LIBRARY}/Shadow-Symbols/S-Trans-Coils.lib     Legacy
✓                  S-Semiconductors    ${KICAD_LIBRARY}/Shadow-Symbols/S-Semiconductors.lib  Legacy
✓                  S-Resistance        ${KICAD_LIBRARY}/Shadow-Symbols/S-Resistance.lib      Legacy
✓                  S-Relay             ${KICAD_LIBRARY}/Shadow-Symbols/S-Relay.lib           Legacy
✓                  S-Modules           ${KICAD_LIBRARY}/Shadow-Symbols/S-Modules.lib         Legacy
✓                  S-Displays          ${KICAD_LIBRARY}/Shadow-Symbols/S-Displays.lib        Legacy
✓                  S-Connectors        ${KICAD_LIBRARY}/Shadow-Symbols/S-Connectors.lib      Legacy
✓                  S-Chips             ${KICAD_LIBRARY}/Shadow-Symbols/S-Chips.lib           Legacy
✓                  S-Capacitors        ${KICAD_LIBRARY}/Shadow-Symbols/S-Capacitors.lib      Legacy
```

Таблица **менеджера библиотек посад.мест**:
```
Использовать       Уникальное имя      Путь библиотеки                                             Тип плагина             Параметры        Описание
✓                  S-Trans-Coils       ${KICAD_LIBRARY}/Shadow-Footprints/S-Trans-Coils.pretty     KiCad
✓                  S-Semiconductors    ${KICAD_LIBRARY}/Shadow-Footprints/S-Semiconductors.pretty  KiCad
✓                  S-Resistance        ${KICAD_LIBRARY}/Shadow-Footprints/S-Resistance.pretty      KiCad
✓                  S-Relay             ${KICAD_LIBRARY}/Shadow-Footprints/S-Relay.pretty           KiCad
✓                  S-Modules           ${KICAD_LIBRARY}/Shadow-Footprints/S-Modules.pretty         KiCad
✓                  S-Displays          ${KICAD_LIBRARY}/Shadow-Footprints/S-Displays.pretty        KiCad
✓                  S-Connectors        ${KICAD_LIBRARY}/Shadow-Footprints/S-Connectors.pretty      KiCad
✓                  S-Chips             ${KICAD_LIBRARY}/Shadow-Footprints/S-Chips.pretty           KiCad
✓                  S-Capacitors        ${KICAD_LIBRARY}/Shadow-Footprints/S-Capacitors.pretty      KiCad
```

[:arrow_up:About](#About)

Автор проектов: [maximalisimus](https://github.com/maximalisimus).

