# SuperBar

SuperBar is a fork of RetroBar which is based on the [ManagedShell](https://github.com/cairoshell/ManagedShell) library for great compatibility and performance.

## Requirements
- Windows 7 SP1, Windows 8.1, Windows 10, or Windows 11
- [.NET 6.0.2 or later desktop runtime](https://dotnet.microsoft.com/download/dotnet/6.0/runtime) (select the appropriate download button under "Run desktop apps")

## Features
- Replaces default Windows taskbar with classic layout
- Native notification area with balloon notification support
- Native task list with UWP app support and drag reordering
- Quick launch toolbar
- Start button opens modern start menu
- Ability to show or hide the clock
- Display taskbar on any side of the screen (even on Windows 11)
- Option to display the taskbar, notification area, and clock on multiple monitors
- Ability to show Vista-style window thumbnails
- Customizable XP-style collapsible notification area
- Custom theme support

## Included themes
- System (Classic and XP)
- Watercolor
- Windows 95-98
- Windows Me
- Windows 2000
- Windows XP:
  - Classic
  - Blue
  - Olive Green
  - Silver
  - Royale
  - Royale Noir
  - Embedded Style
  - Zune Style
- Windows Longhorn Aero
- Windows Vista:
  - Aero
  - Basic
  - Classic

## Supported languages
- Arabic (العربية)
- Bulgarian (български)
- Catalan (català)
- Chinese (Simplified) (中文(简体))
- Chinese (Traditional) (中文(繁體))
- Czech (čeština)
- Dutch (Nederlands)
- English
- English (United Kingdom)
- French (français)
- German (Deutsch)
- Greek (ελληνικά)
- Hebrew (עברית)
- Hungarian (magyar)
- Indonesian
- Italian (italiano)
- Japanese (日本語)
- Korean (한국어)
- Lithuanian (lietuvių)
- Persian (فارسی)
- Polish (polski)
- Portuguese (português)
- Romanian (Română)
- Russian (русский)
- Spanish (español)
- Swedish (svenska)
- Turkish (Türkçe)
- Vietnamese (Tiếng Việt)

## Custom languages and themes
SuperBar supports custom languages and themes. To use custom languages or themes, create a `Languages` or a `Themes` directory and place valid `.xaml` language or theme files there.

Valid locations to create a `Languages` or a `Themes` directory:
- In the same directory as `SuperBar.exe`
- In `%localappdata%\SuperBar`

Themes use the XAML `ResourceDictionary` format. [View the included example themes](https://github.com/brunobits/SuperBar/tree/master/RetroBar/Themes) to get started.
