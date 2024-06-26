# Compile guide

1. [Software install](#software)
2. [Compiling](#compiling)

This only supports compiling on windows as of 3rd of april 2024

### Software
You will need
- .NET 5.0 sdk [x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/sdk-5.0.408-windows-x64-installer) [x86](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/sdk-5.0.408-windows-x86-installer)
- Visual studio 2019 [Link](https://my.visualstudio.com/Downloads?q=visual%20studio%202019&wt.mc_id=o~msft~vscom~older-downloads)
- MOSA Compiler tools [Link](https://github.com/Dell-Optiplex-390/MOSA-Core) (Download all files)
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads) or [VMware player](https://www.vmware.com/content/vmware/vmware-published-sites/us/products/workstation-player/workstation-player-evaluation.html.html)

Launch the .NET 5.0 installer and click "Install"

![.net installer](imgs/net5.0installer.PNG)

Then click "Close" after its installed

![.net installer](imgs/net5.0installer2.PNG)

Now launch the Visual Studio 2019 installer and click "Continue"

![Visual studio installer](imgs/vsinstall1.PNG)

Select ".NET desktop development" and "Desktop development with c++" and click install

![Visual studio installer](imgs/vsinstall2.PNG)

After its installed close the installer

![Visual studio installer](imgs/vsinstall3.PNG)

Click "Not now, Maybe later" if you don't want to login

![Visual studio installer](imgs/vsinstall4.PNG)

Now close Visual Studio and launch the VirtualBox installer or VMware installer

Click "Next"

![VirtualBox](imgs/vbox1.PNG)

Click "Next" again

![VirtualBox](imgs/vbox2.PNG)

Click "Yes"

![VirtualBox](imgs/vbox3.PNG)

Click "Yes" again

![VirtualBox](imgs/vbox4.PNG)

Uncheck "Start Oracle VM VirtualBox after installation" and click "Finish"

![VirtualBox](imgs/vbox5.PNG)

Extract the MOSA Compiler tools and run "Install.bat" as admin

![MOSA Compiler tools](imgs/installbat1.png)

When it asks "Select the desired task" type "install" and hit enter

![MOSA Compiler tools](imgs/installbat2.PNG)

When it asks "Install Visual Studio Intergration?" press y and hit enter

![MOSA Compiler tools](imgs/installbat3.PNG)

When it says "Press any key to continue" press any key and reboot your system

### Compiling

Extract the Ruby4 files 

![Extract ruby4](imgs/extract.png)

Now open Visual Studio as admin

![Visual Studio](imgs/vsrunasadmin.png)

Now click "Open a project or solution

![Visual Studio](imgs/vsopen.png)

Now locate where you extracted the Ruby4 files and open the file called "MOSA1.sln"

![Visual Studio](imgs/vsopenfile.png)

Click "Build" and then "Build Solution"

![Visual Studio](imgs/build.png)

After that completes click "Compile and Run"

![Visual Studio](imgs/run.png)

It will open a VirtualBox or VMware player window once it completes

![VirtualBox](imgs/vboxrunning.png)

The iso will be stored at "C:\Program Files\MOSA-Core\output\" called "MOSA.iso"

If u encounter any issues message waffletm on discord
