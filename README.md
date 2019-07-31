# setup-scripts
a set of scripts to get a new computer set up easily

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
- [ ] Run the 'update' script every week checking for new packages
- [ ] Make a step-by-step guide to getting this setup
