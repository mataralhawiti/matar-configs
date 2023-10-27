# PowerShell config

## Locate pwsh profile
```
$PROFILE
```

## Open the profile
```
code $PROFILE -n
```

## update the profile
```
# oh-my-posh config
oh-my-posh --init --shell pwsh --config C:\Users\matar\AppData\Local\Programs\oh-my-posh\themes\jandedobbeleer.omp.json | Invoke-Expression

# Set-Alias
Set-Alias -Name k -Value kubectl
Set-Alias -Name mk -Value minikube

Set-Alias -Name grep -Value Select-String
```

## reload the profile 
```
. $PROFILE
```

# WSL
```
code .bashrc -n

. ~/.profile 
```


# Linux - TBU