# Credentials Manager

The module Credentials Manager provides you with convenient and safe way to store your credentials to file system and effectively re-use them in your scripts.

List of commands:
- Write-Credential
- Read-Credential
- Convert-Credential
Credentials are saved in file with encrypted content. Only user that saved them, can decrypt them.

Compared to other PowerShell credentials managers available to download this one has following advantages:
- it is written purely in PowerShell, without compiled binaries, or C# modules
- credentials are saved in simple files which can be easily managed (move, backup, etc.)
- usernames are also stored as encrypted data, which eliminates another layer of privacy and security concerns
- there is no need for create credentials command, as return objects are already in proper format, ready to be used in other commands.

All commands have documented help system. Type `Get-Help about_CredentialsManager`, or `Get-Command -Module CredentialsManager` for more info.