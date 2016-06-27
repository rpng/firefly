# Connecting to Monitor and Keyboard

This will go over how to connect a monitor and keyboard to the Mastermind on the Asctec Firefly. This allows you to setup and configure what runs on the Mastermind when it turns on.

* Connect a charged battery to either the terminal on the Mastermind board itself or to the flight controller
	* Note: For long operations you can connect a battery to both then disconnect the dead battery to charge.
![Power terminals](../images/05_01_power_connector.jpg)
* Using the VGA adapter connect to the Mastermind.
![VGA connection](../images/05_02_vga_connection.jpg)
* Connect a USB keyboard to one of the USB 3.0 ports.
	* Note: The USB bus on the Mastermind is very limited and as such it is recommended to use a keyboard with a USB port so that you can use both a mouse and keyboard across one USB header. 
![USB connection](../images/05_03_usb_connection.jpg)
* Power on the Mastermind.
	* Note: If you get a CMOS Checksum Error just power cycle the system until it boots. This is cause by a watch battery on the Mastermind that has died and needs to be replaced.
* Once the boot has completed start the GUI with `sudo start lightdm` and when completed use `sudo init 0` to shut down the Mastermind.