# Dell-Vostro-15-3568-6006u-hackintosh-Big-Sur


I had posted My EFI here for the Dell Vostro 15 3568 Big Sur Hackintosh Which I made recently using Dortania's Opencore Guide (https://dortania.github.io/OpenCore-Install-Guide/)

What's Good:<BR>
1.Keyboard Works Fine<BR>
2.Trackpad does work but not detected in the system preferences.<BR>
3.Gigabit Inbuilt Ethernet Works Fine.<BR>
4.All USB Ports Work but the inbuilt SD card reader doesn't Work at all.<BR>
5.Intel HD Graphics 520 Works fine.<BR>
6.Integrated Webcam Works Fine.<BR>
  
What's Not Well:<BR>
1.Internal Wifi (QCA9377)and Bluetooth doesn't Work at all and the only way to use internet is by the ethernet or via Android USB tethering by installing horndis.kext in your in library\extensions.<BR>
2.Also i Found that you can't install horndis.kext directly in Mac big Sur via horndis 9.2.pkg.You have to do it manually.<BR>

Issues:-<BR>
1.Battery not detected and once the laptop is on with big sur on battery don't plug in charger as it makes the system unresponsive.<BR>
