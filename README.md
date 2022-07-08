# packaged-msix-win32-apps
Repo with some ready-for-pack MSIX packages

Requirements:

Windows Developer Mode to sideload unpacked folders with powershell

Why the folders aren't packed?

Because I can't sucefully sign in them, so you can't install

How to install?

Download the app, extract, open that folder on powershell admin and run: Add-AppxPackage -register AppxManifest.xml
