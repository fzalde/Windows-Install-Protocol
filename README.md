# Windows-Install-Protocol
Installation process used every time I clean install windows

1. [**Windows 11 ISO Download**](https://www.microsoft.com/en-us/software-download/windows11)
2. **Windows login bypass**

	* Shift + F10
	* start ms-cxh:localonly

3. **Windows Tweaks**
```powershell
irm "https://christitus.com/win" | iex
```

4. **App Package Install Script**
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

7. **Microsoft Activation Script**
```powershell
irm https://get.activated.win | iex
```

# Miscellaneous
https://github.com/Raphire/Win11Debloat

[Windows LTSC](LTSC.md)