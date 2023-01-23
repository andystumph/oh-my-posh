# My oh-my-posh theme for PowerShell and WSL

PowerShell
![image](https://user-images.githubusercontent.com/21991233/158450925-5e05ad87-d673-466e-a40e-fde1be42caf3.png)

WSL
![image](https://user-images.githubusercontent.com/21991233/158453088-40ff18bd-473d-44ca-ae44-d3fba39d811b.png)


## Features
- Git integration
- Kubernetes integration
- Azure integration
- Clock
- Operating System
- Admin/Root level

## Installation

**Be sure to to follow the Microsoft [documentation](https://docs.microsoft.com/en-us/windows/terminal/tutorials/custom-prompt-setup) to set up your environment.**

### To Install for PowerShell
- Clone this repo
- Copy ```andy.omp.json``` to your home folder at ```~```
- Run in PowerShell:

```
oh-my-posh.exe init powershell -c ~\andy.omp.json | Invoke-Expression
```

- Optionally, add the above commands to your ```$PROFILE```

### To Install for WSL
- Clone this repo
- Copy ```andy.omp.json``` to your home folder ```~```
- Run in bash:

```
eval "$(oh-my-posh --init --shell bash --config ~/andy.omp.json)"
```

- Optionally, add the above command to your ```.bashrc``` file
