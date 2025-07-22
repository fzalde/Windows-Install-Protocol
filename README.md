# Windows Install Protocol

Installation process used every time I clean install Windows

1. [**Windows 11 ISO Download**](https://www.microsoft.com/en-us/software-download/windows11)
2. [**Rufus Download**](https://rufus.ie/en/)
3. **Windows login bypass**
   - Press `Shift + F10`
   - Run: `start ms-cxh:localonly`
4. **Microsoft Activation Script**

   ```powershell
   irm https://get.activated.win | iex
   ```

5. **Windows Tweaks**

   ```powershell
   irm "https://christitus.com/win" | iex
   ```

6. **App Package Install Script**

   - [Script](App-Package-Script.md)

7. **Ad-Block Utilities**
   - [Ad Block](adblock-utilities.md)

## Miscellaneous

- <https://github.com/Raphire/Win11Debloat>
- [Windows LTSC](LTSC.md)
