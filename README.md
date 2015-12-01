# DVB-T

First you need to install the appropriate software in order to work with the dongle.

Windows Software
==============================
**Zading**

1) Download Zadig from this link: http://zadig.akeo.ie/

2) Once you have downloaded and extracted the software from the zip, run the .exe file. 

3) A window similar to this one will appear:

![](http://s17.postimg.org/j6vsdzfwv/Zading1.jpg)

4) Select "List all devices" from Options and reinstall or replace the USB drivers in order to access the device:

![](http://s8.postimg.org/pjuevpqv9/Zading2.jpg)

Note: You need to run Zadig to apply this driver to the USB port where you will plug an RTLSDR dongle, if you plug the dongle in a different USB port you'll have to reinstall the drivers for that port.

**SDR#**

1) Download sdrsharp.zip from this link: http://airspy.com/download/ 

2) Extract the file from sdrsharp.zip to a folder on your PC.

3) Double click on install-rtlsdr.bat to start a command prompt that will download all the drivers required to make SDR# work with RTL-SDR.

![](http://s7.postimg.org/5kqrgu7ln/SDR_1.jpg)

4) Plug the dongle and install the appropiate drivers using Zading.

5) Open SDRSharp.exe or SDRSharp Application:

![](http://s18.postimg.org/dmg4zbgfd/SDR_2.jpg)

6) Set the box in the “Source” tab on the top left to ‘RTL-SDR (USB)’.

![](http://s23.postimg.org/tm8o3vw97/SDR_3.jpg)

Note: Don't forget to adjust the RF gain. By default the RF gain is set at zero.

![](http://s30.postimg.org/menq9v929/SDR_4.jpg)

Now we are ready to star using the DVB-T dongle for Windows applications.

