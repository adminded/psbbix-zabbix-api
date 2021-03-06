# Changelog
##### [0.2.0-alpha2] - 2019-02-05
##### Breaking change
- cmdlets Get-ZabbixGroup and Set-ZabbixGroup were renamed to Get-ZabbixHostGroup and Set-ZabbixHostGroup
- However old Get-ZabbixGroup and Set-ZabbixGroup will continue to work, thank to aliases. But they will be depricated in the future.
##### Fixed
- Removed annoying splatting parameter: @zabSessionParams. The paraneter still exist, and can be used, if needed.
- Connect-Zabbix
- Disconnect-Zabbix
- New-ZabbixHost
- Set-ZabbixHost
- Set-Zabbixuser
- A lot of minor things

##### Added
```powershell
Copy-ZabbixHost
Get-ZabbixEvent
Get-ZabbixHistory
Get-ZabbixHostGroup
Get-ZabbixMediaType
Get-ZabbixProblem
Import-ZabbixConfiguration
New-ZabbixApplication
New-ZabbixMediaType
New-ZabbixTemplate
Remove-ZabbixApplication
Remove-ZabbixItem
Remove-ZabbixMediaType
Set-ZabbixApplication
Set-ZabbixEvent
Set-ZabbixHostGroup
Set-ZabbixHostGroupAddHosts
Set-ZabbixHostGroupRemoveHosts
Set-ZabbixItem
Set-ZabbixMaintenance
Set-ZabbixMediaType
Set-ZabbixTemplate
``` 

##### [0.1.8] - 2017-03-03
##### Fixed 
- Get-ZabbixItem error when running with no parameters

##### [0.1.7-bf] - 2016-10-22
##### Fixed
- Cosmetic fixes

##### [0.1.6-bf] - 2016-10-10

##### [0.1.6-bf-beta.1] - 2016-10-09
##### Added
- Validations
- Usability improvemets 

##### [0.1.6-bf-beta] - 2016-10-05
##### Added
- Added Get-ZabbixHelp (gzh), for search/list useful examples within help. Pattern will be highlighted in yellow, thanks to David Mohundro's Find-String module

##### Fixed 
- Fixed duplicate function appearance
- Fixed various functions behavior

##### [0.1.5] - 2016-09-12
##### Fixed 
- Fixed dot sourcing load of additional libraries

##### [0.1.4] - 2016-09-12
##### Fixed 
- Fixed `psbbix.psd1` for [PowerShellGallery](https://www.powershellgallery.com)

##### [0.1.3] - 2016-09-12
##### Fixed 
- Fixed `psbbix.psd1` for [PowerShellGallery](https://www.powershellgallery.com)

##### [0.1.2] - 2016-09-12
##### Added
- Added `psbbix.psd1` for support with the [PowerShellGallery](https://www.powershellgallery.com)
