# wsl2
List all running WSL2 distributions
```Powershell
wsl --list
```

To shutdown all running WSL2 distributions
```Powershell
wsl --shutdown
```

Restart a specific distribution to apply the changes in `.wslconfig`
```Powershell
wsl -d <DistributionName>
```
Or just `wsl` to apply to all distributions