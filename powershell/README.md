# Install/Update
Search for latest version:
```
winget search Microsoft.PowerShell
```

Install Powershell
```
winget install --id Microsoft.PowerShell --source winget
```

<br>
<br>
***


# Commands (Aliases)
### #PROFILE
- This shows you location of powershell config file
- You can use this variable to reference config file

### df
- Shows disk usage

### admin
- this will elevate to an Administrator Powershell session


### Edit-Profile
- This will open up my powershell config in my code editor

### ll
- file listing excluding dirs


### g
- cd to Documents/Github << I need to change path to my Git direcotry

### gcom
- quick github commit

### lazyg
- quick github commit and push

### Get-PubIP
- Says on the tin


### reload-profile
- says on the tin

### pkill
- process killer

### pgrep
- process finder


<br>
<br>
***

# Pretty Powershell

Script (Run as ADMINISTRATOR!)
```fallback
irm "https://github.com/ChrisTitusTech/powershell-profile/raw/main/setup.ps1" | iex
```


### Edit Windows Terminal Settings
- ctrl + shift + , (comma) will open up settings.json
- ctrl + , (comma) will open up Terminal UI settings
