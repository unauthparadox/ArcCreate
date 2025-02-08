# Bardzo ważne, proszę przeczytać. | Important, please read.
PL:
Prace nad ArcCreate są obecnie wstrzymane do czasu znalezienia nowego programisty, który zajmie się projektem. **Oznacza to, że obecne polskie tłumaczenie (które również zostało wykonane przeze mnie) w repozytorium Arcthesia (które można znaleźć [tutaj](https://github.com/Arcthesia/ArcCreate)) jest obecnie starszą, niedokończoną wersją, która jest *bardzo, BARDZO zła*.**

Nie wiem jak budować aplikacje w Unity, więc będziesz musiał sam dodać polskie tłumaczenie do aktualnego oficjalnego wydania ArcCreate. Oto jak to zrobić dla edytora:
1. W tym repozytorium przejdź do [pl.yml](https://github.com/unauthparadox/ArcCreate/blob/master/Assets/StreamingAssets/Locales/pl.yml) i pobierz go.
2. Pobierz [najnowszą oficjalną wersję edytora ArcCreate (czyli wersja dla Windows, macOS lub Linux)](https://github.com/Arcthesia/ArcCreate/releases) i wyodrębnij ją.
3. W wyodrębnionym folderze przejdź do `ArcCreate_Data/StreamingAssets/Locales`.
4. Wklej plik pl.yml pobrany z tego repozytorium do folderu `Locales` w ArcCreate.
5. Otwórz ArcCreate i zmień język na polski.
6. Uruchom ponownie ArcCreate.
7. Gotowe.

EN:
ArcCreate development is currently stopped until a new developer is found to maintain the project. **This means that the current Polish translation (which was also done by me) in Arcthesia's parent repository (which you can find [here](https://github.com/Arcthesia/ArcCreate)) is currently an older, unfinished version, which is *very, VERY bad*.**

I don't know how to build applications in Unity, so you'll need to add the Polish translation to the current official ArcCreate release yourself. Here's how you can do it in the editor:
1. In this repository, go to [pl.yml](https://github.com/unauthparadox/ArcCreate/blob/master/Assets/StreamingAssets/Locales/pl.yml) and download it.
2. Download [the latest official ArcCreate release (this means versions for Windows, macOS or Linux)](https://github.com/Arcthesia/ArcCreate/releases) and extract it.
3. In the extracted folder, go to `ArcCreate_Data/StreamingAssets/Locales`.
4. Paste the pl.yml file you've downloaded from this repository to the `Locales` folder in ArcCreate.
5. Open ArcCreate and change your language to Polish.
6. Restart ArcCreate.
7. Done.

## Poniżej znajduje się oryginalna zawartość README z repozytorium Arcthesia. | The following is the original contents of the README from the Arcthesia repository.

# ArcCreate

![Logo](Assets/Textures/Logos/LogoFull.png?raw=true "Title")

Fast and powerful .aff editor made with Unity.

### Support us:

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Q5Q1JE1B1)

### Join our discord server:

[![Join the Discord](https://discord.com/api/guilds/1083452023250354206/widget.png?style=banner4)](https://discord.com/invite/t27ptGsrGH)

# Getting started

### Installation

ArcCreate is available on Windows, MacOS, Linux, Android and iOS.

- Windows, MacOS, Linux (Editor):

  [Download through GitHub releases](https://github.com/Arcthesia/ArcCreate/releases/)

- Android & iOS (Player):

| [<img src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" height=75px>](https://play.google.com/store/apps/details?id=com.Arcthesia.ArcCreate) | [<img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" height=50px>](https://apps.apple.com/us/app/arccreate/id6445904090) |
| - | - |

### Building

This project was made with Unity 2021.3.37f1. You can download the exact version from the [official Download Archive here](https://unity.com/releases/editor/archive).

# Project status

### Gameplay
- [x] Gameplay rendering
- [x] Gameplay judgement
- [x] Pause menu
- [x] Compiled scenecontrol support
- [x] Level selection menu
- [x] Result screen
- [x] Import level from package file
- [x] Settings menu
- [ ] Support for controller input
- [ ] Custom gauge and partner

### Editor (Desktop only)
- [x] Project metadata management
- [x] Project skin settings
- [x] Note editing
- [x] Timing, camera editing
- [x] Custom hotkeys configuration
- [x] FFmpeg rendering support
- [x] Lua macro support
- [x] Lua scenecontrol editing & compiling
- [x] LAN communication between desktop and mobile

# Contributing

See:
- [CONTRIBUTING](CONTRIBUTING.md) for code contribution
- [TRANSLATING](TRANSLATING.md) for helping with translating the application.

# License

This project was licensed under GPL-3.0 license (see [LICENSE](LICENSE)).

# Credits

- `Assets/Plugins/ColorPicker`: https://github.com/mmaletin/UnityColorPicker
- `Assets/Plugins/DOTween`: http://dotween.demigiant.com
- `Assets/Plugins/DynamicPanels`: https://github.com/yasirkula/UnityDynamicPanels
- `Assets/Plugins/Graphy`: https://github.com/Tayx94/graphy/
- `Assets/Plugins/MaterialIcons`: https://fonts.google.com/icons for the icons themselves and https://github.com/convalise/unity-material-icons/ for packaging them for Unity.
- `Assets/Plugins/NativeFilePicker`: https://github.com/yasirkula/UnityNativeFilePicker
- `Assets/Plugins/StandaloneFileBrowser`: https://github.com/gkngkc/UnityStandaloneFileBrowser
- `Assets/Plugins/UIGradient`: https://github.com/azixMcAze/Unity-UIGradient
- `Assets/Plugins/YamlDotNet`: https://github.com/aaubry/YamlDotNet
- Other files under `Assets/Plugins/` are downloaded from NuGet
- A large portion of files under `Assets/Textures/Gameplay` are taken from, or derived from https://github.com/yojohanshinwataikei/arcade-plus
- Files under `Assets/AudioClips` are from https://github.com/yojohanshinwataikei/Arcade-plus.
- Files under `Assets/Fonts/FontFiles` are free font files taken from https://fonts.google.com
