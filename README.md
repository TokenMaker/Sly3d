# Sly3D downloads

Sly3D is a desktop app that scales a 3D model to real size and splits it into parts that fit your printer, with pegs, part numbers and an assembly guide.

This repository holds the installers for each beta. The app's source code is not here.

## Download (Beta 0.9.1)

| Computer | File |
| --- | --- |
| Mac (Apple silicon and Intel, macOS 11 or later) | [Sly3D_Beta_0.9.1_universal.dmg](https://github.com/TokenMaker/Sly3d/raw/main/Beta%200.9.1/Sly3D_Beta_0.9.1_universal.dmg) |
| Windows (64-bit, Windows 10 and 11) | [Sly3D_Beta_0.9.1_x64-setup.exe](https://github.com/TokenMaker/Sly3d/raw/main/Beta%200.9.1/Sly3D_Beta_0.9.1_x64-setup.exe) |

## Check your download

Each beta folder has a `SHA256SUMS.txt` file. Compare it with the checksum of the file you downloaded.

Mac (Terminal):

```sh
shasum -a 256 ~/Downloads/Sly3D_Beta_0.9.1_universal.dmg
```

Windows (PowerShell):

```powershell
Get-FileHash $HOME\Downloads\Sly3D_Beta_0.9.1_x64-setup.exe
```

If the values don't match, delete the file and download it again.

## Installing

- **Mac:** open the .dmg and drag Sly3D into Applications. If macOS says it can't check the app, open System Settings → Privacy & Security and click **Open Anyway**.
- **Windows:** run the installer. If SmartScreen appears, click **More info**, then **Run anyway**. Beta builds aren't signed yet.

## Feedback and bugs

Send feedback, feature requests and bug reports through the form on the Sly3D website.
