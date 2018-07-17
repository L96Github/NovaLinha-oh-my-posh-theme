# NovaLinha Oh-my-posh Theme
A custom theme for beautiful customisation of your powershell. Built for oh-my-posh.

by: Luis Rita
Based and inspired on the Agnoster theme from [oh-my-posh repo](https://github.com/JanDeDobbeleer/oh-my-posh)

### Prerequisites
This theme works with [oh-my-posh](https://github.com/JanDeDobbeleer/oh-my-posh). 
So you have to install oh-my-posh to Powershell:
1. Install posh-git and oh-my-posh:

  ```powershell
  Install-Module posh-git -Scope CurrentUser
  Install-Module oh-my-posh -Scope CurrentUser
  ```

2. Import and set the theme:

  ```powershell
  Import-Module posh-git
  Import-Module oh-my-posh
  ```

3 Make sure to also install version 2.0.0-beta1 of `PSReadLine`

  ```powershell 
  Install-Module -Name PSReadLine -AllowPrerelease -Scope CurrentUser -Force
  ```
    
  *For More info visit [oh-my-posh](https://github.com/JanDeDobbeleer/oh-my-posh).*

###Installation

1. Download this repository to your machine
  ```powershell 
  git clone https://github.com/L96Github/NovaLinha-oh-my-posh-theme.git
  ```

2. Create the folder `C:\Users\<your username>\Documents\WindowsPowerShell\PoshThemes` (replace <your username> with your current username). 
  ```powershell 
  mkdir C:\Users\<your username>\Documents\WindowsPowerShell\PoshThemes
  ```
  
    + (Optional) You can also change the default location where themes are stored by changing oh-my-posh theme setting variable `$ThemeSettings.MyThemesLocation` (the folder defaults to `~\Documents\WindowsPowerShell\PoshThemes`) by running this command:
`$ThemeSettings.MyThemesLocation = "<folder path to your themes>"`

3. Once the theme file is in the right folder, set NovaLinha as the theme of your powershell.

```powershell 
Set-Theme NovaLinha
```

