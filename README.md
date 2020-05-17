# NexaX

[![GitHub release](https://img.shields.io/github/release/BlasterAlex/NexaX?color=green)](https://github.com/BlasterAlex/NexaX/releases/latest) [![GitHub](https://img.shields.io/github/license/BlasterAlex/NexaX?color=blue)](https://github.com/BlasterAlex/NexaX/blob/master/LICENSE.md)

Набор скинов для Rainmeter. За основу был взят дизайн виджетов [Nexa](https://7themes.su/news/nexa/2017-07-02-1282) с добавлением необходимого функционала.

# Что входит
- Часы

<p align="center">
  <img src="./@Resources/preview/clock.png"/>
</p>
  
- Основная информация о системе

    Для ноутбуков выводится информация о текущем состоянии батареи

<p align="center">
  <img src="./@Resources/preview/system.png"/>
</p>
 
- Информация об использовании процессора и оперативной памяти

<p align="center">
  <img src="./@Resources/preview/resources.gif" width="350"/>
</p>

- Информация о дисках, подключаемых USB-устройствах и корзине

<p align="center">
  <img src="./@Resources/preview/drive_1.gif" width="700"/>
</p>

<p align="center">
  <img src="./@Resources/preview/drive_2.gif" width="400"/>
</p>

- Музыкальный проигрыватель

    Для управление воспроизведением треков используется плагин NowPlaying, который поддерживает работу не со всеми плейерами (протестировано с [Winamp](https://www.winamp.com/) и [Aimp](https://www.aimp.ru/?do=download)). В остальных случаях, а также при прослушивании музыки через Интернет, управление воспроизведением будет недоступно и будет отображаться только спектрум и панель громкости. 

<p align="center">
  <img src="./@Resources/preview/music.gif" width="500"/>
</p>

- Сетевой монитор

<p align="center">
  <img src="./@Resources/preview/network.gif" width="380"/>
</p>

# Установка
## Автоматическая установка
1. Загрузите последнюю версию скина здесь: https://github.com/BlasterAlex/NexaX/releases

2. Установите скин, запустив **.rmskin** и пройдя через установщик.

3. После завершения установки **NexaX** появится в списке активных скинов.

## Ручная установка
1. Клонируйте этот репозиторий в **Documents\Rainmeter\Skins**.

2. Запустите Rainmeter и щелкните правой кнопкой мыши на кнопку **Обновить всё**.

3. После обновления в списке активных скинов появится папка **NexaX**.

# Настройка

Настройка параметров скинов выполняется через редактирование [файла переменных](https://github.com/BlasterAlex/NexaX/blob/master/%40Resources/Variables.inc).

Параметр ``compactMode`` включает / отключает (1/0) компактный режим отображения скинов. Компактный режим задает ширину всех скинов (кроме Clock), равную значению параметра ``windowWidthCompact``. По-умолчанию ширина данных скинов равняется значению параметра ``windowWidth``.

Также изменяются некоторые элементы внутри скинов. Сравнения полныхи и компактных версий представлены на рисунках ниже.

- Основная информация о системе

<p align="center">
  <figure>
  <img src="./@Resources/preview/comparison/system_full.png" title="Полная версия" style="margin-right: 20px;"/>
  </figure>
  <img src="./@Resources/preview/comparison/system_compact.png" title="Компактная версия"/>
</p>
 
- Информация об использовании процессора и оперативной памяти

<p align="center">
  <img src="./@Resources/preview/comparison/resources_full.png" title="Полная версия" style="margin-right: 20px;"/>
  <img src="./@Resources/preview/comparison/resources_compact.png" title="Компактная версия"/>
</p>

- Информация о дисках, подключаемых USB-устройствах и корзине

<p align="center">
  <img src="./@Resources/preview/comparison/drive_full.png" title="Полная версия" style="margin-right: 20px;"/>
  <img src="./@Resources/preview/comparison/drive_compact.png" title="Компактная версия"/>
</p>

- Музыкальный проигрыватель

<p align="center">
  <img src="./@Resources/preview/comparison/music_full.png" title="Полная версия" style="margin-right: 20px;"/>
  <img src="./@Resources/preview/comparison/music_compact.png" title="Компактная версия"/>
</p>

- Сетевой монитор

<p align="center">
  <img src="./@Resources/preview/comparison/network_full.png" title="Полная версия" style="margin-right: 20px;"/>
  <img src="./@Resources/preview/comparison/network_compact.png" title="Компактная версия"/>
</p>

В данном конфигурационном файле также заданы настройка цветов и шрифтов отображаемого на скинах текста и элементов, размеры отступов, настройки дисков и музыкального скина.

# Благодарность
- [Nexa](https://7themes.su/news/nexa/2017-07-02-1282) — основной дизайн окон
- [Gotham](https://7themes.su/news/gotham_for_rainmetter/2016-04-21-1174) — скин часов
- [Bolo](https://7themes.su/news/bolo_monitoring_sistemy/2012-09-09-415) — элементы интерфейса
- [Kantas Akra](https://visualskins.com/skin/kantas-akra) — музыкальный проигрыватель
- [USB DISK EJECTOR](https://quickandeasysoftware.net/software/usb-disk-ejector) — аддон для извлечения usb
