# Azure-DevOps-Defect-Tracking
#### Python script for opening/closing issues with in Azure DevOps (formally VSTS). This script will interact with a Checkmarx Static Scan report (XML) and Azure DevOps Work Items to add/delete/update Azure DevOps issues.

#### Running the python script on Windows
Install Python 3.6 or some newer version
Download pip if you do not have it. pip should be already installed if you are using Python 2 >=2.7.9 or Python 3 >=3.4 downloaded from python.org. Pip can be installed with C:\Python27\python.exe get-pip.py

#### Install the following modules (i.e. "pip install requests" or "C:\Python27\python.exe -m pip install requests"):
  - requests
  - keyring
  - json
  - logging
  
Note: This example connects to Sean Casey's Azure DevOps instance and requires an authorization token for connection (https://smccheckmarx.visualstudio.com/WebGoat.Net/)

#### Visual Studio solution can be loaded with VSTS.sln (requires file VSTS.phproj)
