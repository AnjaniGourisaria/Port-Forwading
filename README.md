Edit By https://stackedit.io/app#
# Port-Forwading
Working with port


To unistall the Microsoft Store 
   
    Get-AppxPackage *WindowsStore* | Remove-AppxPackage

To Install Microsoft Store Again

	Get-AppXPackage -AllUsers -Name Microsoft.WindowsStore | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml" -Verbose}
    
 Reference 
![image](https://user-images.githubusercontent.com/82677043/154798582-1ed1c855-b518-4178-a20b-db18631fc856.png)


To To unisntall the Microsoft defender download Defender_unistall.exe from github repo 
    
    https://www.majorgeeks.com/mg/getmirror/windows_defender_uninstaller,1.html 
    or download from this repo

To install Defender
    
    Get-AppXPackage -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register “$($_.InstallLocation)\AppXManifest.xml”}


