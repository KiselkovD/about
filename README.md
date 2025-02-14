если вы с https://hh.ru то перейдите к разделу [Проекты](#Проекты)

## Коротко:

- Мне 22 года, и я учусь в магистратуре по направлению программная инженерия.
- В основном программирую на С/С++, также интересуюсь С#, Python и JavaScript.
- Мне нравится обучатся новым инструментам, например я делал модели для 3д принтера в blender и базу знаний в obsidian.

## Технологический Стек:
- С/С++:
  - QT
  - SDL
  - winapi
  - openGL;
- С#: 
  - WPF;
- Python 
  - pandas;
- JS: 
  - HTML+CSS;
- а также: 
  - Git, GitHub
  - Excel
  - MySQL ...

## Личные Качества:
- Ответственность: в срок выполнял задачи различной сложности.
- Целеустремленность: стремлюсь к развитию в области backend разработки, изучаю новые технологии.
- Стрессоустойчивость: сохраняю эффективность и позитив в стрессовых ситуациях.

## Проекты:

#### Grider
**JS css html**, программа для разрезания изображений и пресетов на части или соответственно кадры. разработана на **docker nginx**.
- состояние: $${\color{green}\textsf{оформлен}}$$, $${\color{green}\textsf{реализован}}$$
- репозиторий: [github](https://github.com/KiselkovD/Grider)
- интерактивная версия: [github.io](https://kiselkovd.github.io/Grider/)

#### Gradient editor:
**С++ QT**, дипломная работа: разработка библиотеки для настраиваемого, контролируемого выделения и редактирования частей растровых изображений. Была создана библиотека, предоставляющая инструменты редактирования с множеством настроек. Программа позволяет с помощью шейдеров **OpenGL** выделить область изображения используя сразу несколько настроек, например комбинируя `перекрытие зазоров` и `относительное выделение` можно выделять буквы текстура которых совпадает с текстурой фона, получая минимум артефактов.
- состояние: $${\color{purple}\textsf{не оформлен}}$$, $${\color{green}\textsf{реализован}}$$
<!-- - репозиторий: []() -->
- интерактивная версия (шейдеры реализующие часть функций): [shadertoy](https://www.shadertoy.com/playlist/DXXSRX)
- скриншоты: <p><a> <img src="https://github.com/KiselkovD/about/blob/main/res/vkr_ui_0.png" alt="example how it work" height="200"/> </a><a> <img src="https://github.com/KiselkovD/about/blob/main/res/vkr_ui_1.png" alt="example how it work" height="200"/> </a><a> <img src="https://github.com/KiselkovD/about/blob/main/res/vkr_ui_2.png" alt="example how it work" height="200"/> </a></p>

#### Game of Life 2:
**C# WPF** , сделал игру жизнь используя **ООП**, наследованием реализовал различные виды клеток. Игра выполнена в темной теме, обладает редактором поля, и загрузкой/сохранением 
- состояние: $${\color{purple}\textsf{не оформлен}}$$, $${\color{blue}\textsf{базовая реализация}}$$
- репозиторий (скриншоты и код): [github](https://github.com/KiselkovD/life_game/tree/main)

#### Event master:
**С++ winapi**, программа начинавшаяся с простого уведомления каждое утро проверяющие и показывающие события, выросшая до календаря с поиском по датам и функции печати событий преобразованных в **word** документ.
- состояние: $${\color{purple}\textsf{не оформлен}}$$, $${\color{blue}\textsf{базовая реализация}}$$
<!-- - репозиторий: []() -->
- скриншоты: <p><a> <img src="https://github.com/KiselkovD/about/blob/main/res/ivent.png" alt="example how it work" height="200"/> </a><a> <img src="https://github.com/KiselkovD/about/blob/main/res/ivent_more.png" alt="example how it work" height="200"/> </a></p><p><a> <img src="https://github.com/KiselkovD/about/blob/main/res/date_choose.png" alt="example how it work" height="200"/> </a><a> <img src="https://github.com/KiselkovD/about/blob/main/res/date_choose_2.png" alt="example how it work" height="200"/> </a></p>

#### Usb hid:
**С++ Keil** `(stm32f103c8t6)`, создана программа позволяющая подключить плату по **USB hid** и управлять ей с компьютера. Были выбраны три порта которые можно было включать, отключать (3.3В между портом и землей), также можно было проверять замкнуты ли они с портом +3.3В.
- состояние: $${\color{purple}\textsf{не оформлен}}$$, $${\color{blue}\textsf{базовая реализация}}$$
<!-- - репозиторий: []() -->

## Мини Проекты:

#### Train sql:
**SQL Excel**, шуточный проект. Весь пользовательский интерфейс реализован в **Excel**. С помощью **VBA макросов**, он может подключаться к серверу **Docker MySQL** и обмениваться информацией.
- состояние: $${\color{green}\textsf{оформлен}}$$, $${\color{blue}\textsf{базовая реализация}}$$
- репозиторий (скриншоты и код): [github](https://github.com/KiselkovD/train_sql)

#### Some ci test:
**С++**, пример использования **github action**.
- состояние: $${\color{green}\textsf{оформлен}}$$, $${\color{green}\textsf{реализован}}$$
- репозиторий: [github](https://github.com/KiselkovD/some_ci_test)

#### Func graph drawer:
**С++ SDL2**, отображает функции с заданной точностью на оси координат с помощью **sdl2**, установленного через **vcpkg**. Скомпилировано **cmake**.
- состояние: $${\color{green}\textsf{оформлен}}$$, $${\color{green}\textsf{реализован}}$$
- репозиторий (скриншоты и код): [github](https://github.com/KiselkovD/func_graph_drawer)

#### Ahk tools:
**Ahk**, небольшой набор инструментов для автоматизации некоторых задач.
- состояние: $${\color{green}\textsf{оформлен}}$$, $${\color{green}\textsf{реализован}}$$
- репозиторий: [github](https://github.com/KiselkovD/ahk_tools)
