![1]()

#  Task : GeoServer-Build-Windows-installer 2.16.1 -Google-Code-In-

**Note** This step requires a Windows machine.

**Process**

1. First Download and Install NSIS from http://nsis.sourceforge.net/ and extract it.

2. Install the NSIS Access Control plugin from http://nsis.sourceforge.net/AccessControl_plug-in and extract the files.

3. Now copy the **AccessControl.dll** file Present in the plugins directory of **NSIS Acess Control Plugin** to **NSIS Installer** which is present in this directory. "C:\Program Files (x86)\NSIS\Plugins\x86-ansi"

![2]()

4. Then Copy the **AcessControl.dll** file present in the Unicode/Plugins directory of **NSIS Access Control Plugin** to **NSIS Installer** which is present in this directory. "C:\Program Files (x86)\NSIS\Plugins\x86-unicode"
![3]()

5. Now Dowload the Binary GeoSerevr Package from this link https://docs.geoserver.org/stable/en/user/installation/win_binary.html and note that it is compatible with **JAVA 8**. Make Sure It is properly Installed. **or** Download **Nightly Development Build** From here  https://build.geoserver.org. and extract any of them.

6. Now Download the zip file and extract Geoserver 2.16.1 From here http://geoserver.org/release/stable/

7. The Copy the files from **src/release/installer/win** to the root of the unpacked archive (the same directory level as the start.jar)

![4]()

8. See the copied files in the given image below down.

9. Now **Right-click on the installer script GeoServerEXE.nsi and select Compile Script.**
![5]()

10. After successfully compiling the script, an installer named geoserver-2.16.1.exe will be located in the root of the unpacked archive. and It is ready to use.

![6]()

![7]()

