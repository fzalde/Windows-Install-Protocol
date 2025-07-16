# Windows-Install-Protocol
Installation process used every time I clean install windows

1. [**Windows 11 LTSC ISO Download**](https://massgrave.dev/windows_ltsc_links)
2. **Windows login bypass**

    * Shift + F10
    * start ms-cxh:localonly

3. **Microsoft Activation Script**
```powershell
irm https://get.activated.win | iex
```
1. **Windows Tweaks**
```powershell
irm "https://christitus.com/win" | iex
```
1. **App Package Install Script**
```powershell
winget install --id=7zip.7zip -e --accept-source-agreements --accept-package-agreements
winget install --id=Brave.Brave -e --accept-source-agreements --accept-package-agreements
winget install --id=Discord.Discord -e --accept-source-agreements --accept-package-agreements
winget install --id=LocalSend.LocalSend -e --accept-source-agreements --accept-package-agreements
winget install --id=Valve.Steam -e --accept-source-agreements --accept-package-agreements
winget install --id=VideoLAN.VLC -e --accept-source-agreements --accept-package-agreements
winget install --id=Mozilla.Firefox -e --accept-source-agreements --accept-package-agreements
winget install --id=Obsidian.Obsidian -e --accept-source-agreements --accept-package-agreements
winget install --id=flux.flux -e --accept-source-agreements --accept-package-agreements
winget install --id=Git.Git -e --accept-source-agreements --accept-package-agreements
winget install --id=Oracle.VirtualBox -e --accept-source-agreements --accept-package-agreements
```

## Useful Links
*https://www.reddit.com/r/WindowsLTSC/wiki/index/*