[English](#english) | [Русский](#russian)

# Spotibar
<a href="https://github.com/avenom/spotibar/releases/tag/v0.3"><img src="https://img.shields.io/github/v/release/avenom/spotibar?color=1&label=Release"></a> <a href="https://rainmeter.net"><img src="https://img.shields.io/badge/Rainmeter-4.4-brightgreen"></a> <img src="https://img.shields.io/badge/Windows-7%2B-brightgreen"> <img src="https://img.shields.io/github/downloads/avenom/spotibar/total?color=1&label=Downloads">

<img src="https://raw.githubusercontent.com/avenom/Spotibar/main/Spotibar/%40Resources/Images/Spotibar.gif">

По всем вопросам пишите в [телеграм](https://t.me/avenom).

## Spotibar Mini <a name="english"></a>

* Launch Spotify on icon, minimizes back to icon when Spotify is not running
* Clicking on the current track and artist opens the Spotify window*
* Control buttons: `Previous track` `Play/Pause` `Next track`
* Volume control by mouse wheel when hovering over the player, right click turns off the sound

## Spotibar Max

* Launch Spotify on icon, minimizes back to icon when Spotify is not running
* Clicking on the current track and artist opens the Spotify window*
* Control buttons: `Previous track` `Play/Pause` `Next track`
* Control buttons when hovering over the cover: `Like` `Repeat track` `Shuffle tracks`
* Volume control by mouse wheel when hovering over the player, right click turns off the sound
* Track progress and background version adapt to cover color

<img src="https://raw.githubusercontent.com/avenom/Spotibar/main/Spotibar/%40Resources/Images/SpotibarBG.png">

###### * Minimize the Spotify window rather than close it to work properly.

## Installation

1. Install [Spotify](https://www.spotify.com/download/windows)
2. Install [Rainmeter 4.4](https://rainmeter.net)
3. Install skin [Spotibar](https://github.com/avenom/spotibar/releases/tag/v0.3), restart Rainmeter and activate the skin

#### Spotibar Max requires installation Spicetify to work:

Open the search bar in Windows 10, type PowerShell, and run the Windows PoweShell. In the terminal window, run the following commands in order:

``` Invoke-WebRequest -UseBasicParsing "https://raw.githubusercontent.com/khanhas/spicetify-cli/master/install.ps1" | Invoke-Expression ```

``` spicetify ```

``` spicetify config extensions webnowplaying.js ```

``` spicetify config inject_css 0 replace_colors 0 ```

``` spicetify backup apply ```

If Spotify client is updated, then you must uninstall Spicetify with command `spicetify restore` and reinstall Spicetify.

## Settings

Close all standart Rainmeter skins illustro and choose Spotibar > Spotibar Mini.ini.

* [x] Stay topmost
* [x] Draggable
* [ ] Click through

You can turn on game mode in Rainmeter to turn off the skin in full screen mode.

## Spotibar Mini <a name="russian"></a>

* Запуск Spotify по иконке, сворачивается обратно в иконку, когда Spotify не запущен
* Клик по текущему треку и исполнителю открывает окно Spotify*
* Кнопки управления:  `Предыдущий трек` `Плей/Пауза` `Следующий трек`
* Регулировка громкости колесом мыши при наведении на плеер, правый клик выключает звук

## Spotibar Max

* Запуск Spotify по иконке, сворачивается обратно в иконку, когда Spotify не запущен
* Клик по текущему треку и исполнителю открывает окно Spotify*
* Кнопки управления:  `Предыдущий трек` `Плей/Пауза` `Следующий трек`
* Кнопки управления при наведении на обложку:  `Лайк` `Повторять трек` `Перемешать треки`
* Регулировка громкости колесом мыши при наведении на плеер, правый клик выключает звук
* Прогресс трека и версия с фоном адаптируются под цвет обложки

<img src="https://raw.githubusercontent.com/avenom/Spotibar/main/Spotibar/%40Resources/Images/SpotibarBG.png">

###### * Для правильной работы сворачивайте окно Spotify, а не закрывайте.

## Установка

1. Установите [Spotify](https://spotify.com/ru-ru/download/windows)
2. Установите [Rainmeter 4.4](https://rainmeter.net)
3. Установите скин [Spotibar](https://github.com/avenom/spotibar/releases/tag/v0.3), перезапустите Rainmeter и активируйте скин

#### Для работы Spotibar Max требуется установка Spicetify:

В поиске Windows 10 наберите PowerShell и запустите Windows PoweShell. В открывшемся окне терминала выполните по порядку следующие команды:

``` Invoke-WebRequest -UseBasicParsing "https://raw.githubusercontent.com/khanhas/spicetify-cli/master/install.ps1" | Invoke-Expression ```

``` spicetify ```

``` spicetify config extensions webnowplaying.js ```

``` spicetify config inject_css 0 replace_colors 0 ```

``` spicetify backup apply ```

Если клиент Spotify обновится, то вы должны удалить Spicetify командой `spicetify restore` и установить Spicetify заново.

## Настройка

Закройте в Rainmeter все стандартные скины illustro и выберите Spotibar > Spotibar Mini.ini.
* [x] Всегда поверх окон
* [x] Перетаскивание
* [ ] Некликабельно

Можете в Rainmeter включить игровой режим, чтобы скин выключался в полноэкранном режиме.
