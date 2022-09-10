# Installing new terminal without MStore

- Go [here](https://github.com/microsoft/terminal/releases) and download the `.msixbundle` from the latest release.
- Open a Powershell window in the directory where you download the file.
- Type `Add-AppxPackage` (space) the full file-name you downloaded.
- So for me it would be `Add-AppxPackage Microsoft.WindowsTerminalPreview_1.7.572.0_8wekyb3d8bbwe.msixbundle`

That’s it! Search for “Terminal” in your search bar and “Windows Terminal Preview” should show up.
I recommend creating a shortcut for it on your desktop or taskbar or w/e.
