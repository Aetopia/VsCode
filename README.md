🐧 Install Visual-Studi-Code in Linux.

```First```

**Download the file** - https://code.visualstudio.com/#alt-downloads

```Secind```

**Extract it**

```Third```

Move the folder to /opt (with root permission) 
_cp <source> <dest> to copy (copy folder require -r flag so cp -r <source> <dest> for folders)
mv <source> <dest> to move
  
```Fourth```
  
**Open the *Terminal* _Ctrl + Alt + T_** 
  
 paste this:
      **sudo nano /usr/share/applications/code.desktop** 
  
  and paste tis:
  
   ```
  [Desktop Entry]
Name=Visual Studio Code
Comment=Code Editing. Redefined.
GenericName=Text Editor
Exec=code --unity-launch %F
Icon=/opt/VSCode-linux-x64/resources/app/resources/linux/code.png
Type=Application
StartupNotify=false
StartupWMClass=VSCode
Categories=TextEditor;Development;IDE;
MimeType=text/plain;inode/directory;application/x-Visual Studio Code-workspace;
Actions=new-empty-window;
Keywords=vscode;

[Desktop Action new-empty-window]
Name=New Empty Window
Exec=/opt/VSCode-linux-x64/code --new-window %F
Icon=/opt/VSCode-linux-x64/resources/app/resources/linux/code.png
  
  ```
  
 
  
```Save it and exit```
  
*Visual Studio Code* *Should be Installed*
  
 



