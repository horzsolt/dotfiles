* Install the latest powershell (core) from the Microsoft Store
    * Useful powershell commands: alias
* nerdfonts.com, download Caskaydia Cove Nerd Font -> it has to be the default font in Windows Terminal
* Download and install oh-my-posh
* Modify the powershell profile: echo $PROFILE -> this shows the location where the profile must exist: oh-my-posh --init --shell pwsh --config ~/jandedobbeleer.omp.json | Invoke-Expression
* https://gist.github.com/shanselman/1f69b28bfcc4f7716e49eb5bb34d7b2c?WT.mc_id=-blog-scottha
* Find oh-my-posh themes folder: dir jandedobbeleer.omp.json /s
* Copy the gist file there (actually my version: ohmyposh.json)
* edit $PROFILE and change the theme to this one: ohmyposhv3-v2.json
* change VS Code Font Family to this: CaskaydiaCove NF, Consolas, 'Courier New', monospace
* [Install](https://www.hanselman.com/blog/take-your-windows-terminal-and-powershell-to-the-next-level-with-terminal-icons) terminal icons
* [Install](https://www.hanselman.com/blog/you-should-be-customizing-your-powershell-prompt-with-psreadline) PSreadline
* Currently prompt prediction in listview work ONLY with this version: Install-Module PSReadLine -RequiredVersion 2.2.0-beta1 -AllowPrerelease
* [Example](https://raw.githubusercontent.com/PowerShell/PSReadLine/master/PSReadLine/SamplePSReadLineProfile.ps1) of PSReadline settings
* [Install](https://github.com/ecsousa/PSColors) PSColors
* [Install](https://www.hanselman.com/blog/spend-less-time-cding-around-directories-with-the-powershell-z-shortcut) Z: Install-Module z -AllowClobber

* Install github.cli: winget install Github.Cli --source winget
    * gh auth login
    * usage gh repo clone ... https://cli.github.com/
    
