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
4. **Windows Tweaks**
```powershell
irm "https://christitus.com/win" | iex
```
5. **App Package Install Script**
    * [Script](App-Package-Script.md)

## Useful Links
*https://www.reddit.com/r/WindowsLTSC/wiki/index/*