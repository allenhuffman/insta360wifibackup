# insta360wifibackup

This project is an automatic WiFi backup for your Insta360 X2 or X3 camera.

This simple script will scan for Insta360 X2 or X3 devices over WiFi, and if it finds one it will connect using the default password and then begin downloading any new files.

The rough prototype runs on any full Raspberry Pi, and can copy contents to the Pi's SD boot drive or an external USB device (configurable in the setup file).

Configuration Settings
=====================
<pre>
WiFiName = 
WiFiPassword = 88888888
SimultaneousTranfers = 1
BackupPath = x2files
</pre>
