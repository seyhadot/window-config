
## Download Nerd Fonts
https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/JetBrainsMono.zip
https://github.com/git-for-windows/git/releases/download/v2.35.1.windows.2/Git-2.35.1.2-32-bit.exe

## Install 
    Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
    iwr -useb get.scoop.sh | iex
    scoop install curl sudo jq neovim gcc nvm fzf
    nvm install 14.16.0
    nvm use 14.16.0
    Install-Module posh-git -Scope CurrentUser -Force
    Install-Module oh-my-posh -Scope CurrentUser -Force
    Install-Module -Name Terminal-Icons -Repository PSGallery -Force                                                                                       
    Install-Module Terminal-Icons
    Install-Module -Name z -Force
    Install-Module -Name PSReadLine -AllowPrerelease -Scope CurrentUser -Force -SkipPublisherCheck
    Set-PSReadLineOption -PredictionSource History
    Set-PSReadLineOption -PredictionViewStyle ListView
    Install-Module -Name PSFzf -Scope CurrentUser -Force
### Open Vim or Editor 
    nvim $PROFILE.CurrentUserCurrentHost
### Paste Into Vim 
    . $env:USERPROFILE\.config\powershell\user_profile.ps1
 
