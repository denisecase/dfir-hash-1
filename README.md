# dfir-hash-1

## Helper Script

Run helperscript.exe. 

```
.\helperscript.exe
```

## Helpful Info

helperscript.exe

Algorithm 
---------
SHA256     

Hash
----     9469F20245204729AE1FA362A436C7DFB8F4A6CF885AB6269A666FC58B997151

## Check Hash

```PowerShell
Get-FileHash helperscript.exe
```

## Creation Resources

* Compile PS1 to Exe with https://www.powershellgallery.com/packages/ps2exe/1.0.10

```
Install-Module -Name ps2exe
Invoke-ps2exe helperscript.ps1
ls
```
