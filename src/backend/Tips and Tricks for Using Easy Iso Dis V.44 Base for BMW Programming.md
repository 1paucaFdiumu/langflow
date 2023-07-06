# How to Install Easy DIS v.44 Base for BMW Diagnostic Software
 
Easy DIS v.44 Base is a software package that allows you to run BMW diagnostic software on your PC. It is based on the original GT1 software that is used by BMW dealers and technicians. Easy DIS v.44 Base can be installed on a virtual machine using VMware and Daemon Tools. In this article, we will show you how to install Easy DIS v.44 Base step by step.
 
## What You Need
 
- Easy DIS v.44 BASE iso file[^1^]
- Easy DIS v.44 Program iso file[^1^]
- VMware Workstation version 6[^2^]
- Daemon Tools[^2^]
- A PC with enough disk space and memory to run a virtual machine

## How to Install

1. Open VMware and create a new virtual machine with the following settings:
    - Type: Typical
    - Guest operating system: Other - Other
    - Name: Any name you like
    - Network: Host Only
    - Disk size: 18.635 GB, allocate all disk space now
2. Remove the sound adapter from the virtual machine settings.
3. Add two additional Ethernet adapters and assign them to VMnet1.
4. Uncheck drag and drop from Guest Isolation in the options tab.
5. Mount the Easy DIS v.44 BASE iso file in Daemon Tools.
6. Edit the CD drive of your virtual machine to use the Daemon Tools drive.
7. Start the virtual machine and quickly press F2 to enter the BIOS.
8. Set the CD-ROM to be the first boot device.
9. Save and exit the BIOS. The installation of GT1 will begin automatically.
10. When the installation is finished, you will be asked to eject the CD and restart the VM, but do not do that yet.
11. Eject the Easy DIS v.44 BASE iso file from Daemon Tools.
12. Mount the Easy DIS v.44 Program iso file in Daemon Tools.
13. Shut off and restart the virtual machine.
14. Return to the BIOS by pressing F2 and set the boot order back to default.
15. Save and exit the BIOS. The VM will boot up and ask you to select your language, vehicle, country, dealer number, and other information.
16. Enter 12345 for dealer number and make up the rest of the information as you like.
17. Click End > Quit > OK > OK > OK > OK > OK > OK > OK > OK > OK > OK > OK > OK > OK > OK > OK > OK > OK > OK > OK > OK > End (yes, that's a lot of clicks).
18. The installation is complete. You can now run DIS from your desktop or start menu.

## How to Use DIS
 
DIS stands for Diagnostic and Information System. It is a software that allows you to perform various diagnostic and coding functions on your BMW. You can read and clear fault codes, view live data, program modules, reset service intervals, and more. To use DIS, you need to connect your car to your PC using a compatible interface cable. The most common ones are INPA K+DCAN for OBD2 cars and INPA K+D-CAN for older cars with round 20-pin connector. You also need to configure the network settings of your virtual machine to match the interface cable.
 
**Download 🔗 [https://www.google.com/url?q=https%3A%2F%2Fblltly.com%2F2uHBeN&sa=D&sntz=1&usg=AOvVaw3j22vwouLuGS3rd2aebv9Q](https://www.google.com/url?q=https%3A%2F%2Fblltly.com%2F2uHBeN&sa=D&sntz=1&usg=AOvVaw3j22vwouLuGS3rd2aebv9Q)**


 
### Connecting Your Car

1. Plug the interface cable into your car's diagnostic port. The location of the port may vary depending on the model and year of your car. It is usually under the dashboard, near the steering wheel, or in the engine bay.
2. Plug the other end of the cable into your PC's USB port.
3. Turn on the ignition of your car, but do not start the engine.
4. Open VMware and select your virtual machine.
5. Click on Edit > Virtual Network Editor.
6. Select VMnet1 from the list of virtual networks.
7. Click on NAT Settings.
8. Enter 192.168.68.1 for Gateway IP address.
9. Enter 255.255.255.0 for Subnet mask.
10. Click OK > Apply > OK.
11. Click on Edit > Virtual Machine Settings.
12. Select Network Adapter 1 from the list of hardware devices.
13. Click on Advanced > Generate.
14. Note down the MAC address that is generated.
15. Click OK > OK.
16. Start the virtual machine.
17. Login with username Administrator and password EasyDIS44.

### Running DIS

1. Double-click on the DIS icon on the desktop or go to Start > Programs > DIS v44 > DIS v44.
2. Select your language and click OK.
3. Select Diagnosis from the main menu.
4. Select your vehicle series and model from the list or enter your VIN number.
5. Select Test Schedule from the sub-menu.
6. Select Quick Test from the list of test options.
7. The software will scan your car and display a list of modules and their status. Green means no faults, yellow means faults present, and red means communication error.
8. You can click on each module to view more details, such as fault codes, live data, coding options, etc.
9. You can also perform other functions from the sub-menu, such as Service Functions, Coding Data, or Component Activation.

 8cf37b1e13
 
