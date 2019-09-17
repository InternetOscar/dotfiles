<div align="center">
    <a href="oscardobsonbrown.me">
        <h3>🎨</h3>
        <h1>Dotfiles</h1>
    </a>

My Dotfiles for Windows 10

</div>

## How To use
1a. run these scripts it will set powershell scripts to be handled by powersell instead of notepad

`setx PATHEXT "%PATHEXT%;.PS1" /m`

 `assoc .ps1=Microsoft.PowerShellScript.1`
 
 `ftype Microsoft.PowerShellScript.1="%SystemRoot%\system32\WindowsPowerShell\v1.0\powershell.exe" "%1"`
 
1. download this repo as a .zip and extract it to a place
2. open command prompt as **administrator**
3. type this command `choco install C:\path\to\packages.config`

### Things coming in future updates
- [ ] All scripts in one file
- [ ] Create SOME documentation
- [ ] Make a step-by-step guide to getting this setup
