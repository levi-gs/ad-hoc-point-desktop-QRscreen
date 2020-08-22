# ad-hoc-point-desktop-QRscreen
transmission of work area through the creation of an AD-HOC network by QR code

---------------------------------------------------------------------------------------------
The idea is that the whole process for the creation of an AD-HOC network, be simplified by the execution and the display of this information in the QR code for the android application posteiromente is reading the QR code and mirroring the Desktop mode.

---------------------------------------------------------------------------------------------
To create an AD-HOC network on windows, we need to execute the following commands.

netsh wlan set hostednetwork mode=allow ssid=Test key=password

netsh wlan start hostednetwork

---------------------------------------------------------------------------------------------

We just need to channel the WIFI string: WIFI:S:<SSID>;T:<WPA|WEP|>;P:<password>;; through the QR code generator.

The project itself requires the development of a QR code reader, and subsequently the execution code for sending the transmission of the android desktop mode.
---------------------------------------------------------------------------------------------
