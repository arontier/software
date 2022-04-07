# software

This is a guide explaining how to use software at Arontier Co., Inc.

* [OpenVPN](#openvpn)
* [Drivers](#drivers)
* [Applications](#applications)
* [PC-specific software](#pc-specific-software)

## OpenVPN

If you want to access hosts (e.g. servers, printers, nas, and so on) in the office or IDC
from non-Arontier network (e.g. home, cafe, and so on),
you may ask any of system administrators to issue an OpenVPN certificate of your own.

Once you get a certificate file with suffix `.ovpn`, you should download
and install OpenVPN Client Connect from https://openvpn.net/vpn-client/.
Then import your certificate to OpenVPN Client Connect.

If you want to change the certificate password, connect to Arontier network
(you do so with or without OpenVPN connection) and visit http://192.168.10.1 in a browser. 
Enter your account name, which shows in your certificate filename,
and the current password to log in to the site.
Enter a new password and click save. 
Next time you use OpenVPN Client connect, you can use the new password to connect Arontier network.

## Drivers

### Sindoh D430 on Microsoft Windows 10

Visit https://www.sindoh.com/downcenter/dc_list.do and search for D430.
Then select `PCL6 Driver(빠른설치)`, download, and install the driver.

### HP Color LaserJet Pro MFP M277dw on Microsoft Windows 10

It is a printer **for Business Management Department only**.
If you are not in the department stop now. Otherwise download 
https://h30438.www3.hp.com/pub/softlib/software13/LES/M277/HP_Color_LJ_Pro_MFP_M277-full-solution-15345.exe
and install the program *and* the driver.

## Applications

### [Marvin of ChemAxon](files/marvin.pdf)

## PC-specific software

### MAG B550M MORTAR (MS-7C94)

* System & Chipset Drivers (Windows 10): https://download.msi.com/dvr_exe/mb/amd_chipset_drivers_am4_wt.zip
* On-Board VGA Drivers (Windows 10): https://download.msi.com/dvr_exe/mb/amd_vga_driver.zip

## References
