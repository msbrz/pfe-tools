# PFE Tools
Tools and resources used by PFEs

https://aka.ms/pfe/tools

## [PerfView](https://github.com/microsoft/perfview/releases)

Download **PerfView.exe** and **PerfView64.exe**.

## [Sysinternals](https://docs.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite)

Download: https://download.sysinternals.com/files/SysinternalsSuite.zip

```powershell
choco install sysinternals
```

### [ProcessExplorer](https://docs.microsoft.com/en-us/sysinternals/downloads/process-explorer)

    https://download.sysinternals.com/files/ProcessExplorer.zip

### [Procmon](https://docs.microsoft.com/en-us/sysinternals/downloads/procmon)

    https://download.sysinternals.com/files/ProcessMonitor.zip

### [Procdump](https://docs.microsoft.com/en-us/sysinternals/downloads/Procdump)

    https://download.sysinternals.com/files/Procdump.zip

### [Procdump for Linux](https://github.com/Microsoft/ProcDump-for-Linux)

    https://download.sysinternals.com/files/Procdump.zip

    https://github.com/msbrz/procdump-docker

### [TCP View](https://docs.microsoft.com/en-us/sysinternals/downloads/tcpview)

    https://download.sysinternals.com/files/TCPView.zip

## [Log Parser Studio](https://gallery.technet.microsoft.com/Log-Parser-Studio-cd458765)

## [DebugDiag](https://www.microsoft.com/en-us/download/details.aspx?id=49924)

## [Chocolatey](https://chocolatey.org/)

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