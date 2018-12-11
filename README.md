# Remote Region Screenshot

## Summary:

This application is still in development. It is currently able to take remote screenshots of regions in Windows machines. The future application will be able to act like a VNC client for regions in remote desktops

## Compilation:

Please execute the following commands:

```
C:\RegionVNC\client> compile.bat
C:\RegionVNC\server> compile.bat
```

## Execution:

* Execute regionVNC.exe from the server folder

```
C:\RegionVNC\server> regionVNC.exe
```

* This will start up a server application listening on port 567
* Execute the RegionVNCClient command as described above, and notice that the region of the remote desktop is shown in client desktop 
Press Escape button to close the window

```
C:\RegionVNC\client> regionVNCClient.exe ServerIP 567 display x y width height
C:\RegionVNC\client> regionVNCClient.exe 192.168.2.80 567 display 100 100 200 200
```
