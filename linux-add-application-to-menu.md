Create a new file named `{app-name}.desktop`

Modify the following code according to your application
and copy it inside `{app-name}.desktop`

```
[Desktop Entry]
Version=version-number
Name=program-name
Comment=what the application is
Exec=/home/username/path/to/application-launcher
Path=/home/username/path/to/application-folder/
Icon=/home/username/path/to/application-folder/icon.xpm
Terminal=false
Type=Application
Categories=Utility;Application;Development;
```

Add execution permissions to it with `chmod u+x`

And move the file to `/home/$USER/.local/share/applications`

--------------------------------------------------------------------------

Example with Eclipse

```
[Desktop Entry]
Version=Oxygen
Name=Eclipse
Comment=Eclipse is an IDE
Exec=/home/turi/Applications/eclipse-version/eclipse
Icon=/home/turi/Applications/eclipse-version/icon.xpm
Terminal=false
Type=Application
Categories=Utility;Application;Development;
```
