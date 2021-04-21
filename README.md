# Spotibar
<a href="https://github.com/avenom/spotibar/releases/tag/v0.1"><img src="https://img.shields.io/github/v/release/avenom/spotibar?color=1&label=Release"></a> <a href="https://rainmeter.net"><img src="https://img.shields.io/badge/Rainmeter-4.4-brightgreen"></a> <img src="https://img.shields.io/badge/Windows-7%2B-brightgreen"> <img src="https://img.shields.io/github/downloads/avenom/spotibar/total?color=1&label=Downloads">

<img src="https://raw.githubusercontent.com/avenom/Spotibar/main/%40Resources/Images/Spotibar1.png">

Мини-плеер Spotify для панели задач в виде скина Rainmeter

## Возможности

* Отображение текущего трека и исполнителя
* Кнопки управления:  `Предыдущий трек` `Плей/Пауза` `Следующий трек`
* Сворачивается в иконку, когда Spotify не запущен

## Установка

1. Установите клиент [Spotify](https://spotify.com/ru-ru/download/windows)
2. Установите [Rainmeter 4.4](https://rainmeter.net)
3. Установите скин [Spotibar](https://github.com/avenom/spotibar/releases/tag/v0.1)

Дополнительно можете установить [7+ Taskbar Tweaker](https://rammichael.com/7-taskbar-tweaker), в котором можно настроить управление громкостью колесом мыши при наведении на панель задач.

## Настройка

Закройте в Rainmeter все стандартные скины illustro и выберите Spotibar > Spotibar.ini.
* [x] Всегда поверх окон
* [x] Перетаскивание
* [ ] Некликабельно

Можете в Rainmeter включить игровой режим, чтобы скин выключался в полноэкранном режиме.

## Плееры

Помимо Spotify вы можете выбрать другой плеер из этого [списка](https://docs.rainmeter.net/manual/measures/nowplaying), откройте в Rainmeter скин Spotibar > Spotibar.ini, нажмите `Изменить`, найдите и замените следующую строку:

```bash
PlayerName=Spotify
```

#### Полностью поддерживаемые плееры:
* AIMP: `PlayerName=AIMP`
* foobar2000: `PlayerName=CAD`
* iTunes: `PlayerName=iTunes`
* J. River Media Center and Media Jukebox: `PlayerName=CAD`
* MediaMonkey: `PlayerName=MediaMonkey`
* MusicBee: `PlayerName=CAD`
* Winamp: `PlayerName=Winamp`
* WMP: `PlayerName=WMP`

#### Частично поддерживаемые плееры:
* Last.fm Client, TTPlayer, OpenPandora, Zune: `PlayerName=WLM`
