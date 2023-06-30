# BlueProtocol-Translate
Client-side patch to translate the game interface into different languages.
You can participate in the translation of the game into other languages, English, German, French, Spanish and others. Visit our discord: https://discord.gg/nVfDBy97aK

## Disclaimer.
This is a third-party fan project that has nothing to do with the creators of the game.
This patch requires modification of the game client.
Using this patch can lead to a ban of the account, but at the moment there are no such cases, bans only for IP 

## Progress client
* `Ru-ru` - Около `26%` ручного русского перевода, и `74%` GPT+deepl русского механического перевода
* `En-en` - About `20%` lines of manual English translation, and `80%` English mechanical DeepL translation
* `En-pt` - About `100%` lines of manual Portuguese translation

## Progress server
* `Ru-ru` - Около `7%` ручного русского перевода, и `93%` GPT+deepl+google русского механического перевода
* `En-en` - About `14%` lines of manual English translation, and `86%` English mechanical Google translation
* `En-pt` - About `7%` lines of manual Portuguese translation, `14%` lines of manual English translation, `79%` English mechanical Google translation

## Installation and usage
1. Go to latest release [Releases page]([https://github.com/digitalstars/BlueProtocol-Translate/releases]) and download the required .rar archive with the translation from Assets and unpack.
2. Copy `dinput8.dll` to `C:\BandaiNamcoLauncherGames\BLUEPROTOCOL\BLUEPROTOCOL\Binaries\Win64\`.
3. Copy the `~mods` folder to `C:\BandaiNamcoLauncherGames\BLUEPROTOCOL\BLUEPROTOCOL\Content\Paks`.
4. Move the `BP-translate 1.1` folder to any location convenient for you
5. Run `BP-translate.exe` (It is necessary to restart every time you enter the game. The window will automatically close when the game starts)
6. Launch the game as usual with the BNO launcher.
7. A window saying "SkyProc Launcher - Done!" will appear, press OK. (It may not appear the first time.)
8. the game will start with the translation patch

* These instructions assume that you have installed the game in the standard path `C:\BandaiNamcoLauncherGames\BLUEPROTOCOL`. If you installed the game in your own path, adjust the folder paths above as necessary.

## If the server translation doesn't work:
1. So far it does not work if you use a proxy for Blue Protocol. VPN is fine
2. The .exe uses port 443, make sure it is not busy (usually with web developers)
3. May not work when antivirus software is enabled
4. Make sure you have the hosts file at the path `c:\windows\system32\drivers\etc\hosts`

## Uninstall
The patch can be removed at any time by deleting the files copied in the `Installation` section:
1. Delete `dinput8.dll` from `C:\BandaiNamcoLauncherGames\BLUEPROTOCOL\BLUEPROTOCOL\Binaries\Win64\dinput8.dll`.
2. Delete the `~mods` folder from `C:\BandaiNamcoLauncherGames\BLUEPROTOCOL\BLUEPROTOCOL\Content\Paks\`.

## Thanks
- `ArtFect` - https://github.com/ArtFect/BP-translate - server-side patch and  fix .dll file

- `Zakum` worked on this to create the initial glossary of terms used for the translations. ([bapharia.com](https://bapharia.com/))

- `SkyProc` - The first iteration of the dll patch. No longer supports