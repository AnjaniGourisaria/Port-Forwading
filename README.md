# Port-Forwading
Working with port

Get-AppXPackage -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register “$($_.InstallLocation)\AppXManifest.xml”}


https://consumer.huawei.com/en/support/content/en-us15779991/
To unisntall the defender download Defender_unistall.exe from github repo
![image](https://user-images.githubusercontent.com/82677043/154798582-1ed1c855-b518-4178-a20b-db18631fc856.png)
https://www.majorgeeks.com/mg/getmirror/windows_defender_uninstaller,1.html

TO install Defender

Get-AppXPackage -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register “$($_.InstallLocation)\AppXManifest.xml”}

