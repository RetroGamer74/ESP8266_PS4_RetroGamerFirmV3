# Firmware V3 ( PS4ADMIN ) for chip ESP8266 including PS4 4.55 Exploits

Firmware for chip ESP8266 including PS4 4.55 Exploits

V3 1.2 (RC2) 
============
Added MiraCFW, custom firmware support. Payload added for MiraHEN. In order to connect to get full debugger info, remember to connect to the WiFi Chip from your own computer. Usually the PS4 IP should be 10.10.10.100, so from your computer connected to the WiFi chip, you can send the command: telnet 10.10.10.100 9998

That should be enough to get debug log into your PC Computer.

https://github.com/RetroGamer74/ESP8266_PS4_RetroGamerFirmV3/releases/tag/v1.2-RC2


V3 1.1 (RC1) 
============

https://github.com/RetroGamer74/ESP8266_PS4_RetroGamerFirmV3/releases/tag/v1.1-RC1

File: retrogamerfirmv3_rc1.bin includes next payloads with multilangue spanish / english support.
AppToUSB, Original (Payload Injections 9020 Port ) , HEN, HEN-VR, DUMPER, BACKUP, FTP, Enable Browser, Block FW Updates, Unblock FW Updates, Arabic Guy v1.0 GTA V ModMenu, WildeModz v.1.1 GTA V ModMenu, Lamance v.0.8 GTA V ModMenu.

V3 1.0 (Stable) 
===============

https://github.com/RetroGamer74/ESP8266_PS4_RetroGamerFirmV3/releases/tag/v1.0.0

File: retrogamerfirmv3.bin includes next payloads with only english support.
AppToUSB, Original (Payload Injections 9020 Port ) , HEN, HEN-VR, DUMPER, BACKUP, FTP, Enable Browser, Block FW Updates, Unblock FW Updates, Arabic Guy v1.0 GTA V ModMenu, WildeModz v.1.1 GTA V ModMenu, Lamance v.0.7 GTA V ModMenu.

Demo Video: https://www.youtube.com/watch?v=fjxIDXEObL4


Spanish Installation Instructions
==================================

Descargar el paquete ZIP de este repositorio

Usar retrogamerfirmv3.bin

Instalar haciendo uso del instalador.

Puedes utilizar este instalador que te dejo aquí para versiones Windows x86, Windows x86_64, y MacOSX.

https://github.com/marcelstoer/nodemcu-pyflasher/releases/tag/v3.0



Una vez en PS4:

Ajustes -> Configuración de Red.

Elegir la opción Personalizada.

Seleccionar la red PS4Wifi. ( No requiere contraseña )

Obtener dirección IP -> Automático

En Dirección DNS, Ajustar los valores de DNS Primario y Secundario a: 10.10.10.1

Continuar con los valores por defecto hasta completar la configuración de red.

Por último ir a la Guía de Usuario y esperar a que cargue la web desde el dispositivo ESP8266

English Installation Instructions
==================================

Download the ZIP package of this repository

Use retrogamerfirmv3.bin if you want firmware in english language.

Flash ESP8266 firmware using next flasher.

You can flash the firmware using Windows x86, Windows x86_64, or MacOSX.

https://github.com/marcelstoer/nodemcu-pyflasher/releases/tag/v3.0

Once running PS4:

Settings -> Networking setup.

Choose option Customized.

Select WiFi network identified by PS4Wifi. ( Password not required )

Select Automatic IP.

DNS IP, Set values for Primary and Secondary DNS to: 10.10.10.1

Set next options to their default values, until you reach the end of the networking setup.

Finally go to the Users Guide, in the Settings. The website installed into ESP8266 firmware will be shown.


Ver: 1.0

# Credits
qwertyoruiop, specter dev, flatz

Al Azif GitHub:https://github.com/Al-Azif/ps4-exploit-host

APPtoUSB v15: https://github.com/stooged/AppToUsb-455

DB-SG Backup: https://github.com/stooged/DB_SG_Backup

Dumper-XVortex v1.7: https://github.com/xvortex/ps4-dumper-vtx

FTP-XVortex v1.2: https://github.com/xvortex/ps4-ftp-vtx

HEN-XVortex v1.4: https://github.com/xvortex/ps4-hen-vtx

HEN-VR: https://github.com/stooged/Enable_VR

Enable Browser: https://www.psxhax.com/threads/ps4brew-4-55-full-ps4-jailbreak-4-55-debug-settings-payload-ports.4568

PKG2USB v1: https://github.com/CelesteBlue-dev/ps4-pkg2usb

Original (Port 9020): https://github.com/Cryptogenic/PS4-4.55-Kernel-Exploit

Update Blocker: https://github.com/LightningMods/PS4-4.55-Update-Blocker-HEN

Uninstall Update Blocker: https://github.com/LightningMods/PS4-4.55-Update-Blocker-HEN
