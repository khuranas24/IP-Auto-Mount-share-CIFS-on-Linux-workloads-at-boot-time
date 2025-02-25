Scenario 1 : Create azure file share -> SMB scripts steps can be seen from Azure (Connect) – drawback is credentials will be stored on Linux machine , where any user can access (sudo , root previleges)
Scenario 2 : Using Azure key vault -> Create azure file share -> Create secret in Azure key vault 

We can delete credential files in both the scenarios but in 1st case after reboot mount pt. will disappear


