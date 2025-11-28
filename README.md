# Windows Install Protocol

## 1. **ISO's**

- [**Windows 11 ISO Download**](https://www.microsoft.com/en-us/software-download/windows11)
- [**Windows 11 LTSC ISO Download**](https://massgrave.dev/windows_ltsc_links)

## 2. **Formatting USB**

[**Rufus Download**](https://rufus.ie/en/)

- Rufus' default settings should suffice

## 3. **Windows login bypass**

- Press `Shift + F10`
- Run: `start ms-cxh:localonly`

## 4. **Microsoft Activation Script**

```powershell
irm https://get.activated.win | iex
```

## 5. **Windows Tweaks**

Do not run tweaks until further notice (Nov 26 2025).  
Icons keps disappearing on the taskbar and was only fixed after another clean install.

```powershell
irm "https://christitus.com/win" | iex
```

## 6. **App Package Install Script**

If using windows LTSC you have to reinstall the MS store and install winget before running the app package script:  

1.  run in Admin CMD: `wsreset -i`
2.  [Winget](https://apps.microsoft.com/detail/9nblggh4nns1?hl=en-US&gl=CA) 

[App Package Script](App-Package-Script.md)

## Miscellaneous

- <https://github.com/Raphire/Win11Debloat>
- [Adding a new SSH key to your GitHub account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
- [Generating a new SSH key and adding it to the ssh-agent](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
- sysdm.cpl (opens sytem properties)
- mmsys.cpl (opens Sound settings)
- timedate.cpl (opens Date and Time settings)
- intl.cpl (opens Region settings)
- powercfg.cpl (opens Power Options / Power Plan settings)
- <https://www.reddit.com/r/WindowsLTSC/wiki/index/>
- <https://github.com/microsoft/winget-cli>

## Log

- May 10 2025
- November 11 2025
