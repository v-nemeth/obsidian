Tags: [[Developer]] [[Linux]] [[Environment]]
Time: 16-04-2025-10:56

#### *Abstract*
___
This document provides a step-by-step guide for creating system-wide desktop application entries in Linux. It covers the necessary commands and file structure required to make custom applications appear in the system's application menu, making them easily accessible.
___

# Linux Desktop Entry

## Making a system-wide desktop application

Navigate to the system-wide applications directory where desktop entries are stored
```sh
cd /usr/share/applications/
```

Create or edit a desktop entry file with root privileges
Replace {application_name} with your actual application name
```sh
sudo vim {application_name}.desktop
```

### Example desktop file
```txt
[Desktop Entry]
Version=1.0
Type=Application
Name=
Comment=
Exec=
Icon=
Terminal=false
Categories=
```
Name=           # Application name that appears in menus
Comment=        # Optional description of the application
Exec=           # Command to execute, %F allows file arguments
Icon=           # Path to the icon file (optional)
Terminal=false  # Whether to run in terminal (true/false)
Categories=     # Application categories (e.g., Development;Utility)

___
https://specifications.freedesktop.org/desktop-entry-spec/latest/example.html