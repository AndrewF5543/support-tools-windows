# support-tools-windows
Threat Stack Support Tools- Windows

To use this support tool:

Download and save diagnostics.ps1 to your Windows server- click the green 'Clone or Download' button in the top righthand corner of GitHub and select 'Download ZIP'.
Right click and run diagnostics.ps1 with Powershell.

Diagnostics Script Overview

Running the diagnostics.ps1 master script gathers system information. It runs a series of commands that return the following content:

policies.txt: policy settings
status.txt: agent and log collection status
logs folder: recent agent logs
etc folder: config files


The result of diagnostics.ps1 saves in your current working directory in .zip format, named TSLogs_<SERVER_NAME>_<CURRENT_DATE>.zip. An example of the name would be TSLogs_WIN-Test_2017-09-05-171824.zip.

Send that file to Threat Stack. You can encrypt the files with support.pub, also located in the repository.
