# software

This is a guide explaining how to use software at Arontier Co., Inc.

* [OpenVPN](#openvpn)
* [Drivers](#drivers)
* [Applications](#applications)
* [PC-specific software](#pc-specific-software)

## OpenVPN

If you want to access hosts (e.g. printers, nas, and so on) in the office or IDC
from  non-Arontier network (e.g. home, cafe, and so on),
you ask system administrators to issue an OpenVPN certificate.

Once you get a certificate file with suffix `.ovpn`, you should import it to
OpenVPN Client Connect program. Download it from https://openvpn.net/vpn-client/
and install it on your device. Then import your certificate to the program.

If you want to change the certificate password, connect to Arontier network
(it does not matter if you do with or without OpenVPN) and visit http://192.168.10.1 in a Chrome browser. 
Enter your account name (it shows in the certificate filename) and the current password to login.
Then enter a new password and click save. 
Next time you use OpenVPN Client Connect program, you can use the new password.

## Drivers

### Sindoh D430 on Microsoft Windows 10

* Visit [https://www.sindoh.com/downcenter/dc_list.do](https://www.sindoh.com/downcenter/dc_list.do) and search for D430.
* Choose `PCL6 Driver(빠른설치)`, download and install the driver.

### HP Color LaserJet Pro MFP M277dw on Microsoft Windows 10

* It is for Business Management Department *only* printer.
* Download [https://h30438.www3.hp.com/pub/softlib/software13/LES/M277/HP_Color_LJ_Pro_MFP_M277-full-solution-15345.exe](https://h30438.www3.hp.com/pub/softlib/software13/LES/M277/HP_Color_LJ_Pro_MFP_M277-full-solution-15345.exe)
* Install the program and the driver.

## Applications

### [Marvin of ChemAxon](files/marvin.pdf)

## PC-specific software

### MAG B550M MORTAR (MS-7C94)

* System & Chipset Drivers (Windows 10): [https://download.msi.com/dvr_exe/mb/amd_chipset_drivers_am4_wt.zip](https://download.msi.com/dvr_exe/mb/amd_chipset_drivers_am4_wt.zip)
* On-Board VGA Drivers (Windows 10): [https://download.msi.com/dvr_exe/mb/amd_vga_driver.zip](https://download.msi.com/dvr_exe/mb/amd_vga_driver.zip)

## References
