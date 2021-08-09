# Dotfiles for Microsoft Windows 11

Repeatable, reboot resilient Dotfiles script to setup a development environment in Microsoft Windows 11.

## Usage

Open a PowerShell console as administrator and run:

```Powershell
$GitHubRepositoryAuthor = "JMOrbegoso"; `
$GitHubRepositoryName = "Dotfiles-for-Windows-11"; `
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass; `
Invoke-Expression (Invoke-RestMethod -Uri "https://raw.githubusercontent.com/${GitHubRepositoryAuthor}/${GitHubRepositoryName}/main/Download.ps1");
```

## What does

- Install Chocolatey.
- Configure Chocolatey to remembered arguments for upgrades.
- Install Hack Nerd Font.
- Install Git;
- Configure Git.
- Install Vim;
- Install Vim-Plug.
- Install Vim plugins.
- Install Visual Studio Code.
- Configure Visual Studio Code.
- Install Visual Studio Code extensions.
- Install Oh My Posh for PowerShell.
- Configure Oh My Posh theme.
- Configure Windows Terminal.
- Install TeraCopy.
- Install Notepad++.
- Configure Notepad++.
- Set Notepad++ as the default program to open .txt, .xml, .ini, .bat, .cmd and .ps1 files.
- Install .NET SDK.
- Install Visual Studio 2019.
- Enable Windows Subsystem for Linux.
- Install Ubuntu 20.04 LTS in WSL.
  - Install curl.
  - Install Neofetch.
  - Configure Git in Ubuntu.
  - Install Visual Studio Code extensions in Ubuntu.
  - Install Volta in Ubuntu.
    - Install Node.js LTS using Volta in Ubuntu.
    - Install NPM using Volta in Ubuntu.
    - Install Yarn using Volta in Ubuntu.
    - Install TypeScript using Volta in Ubuntu.
    - Install Yarn-Upgrade-All using Volta in Ubuntu.
    - Install Angular CLI using Volta in Ubuntu.
    - Install NestJS CLI using Volta in Ubuntu.
  - Install Golang in Ubuntu.
  - Install HUGO in Ubuntu.
  - Install Vim in Ubuntu.
  - Install Vim-Plug in Ubuntu.
  - Install Vim plugins in Ubuntu.
  - Install Zsh in Ubuntu.
  - Install Oh My Zsh in Ubuntu.
  - Configure Oh My Zsh in Ubuntu.
- Install Docker Desktop.
- Configure File Explorer:
  - Show file extensions.
  - Open file explorer to This PC.
  - Set as background option only for extended Context Menu.
  - Disable recently opened items from JumpList.
- Microsoft Windows optional features:
  - Disable Windows Media Player.
  - Disable Internet Explorer.
  - Disable Microsoft XPS Document Writer.
  - Disable WorkFolders Client.
  - Enable Microsoft Hyper-V.
  - Enable Windows Sandbox.
- Configure Windows 11 power plan.
- Rename PC.

## Alias and functions for Zsh in Ubuntu (Windows Subsystem for Linux)

### Directories commands and functions

| Alias | Description                      |
| ----- | -------------------------------- |
| mkcd  | Create folder and navigate to it |

### Linux system commands and functions

| Alias       | Description                                    |
| ----------- | ---------------------------------------------- |
| pathl       | List the content of PATH environment variables |
| sourcefonts | Refresh the system fonts cache                 |

### ZSH commands and functions

| Alias     | Description               |
| --------- | ------------------------- |
| editzsh   | Edit Zsh configuration    |
| sourcezsh | Refresh Zsh configuration |

### NeoVim commands and functions

| Alias      | Description                  |
| ---------- | ---------------------------- |
| editnvim   | Edit init.vim file           |
| sourcenvim | Refresh NeoVim configuration |

### Git commands and functions

| Alias | Description                                                      |
| ----- | ---------------------------------------------------------------- |
| gcb   | git checkout creating new branch                                 |
| ga    | git add                                                          |
| gaa   | git add all                                                      |
| gsc   | git clone, load submodules and navigate to the repository folder |
| gst   | git status                                                       |
| gcmsg | git commit message                                               |
| ggp   | git push origin current_branch                                   |
| glg   | git log                                                          |
| gulc  | Git undo last commit                                             |

### NPM commands and functions

| Alias | Description                       |
| ----- | --------------------------------- |
| ngl   | List global NPM packages          |
| ngo   | List outdated global NPM packages |
| ngu   | Update global NPM package         |

### Yarn commands and functions

| Alias | Description                                   |
| ----- | --------------------------------------------- |
| yi    | Install Yarn package                          |
| yid   | Install Yarn package as dev dependency        |
| yl    | List all Yarn packages locally installed      |
| ylo   | List outdated Yarn packages locally installed |
| yu    | Update Yarn package                           |
| yua   | Upgrade all Yarn packages                     |
| yr    | Remove Yarn package                           |

### Docker commands and functions

| Alias | Description                        |
| ----- | ---------------------------------- |
| dlc   | List the Docker containers working |
| dlca  | List all the Docker containers     |
| dli   | List all the Docker images         |
| dsc   | Stop Docker container              |
| drc   | Delete Docker container            |
| dri   | Delete Docker image                |

### NestJS commands and functions

| Alias   | Description                      |
| ------- | -------------------------------- |
| nestnew | Create a new project with NestJS |

### Angular commands and functions

| Alias | Description                       |
| ----- | --------------------------------- |
| ngnew | Create a new project with Angular |

### Go commands and functions

| Alias | Description           |
| ----- | --------------------- |
| gmi   | Initialize Go modules |
