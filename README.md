# Windows-Install-Protocol
Installation process used every time I clean install windows

1. [**Windows 11 ISO Download**](https://www.microsoft.com/en-us/software-download/windows11)

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

6. **Microsoft Activation Script**
```powershell
irm https://get.activated.win | iex
```

# Miscellaneous
https://github.com/Raphire/Win11Debloat

[Windows LTSC](LTSC.md)