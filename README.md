# CloudScripts
This Repo is designed to be able to easily share powerful powershell scripts to be run quickly.
The way you use any file in this repo will be with the following command:
invoke-expression (invoke-webrequest "URL" -usebasicparsing).content
For example, to run the example script that opens notepad, run the following command: 


invoke-expression (invoke-webrequest "https://raw.githubusercontent.com/ChrisSalProTools/CloudScripts/main/example.txt" -usebasicparsing).content
