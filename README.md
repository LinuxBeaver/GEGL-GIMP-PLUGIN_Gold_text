**WARNING**
If you have an old version of my GEGL Effects Layer Effects plugin before May 2023 this will break GEGL Effects, once this plugin is installed. Check to make sure the version of GEGL Effects you are using was released May 2023 or onward.  If not update here to the latest version.
https://github.com/LinuxBeaver/GEGL-Effects---Layer-Effects-in-Gimp-using-GEGL/releases

To confirm test if GEGL Effects is working after the update, install Gold Text binaries and then see if “inner glow and or bevel” in GEGL Effects still work. If they are not, the update in the link above will fix GEGL Effects.


## Gold Text.
A Gimp Plugin where GEGL transforms plain text into Gold. Go to releases section for Binaries. 
https://github.com/LinuxBeaver/Gimp_Gold_Text_Plugin/releases

Preview 1 
![image](https://github.com/LinuxBeaver/Gimp_Gold_Text_Plugin/assets/78667207/b74606ce-8441-4ead-811e-f38b49c65938)

Preview 2
![image](https://github.com/LinuxBeaver/Gimp_Gold_Text_Plugin/assets/78667207/69f6003b-a889-4308-9341-2dda40a44c71)


## Location to put Binaries 
(THEY DO NOT GO IN THE NORMAL PLUGINS FOLDER)

### Windows
 C:\Users\(USERNAME)\AppData\Local\gegl-0.4\plug-ins
 
### Linux 
 /home/(USERNAME)/.local/share/gegl-0.4/plug-ins
 
### Linux (Flatpak includes Chromebook)
 /home/(USERNAME)/.var/app/org.gimp.GIMP/data/gegl-0.4/plug-ins

## Compiling and Installing

### Linux

To compile and install you will need the GEGL header files (`libgegl-dev` on
Debian based distributions or `gegl` on Arch Linux) and meson (`meson` on
most distributions).

```bash
meson setup --buildtype=release build
ninja -C build

```
### Windows

The easiest way to compile this project on Windows is by using msys2.  Download
and install it from here: https://www.msys2.org/

Open a msys2 terminal with `C:\msys64\mingw64.exe`.  Run the following to
install required build dependencies:

```bash
pacman --noconfirm -S base-devel mingw-w64-x86_64-toolchain mingw-w64-x86_64-meson mingw-w64-x86_64-gegl
```

Then build the same way you would on Linux:

```bash
meson setup --buildtype=release build
ninja -C build
```

### More previews of this based Gimp plugin

Preview 3
![image](https://github.com/LinuxBeaver/Gimp_Gold_Text_Plugin/assets/78667207/272f5fe5-8625-4c2c-854d-26ff5a0c1ae0)

Preview 4
![image](https://github.com/LinuxBeaver/Gimp_Gold_Text_Plugin/assets/78667207/c13dd737-560c-42fe-a526-7a268da7edaf)

Preview 5
![image](https://github.com/LinuxBeaver/Gimp_Gold_Text_Plugin/assets/78667207/17c8c6f6-1038-457f-9d32-6035db1f03f8)

Preview 6
![image](https://github.com/LinuxBeaver/Gimp_Gold_Text_Plugin/assets/78667207/d75f3409-0227-42f0-915e-c293a5eaa2d4)

Preview 7
![image](https://github.com/LinuxBeaver/Gimp_Gold_Text_Plugin/assets/78667207/9bbb992f-fef5-41d4-b2aa-361dba8358d1)


