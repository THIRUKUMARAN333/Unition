#Unition

It's just a simple note taking html or exe

open powershell and locate the file location and then copy this command 'npm install electron --save-dev'
Then try to run with this command 'npm start'
Then install electron 'npm install electron-packager --save-dev' in same powershell
And give final command 'npx electron-packager . MyApp --platform=win32 --arch=x64 --icon=icon.ico'
Then, just open the file and locate "dist folder---->Unition-win32-x64---->Find 'Unition.exe' and add it as desktop shortcut.
And finally you can use this locally on your desktop.
