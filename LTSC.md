# Windows Install Protocol For LTSC

Installation process used every time I clean install Windows

1. [**Windows 11 LTSC ISO Download**](https://massgrave.dev/windows_ltsc_links)
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

6. **Microsoft Store**
   - For Windows 11, run in Admin CMD: `wsreset -i`
7. **Installing Winget**

   - [App Installer](https://apps.microsoft.com/detail/9nblggh4nns1?hl=en-US&gl=CA)

8. **App Package Install Script**

   - [Script](App-Package-Script.md)

## Useful Links

- <https://www.reddit.com/r/WindowsLTSC/wiki/index/>
- <https://github.com/microsoft/winget-cli>
- [Ad Block Utilities](adblock-utilities.md)
- [Browser Extensions](extensions.md)