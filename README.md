# dfir-hash-1

> Mirror 1 - Example of Hosted Executable

Before running this executable, verify the SHA256 hash is:

`2A858B6EC58BAD78199888EFDDC6B090CFBF223D18A99B49E90E6525B13910AB`

## Running Programs From the Web

* Developers may need to install software found on the web.
* Installations may involve running executable code on our machine. 
* However, this common practice can be dangerous.
* Running unchecked executables can introduce viruses and vulnerabilites on our machine.
* It's important to verify the 'hash values' for a downloaded executable BEFORE running it.
* A hash provides a calculated value intended to uniquely identify the file contents. 
* Older algorithms like MD5 have sometimes created conflicts. 
* In very rare cases, two different files could have the same MD5 hash value.
* Newer algorithms like SHA256 are generally considered to create truly unique identifiers.

## Verify Safe Executable File Contents

* Get the executable's correct hash value from the original web site. 
* Calculate the hash value of the downloaded executable. 
* If the two values match, you can safely run the executable.

## Calculate Hash Values w/PowerShell

* PowerShell has a command, [Get-FileHash](https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.utility/get-filehash), that calculates hash values. 
* The default algorithm is SHA256. 
* Open PS as Admin in the folder where your file is. 
* Provide the command and the file name to find the hash.

```PowerShell
Get-FileHash helperscript.exe
```

## Calculate Hash Values w/Bash

* Bash has a command, sha256sum, to calculate hash values. 
* Open Bash in the folder where your file is. 
* Provide the command and the file name to find the hash.

```Bash
sha256sum helperscript.exe
```

## DFIR

1. Did you keep your computer safe?

## Resources

* VS Code Extension - PowerShell Pro Tools
* https://dotnet.microsoft.com/download/visual-studio-sdks (4.6.2 Developer Pack)
* Do not use PS2EXE. Executables created with PS2EXE are flagged as dangerous by Windows Defender.
* [Just For Fun](https://ascii.co.uk/art/skulls)
* [Mirror 1](https://github.com/denisecase/dfir-hash-1)
* [Mirror 2](https://github.com/denisecase/dfir-hash-2)