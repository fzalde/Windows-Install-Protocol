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
   - sysdm.cpl

6. **App Package Install Script**

   - [Script](App-Package-Script.md) 

## Miscellaneous

- <https://github.com/Raphire/Win11Debloat>
- [Windows LTSC](LTSC.md)
- [Ad Block Utilities](adblock-utilities.md)
- [Browser Extensions](extensions.md)
- [Adding a new SSH key to your GitHub account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
- [Generating a new SSH key and adding it to the ssh-agent](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

## Log
- [2025-5-10]
- [2025-11-11]
