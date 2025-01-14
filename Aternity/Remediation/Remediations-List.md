|#|Folder|Script|Action Name|Description|
|---|---|---|---|---|
|1|Acceleration|Capture-SHMobileInterfacesTrace.ps1|Capture-SHMobileInterfacesTrace|Launch a network capture on the SteelHead Mobile agent|
|2|Acceleration|Check-SHMobileStatus.ps1|Check-SHMobileStatus|Check the status and statistics of the SteelHead mobile agent|
|3|Acceleration|Clear-SHMobileStats.ps1|Clear-SHMobileStats|Reset statistics of the SteelHead mobile agent|
|4|Acceleration|Disable-SHMobileOptimization.ps1|Disable-SHMobileOptimization|Disable optimization on the SteelHead mobile agent|
|5|Acceleration|Enable-SHMobileOptimization.ps1|Enable-SHMobileOptimization|Enable optimization on the SteelHead mobile agent|
|6|Application|Remediation-Aternity-Launch-Recorder.ps1|Aternity-LaunchRecorder|Launch Aternity Recorder|
|7|Application|Remediation-FinApp-Deploy-PatchFromUNC.ps1|Deploy FinApp Patch1903|Download and install patch 1903 for FinApp|
|8|Application|Remediation-FinApp-Deploy-PatchFromURL.ps1|Deploy FinApp Patch1906|Download and install patch 1906 for FinApp|
|9|Application|Remediation-Outlook-Delete-CurrentUserOST.ps1|Outlook-Delete-CurrentUserOST|Delete .OST file|
|10|Application|Remediation-Outlook-Resetpane.ps1|Reset Outlook pane|Removes all customizations to the navigation pane to fix "cannot start" issue|
|11|Application|Remediation-Remove-App-appname.ps1|Remove-App-{{app name}}|Uninstall the application {{app name}} using MSI|
|12|Browser|Remediation-Clear-BrowsingData-Cache-Downloads.ps1|Clear-BrowsingData-Cache-Downloads|Clear caches and temp folders for browsers Google, Firefox and Internet Explorer|
|13|Browser|Remediation-Remove-App-Google-Update-Helper.ps1|Remove-App-Google-Update-Helper|Uninstall the application Google-Update-Helper using MSI|
|14|Disk|Remediation-Check-Disks.ps1|Check Disks - spotFix|Perform a check disk diagnostic and fix errors|
|15|Disk|Remediation-Repair-Volumes-offline.ps1|Repair Volumes offline|Perform an offline scan and fix of volumes or schedule at next reboot|
|16|Network|Remediation-DNS-ClearCache.ps1|DNS Clear Cache|Clear the device DNS Cache|
|17|Security|Remediation-Check-FileHash-Powerpoint.ps1|Check-Filehash-Powerpoint|Check the MD5 file hash of powerpoint|
|18|Security|Remediation-Check-FileHash-WAB.ps1|Check-Filehash-WAB|Check the MD5 file hash of wab|
|19|System|Remediation-Rebuild-PerfCounters.ps1|Rebuild-PerfCounters|Rebuild Performance counters to fix a corruption|
|20|System|Remediation-Reinitialize-PrintSpooler.ps1|Reinitialize-PrintSpooler|Reinitialize the print spooler service|
|21|System|Remediation-Restart-AternityAgent.ps1|Restart-AternityAgent|Restart-AternityAgent|
|22|System|Remediation-Restart-Computer.ps1|Restart-Computer|Reboot the computer|
|23|System|Remediation-Restart-SMSAgentHostService.ps1|Restart-SMSAgentHostService|Restart SMS Agent Host Service (CCMExec)|
|24|System|Remediation-Restart-WindowsSearch.ps1|Restart-WindowsSearch|Fix issues with Windows Search|
|25|System|Remediation-Restart-WindowsUpdateServices.ps1|Restart-WindowsUpdateService|Stop and start services related to Windows Update|
|26|System|Remediation-SCCM-Run-MachinePolicyRetrieval-generic.ps1|SCCM Machine Policy Retrieval - generic|Perform a Machine Policy Retrieval & Evaluaton Cycle to immediately trigger software deployment. Use TriggerSchedule.|
|27|System|Remediation-SCCM-Run-MachinePolicyRetrieval.ps1|SCCM Machine Policy Retrieval|Perform a Machine Policy Retrieval & Evaluaton Cycle to immediately trigger software deployment|
|28|System|Remediation-Update-GroupPolicies.ps1|Update-GroupPolicies|Update Group Policies (GPO)|
|29|Troubleshooting|Remediation-Aternity-Record-UserInteraction.ps1|Record-UserInteraction|Record user interaction on the screen to troubleshoot an application|
