# ad-hoc-point-desktop-QRscreen
transmission of work area through the creation of an AD-HOC network by QR code
![1 - Cópia](https://user-images.githubusercontent.com/39824080/90968088-bf24ca80-e4be-11ea-8cdd-2f716957817a.jpg)
![maru_990443_full - Cópia](https://user-images.githubusercontent.com/39824080/90968073-96043a00-e4be-11ea-888c-96c535420b74.jpg)
![maru_990443_full - Cópia - Cópia](https://user-images.githubusercontent.com/39824080/90968074-9a305780-e4be-11ea-82a4-f1a33b2a6136.jpg)
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
