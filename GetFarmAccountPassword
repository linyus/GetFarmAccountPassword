Import-Module WebAdministration

#Get Central Admin App Pool - which Runs on FARM account

$CAPool = Get-ChildItem -Path IIS:\AppPools\ | Where { $_.Name -eq "SharePoint Central Administration v4" }

#Get User Name and Password for Farm Account
$CAPool.ProcessModel.UserName
$CAPool.ProcessModel.Password
