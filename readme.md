# WinGet Configuration Files
This repo provides Win-Get configuration files to easily configure your PC. To find out more about Win-Get Configuration view the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/package-manager/configuration/) article.

## Usage Instructions
1. Clone the repo or download a specific file
2. Open PowerShell or CMD in administrator mode
3. Run the following command
   `winget configure -f <file>`

## Modules
### Base
Changes the following settings:
- Sets taskbar alignment to left
- Do not display seconds in system clock
- Show file extensions
- Show hidden files
- Enables dark mode (You still need to choose an accent in Settings > Personalize)

**Installs:**
- [Discord](https://winget.run/pkg/Discord/Discord)
- [Firefox](https://winget.run/pkg/Mozilla/Firefox)
- [Google Chrome](https://winget.run/pkg/Google/Chrome)
- [Microsoft Office 365](https://winget.run/pkg/Microsoft/Office)
- [Notepad++](https://winget.run/pkg/Notepad++/Notepad++)
- [ShareX](https://winget.run/pkg/ShareX/ShareX)
- [Steam](https://winget.run/pkg/Valve/Steam)
- [Yubikey Manager](https://winget.run/pkg/Yubico/YubikeyManager)

### Eve Online
Installs the following software
- [Evemon](https://winget.run/pkg/EVEMonDevelopmentTeam)
- [Eve Online](https://winstall.app/apps/CCPGames.EVEOnline)
- [Mumble](https://winget.run/pkg/Mumble/Mumble.Client)
- [Pidgin](https://winget.run/pkg/Pidgin/Pidgin)
- [Pyfa](https://winget.run/pkg/pyfa/pyfa)
- [ShareX](https://winget.run/pkg/ShareX/ShareX)
- [Stream Deck](https://www.elgato.com/ww/en/s/explore-stream-deck)

### Development (WIP)
Installs the following packages
- [Visual Studio](https://winget.run/pkg/Microsoft/VisualStudio.2022.Community.Preview) + Desktop Development & Website Development
- [Visual Studio Code](https://code.visualstudio.com/) + Plugins
- [GIT](https://winget.run/pkg/Git/Git) + [Desktop](https://winget.run/pkg/GitHub/GitHubDesktop)
- [Docker Desktop](https://winget.run/pkg/Docker/DockerDesktop)
- [Postman](https://winget.run/pkg/Postman/Postman)

> [!NOTE]
> The WinGetPackage DSC doesn't provide the ability to pass arguments to the installer. This is a known issue see: https://github.com/microsoft/winget-cli/issues/3401


**Todo:**

Setup a script that enables services using Docker Compose:
- Postgres

