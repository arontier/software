# software

This is a guide explaining how to use software at Arontier Co., Inc.

* [OpenVPN](#openvpn)
* [Drivers](#drivers)
* [Applications](#applications)
* [PC-specific software](#pc-specific-software)

## OpenVPN

If you want to access hosts (e.g. servers, printers, nas, and so on) in the office or IDC
from non-Arontier network (e.g. home, cafe, and so on),
you may ask any of system administrators to issue an OpenVPN certificate.

### Connecting to Arontier network

Once you get a certificate file with suffix `.ovpn`, you should download
and install OpenVPN Client Connect from https://openvpn.net/vpn-client/.
Then import your certificate to OpenVPN Client Connect.

### Changing your password

If you want to change the certificate password, connect to Arontier network
(you do so in the office or with OpenVPN connection) and visit 

* http://192.168.10.1 (if the certificate filename starts with seoul) or 
* https://192.168.40.9 (if the certificate filename starts with yatap) 

in a browser. 

Enter your account name for `Username` field, which shows in your certificate filename
and the current password for `Password` to log in to the site.
After log in, you should see `Update Password` section. 
Enter a new password twice (for `Password` and `Confirmation`) and click `Save`.
Then log out from the site.  

Next time you use OpenVPN Client Connect, you must use the new password to connect Arontier network.

## Drivers

### (Printer) Sindoh D430 on Microsoft Windows 10

Click https://www.sindoh.com/upload/downcenter/1708092544880391.zip to download the printer driver.
Then uncompress the downloaded file. Find and click `SETUP.EXE` file to start installation.
It may ask the printer network address, which is shown on a white label around the control panel of the printer itself. 

<!--
Visit https://www.sindoh.com/downcenter/dc_list.do and search for D430.
Then select `PCL6 Driver(빠른설치)`, download, and install the driver.
-->

### (Printer) HP Color LaserJet Pro MFP M277dw on Microsoft Windows 10

It is a printer **for Business Management Department only**.
If you are not in the department stop now, full stop. It's not for you.

Otherwise download 
https://h30438.www3.hp.com/pub/softlib/software13/LES/M277/HP_Color_LJ_Pro_MFP_M277-full-solution-15345.exe
and install the program *and* the driver.

## Applications

~~### [Marvin of ChemAxon](files/marvin.pdf)~~

## PC-specific software

### MAG B550M MORTAR (MS-7C94)

* System & Chipset Drivers (Windows 10): https://download.msi.com/dvr_exe/mb/amd_chipset_drivers_am4_wt.zip
* On-Board VGA Drivers (Windows 10): https://download.msi.com/dvr_exe/mb/amd_vga_driver.zip

## References
