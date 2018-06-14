## PFE Tools

### [PerfView](https://github.com/microsoft/perfview/releases)

Download **PerfView.exe** and **PerfView64.exe**.

### [Chocolatey](https://chocolatey.org/)

* Install

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

* Allow Global Confirmation

```powershell
choco feature enable -n=allowGlobalConfirmation
```

* Install [packages](https://chocolatey.org/packages)

```powershell
choco install package-name
```

### [DebugDiag](https://www.microsoft.com/en-us/download/details.aspx?id=49924)
