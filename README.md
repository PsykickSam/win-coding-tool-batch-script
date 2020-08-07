# Windows Coding Tools Batch Script - Install/Uninstall
After Windows installation application installer programming tools installation script for programmers. Feel free to edit, Fork and Star my repository,

# Included!
  - Chocolatey
  - Visual C++ Redistributable 2005, 2008, 2010, 2012, 2013, 2015, 2017, 2019
  - Visual Studio Code
  - WSL (Ubuntu)
  - Windows Terminal
  - Winrar
  - Java JDK 8
  - Python 
  - NodeJs
  - Deno
  - Rust (WSL) - [To use in cmd/powershell download and install here, [Rust](https://www.rust-lang.org/tools/install)]
  - Git
  - Intellij IDEA Community
  - Intellij Pycharm Community
  - Android Studio 
  - Android SDK
  - Unity 
  - Unity Hub
  - MongoDB (Add to Environment Veriables manually) (Install Mongo Compass From [Mongo Compass](https://www.mongodb.com/try/download/compass)) 
  - MySQL
  - Visual Studio Community Edition with .NET Core Build Tools (only)
  - Blender
  - HeidiSQL (SQL Tool - Use desired one) [ALT - Dbeaver, DataGrid]
  - Virtual Box
  - Anaconda (Python 3)

# Install
```
Run the script as administrator
```

# Guides
  - Use '-y' flag in choco to install without hit 'y' everytime 
  - Use '--installArgs="^/DIR={desired_dir}^"' ("^(double quote in batch)^") [I tried but not working]
  - Add some thing after 'START /WAIT...' command (echo, ::, ...) anything to avoid unfortunate force close
  - Goto [Chocolatey](https://chocolatey.org/) website and find desired software to install

# Next
  - Uninstaller (One can create their own by only replacing 'install' to 'uninstall' in choco installation)

# Cradits 
##### SadmanDMCX 
