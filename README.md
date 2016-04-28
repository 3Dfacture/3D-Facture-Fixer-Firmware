# 3D-Facture-Fixer-Firmware
Beta Version, Copyright:  3D Facture LLC,  2016

1.The Fixer is a simple program based on Maple Mini.Open the official website link:http://leaflabs.com/docs/, find and download Maple-IDE corresponding to your PC system.(If you PC system is Win64,please download maple-IDE(win-XP) first,then do as step 6);

2.Copy maple-ide-0.0.12-windowxp32.zip to :/D,and unzip;

3.Prepare COM.Connect Fixer to your PC,then the light of Fixer will open.Press both Reset and Boot;release Reset first,then release Board,the Fixer will be Entered in DFU-mode. Your PC will check the SerialPort now.Run Maple-IDE,press Tools->SeialPort,you will find the name of virtual USB SerialPort (named COM1,or COM2 and so on.)had been selected.Open DeviceManage of your PC,find COM1,Update the driver installation directory by Dir(D:\maple-ide-0.0.12-windowsxp32\maple-ide-0.0.12-windowsxp32\drivers\mapleDrv\dfu).

4.Upload.Press File->Example->digital->Blink,press Verify. Confirm ¡COM1¡ had been selected,press Tools->Board->Leaflabs Maple Mini Rev2 to Flash Maple.Press Upload(If upload failed,you can press Reset of Fixer when Uploading to try.).

5. Plug USB of Fixer,reset it.Re designated COM directory byD:\maple-ide-0.0.12-windowsxp32\maple-ide-0.0.12-windowsxp32\drivers\mapleDrv\serial

6.You need install LIBUSB32.Open shared link:http://pan.baidu.com/s/1kUdgIt5, download LIBUSB32 and unzip.Run \LIBUSB\bin\inf-wizard.exe,press Next.Choose Device whose description is named maple,Press Next.Press Next,Saved in :C.Waiting for window of Information,press Install Now....At last it will show install successfully,finished.

7.If you have any other problem you can refer to the following links:
http://leaflabs.com
