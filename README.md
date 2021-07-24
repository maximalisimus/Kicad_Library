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
KICAD_LIBRARY     /home/mikl/git_ssh/Kicad_Library/
```

А далее, в **менеджере библиотек компонентов** и **менеджере библиотек посад.мест** добавьте в список глобальных библиотек для каждой библиотеки следующие строки.

В качестве примера строка для **менеджера библиотек компонентов**.
```
Использовать       Уникальное имя      Путь библиотеки                                       Тип плагина             Параметры        Описание
✓                  S-Trans-Coils       ${KICAD_LIBRARY}/Shadow-Symbols/S-Trans-Coils.lib     Legacy
```

[:arrow_up:About](#About)

Автор проектов: [maximalisimus](https://github.com/maximalisimus).

