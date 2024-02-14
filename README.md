# software

This is a guide explaining how to use software at Arontier Co., Inc.

* [Groupware](#groupware)
  * [Contact](#contact) 
  * [Calendar](#calendar) 
* [OpenVPN](#openvpn)
* [Drivers](#drivers)
* [Applications](#applications)
* [PC-specific software](#pc-specific-software)

## Groupware 

### Contact

To sync groupware contact with your Mac/iPhone or Android, please read https://support.daouoffice.com:8443/DO_2.4.2#sync_calendar_contacts (written in Korean only).
Basically groupware contact supports [CardDAV](https://en.wikipedia.org/wiki/CardDAV). 
The following information can be used in Section 1.1.7 of the above reference:

* Server: `arontier.daouoffice.com`
* Username: your company email address
* Password: password for your company email address

### Calendar

To sync groupware calendar with your Mac/iPhone or Android, please read https://support.daouoffice.com:8443/DO_2.4.2#sync_calendar_contacts (written in Korean only).
Basically groupware calendar supports [CalDAV](https://en.wikipedia.org/wiki/CalDAV).
The credentials described in [Contact](#contact) can be used in Section 1.2.7 of the above reference.

## OpenVPN

If you want to access hosts (e.g. servers, printers, NAS, and so on) in the office or IDC
from non-company network (e.g. home, cafe, and so on),
you may ask any of system administrators to issue an OpenVPN certificate.

### Connecting to company network

Once you get a certificate file with suffix `.ovpn`, you should download
and install OpenVPN Client Connect from https://openvpn.net/vpn-client/.
Then import your certificate to OpenVPN Client Connect.

### Changing password

If you want to change the certificate password, *connect to company network first*
(you do so in the office or with OpenVPN connection) and type one of the followigs in the browser address bar (don't click!):

* http://192.168.10.1 (if the certificate filename starts with `fw-head-office` or `seoul`) or 
* https://192.168.40.2:10443 (if the certificate filename starts with `fw-enchanters`) or 
* https://192.168.40.9 (if the certificate filename starts with `fw-brain` or `yatap`) 

Enter your account name for `Username` field, which shows in your certificate filename
and the current password for `Password` to log in to the site.
After log in, you should see `Update Password` section. 
Enter a new password twice (for `Password` and `Confirmation`) and click `Save`.
Then log out from the site.  

Next time you use OpenVPN Client Connect, you must use the new password to connect company network.

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
If you are not in the department **STOP NOW, FULL STOP**. It's not for you.
Otherwise download "HP 컬러 레이저젯 프로 M277 프린터 시리즈 통합 소프트웨어 및 PCL 6 드라이버" 
https://support.hp.com/kr-ko/drivers/selfservice/hp-color-laserjet-pro-mfp-m277dw/7089945/model/7089949
and install the program *and* the driver.

## Applications

~~### [Marvin of ChemAxon](files/marvin.pdf)~~

## PC-specific software

### MAG B550M MORTAR (MS-7C94)

* System & Chipset Drivers (Windows 10): https://download.msi.com/dvr_exe/mb/amd_chipset_drivers_am4_wt.zip
* On-Board VGA Drivers (Windows 10): https://download.msi.com/dvr_exe/mb/amd_vga_driver.zip

## References
