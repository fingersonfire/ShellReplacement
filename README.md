# ShellReplacement

This is a quick and dirty fork of the program made available (like 10 years ago) by avatar-e (Erwin Ried - https://github.com/eried) on Experts-Exchange.
Source Article : https://www.experts-exchange.com/questions/23074854/Windows-Shell-Explorer-Replacement-with-simple-program-launcher.html
Sources Code : http://erwin.ried.cl/files/articles/_public/ShellReplacement_0.1.zip

## Requirements 

### Dev
- Visual Studio 2017 

### Execution
- DotNet Framework 4.5

## Limitation

The software can only have 5 action buttons

## Installation

To replace the main shell, Windows Explorer (explorer.exe), please create the following registry value :

Location : HKEY_CURRENT_USER\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\
Type : String
Name : Shell
Value : The full path to ShellReplacement.exe

Make sure the EXE and the CONFIG files are in the same folder.