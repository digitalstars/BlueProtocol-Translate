# BlueProtocol-Translate
Client-side patch to translate the game interface into different languages.
You can participate in the translation of the game into other languages, English, German, French, Spanish and others. Visit our discord: https://discord.gg/nVfDBy97aK

## Server-side patch
To translate the server part of the game (quest, items, mobs, boards, etc...) use this patch in conjunction with ours. In the future this patch will be included in our archives
https://github.com/ArtFect/BP-translate

## Disclaimer.
This is a third-party fan project that has nothing to do with the creators of the game.
This patch requires modification of the game client.
Using this patch can lead to a ban of the account, but at the moment there are no such cases, bans only for IP 

## Progress
* `Ru-ru` - Около `13%` ручного русского перевода, и `87%` русского механического DeepL перевода
* `En-ru` - Около `13%` ручного русского перевода, и `87%` английского механического DeepL перевода
* `En-en` - About `10%` lines of manual English translation, and `90%` English mechanical DeepL translation
* `En-pt` - About `15%` lines of manual Portuguese translation, and `85%` English mechanical DeepL translation

## Installation client-side translate
1. Download the latest release [Releases page]([https://github.com/digitalstars/BlueProtocol-Translate/releases]) and unpack the archive with the desired localization
2. Copy `dinput8.dll` to `C:\BandaiNamcoLauncherGames\BLUEPROTOCOL\BLUEPROTOCOL\Binaries\Win64\`.
3. Copy the `~mods` folder to `C:\BandaiNamcoLauncherGames\BLUEPRTOCOL\BLUEPROTOCOL\Content\Paks`.

* These instructions assume that you have installed the game in the standard path `C:\BandaiNamcoLauncherGames\BLUEPROTOCOL`. If you installed the game in your own path, adjust the folder paths above as necessary.

## Usage.
1. Launch the game as usual with the BNO launcher.
2. A window saying "SkyProc Launcher - Done!" will appear, press OK. (It may not appear the first time.)
3. the game will start with the translation patch

## Uninstall
The patch can be removed at any time by deleting the files copied in the `Installation` section:
1. Delete `dinput8.dll` from `C:\BandaiNamcoLauncherGames\BLUEPROTOCOL\BLUEPROTOCOL\Binaries\Win64\dinput8.dll`.
2. Delete the `~mods` folder from `C:\BandaiNamcoLauncherGames\BLUEPROTOCOL\BLUEPROTOCOL\Content\Paks\`.