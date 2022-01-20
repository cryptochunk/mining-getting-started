# Building the Mining Rig

Once you’ve successfully collected all the [hardware components](https://github.com/cryptochunk/mining-getting-started/blob/main/hardware-requirements.md) needed, you will have to start assembling the rig. It may seem like a daunting task initially, but it’s like building a Lego set if you follow the instructions accurately.

## Steps to assemble the rig

1) Install the CPU in the motherboard or get this done in the shop you buy and test it.

2) Install the fan on the CPU or you can get this done in the shop where you buy and test it.

3) Get the power supply, Connect the 12 pin power cable to the motherboard.

4) Plug the CPU power connector in the motherboard.

5) Connect the SSD to the motherboard with the SATA cable.

6) Connect the SATA power cable to the SSD from the power supply.

7) Connect the power switch to the motherboard.

8) Connect the monitor to the motherboard.

9) Connect Keyboard and Mouse.

10) Connect all GPU risers to the motherboard.

11) Do not use the SATA power cable that comes with the PCIe riser.

12) Attach the GPU/Riser power cable to the PCIe 6pin male connector and power the riser.

13) Use another computer/laptop and prepare the USB for windows installation.

14) Power on the new rig and press “Delete” or “F2” to enter setup.

15) Go through the options and enable “Above 4G decoding”. 
	- Google this for your Mobo.

16) Enable integrated Graphics in the bios. - Google this for your Mobo.

17) Set Restore on AC/Power Loss to Power On. - Google this for your Mobo.

18) Set the boot sequence to boot from external USB first then SSD 
	- Google this for your Mobo.

19) Plug in the windows installation USB to any USB port in the Mobo.

20) Save and exit from the Mobo BIOS. This should reboot to the Windows installation screen.

21) Make sure you are not connected to the internet during the windows installation.

22) Install Windows, use the whole SSD.

23) Use a local account.

24) After installing Windows, download and install Nvidia drivers and MSI afterburner.

25) Create a folder in the Desktop and rename it to Mining

26) Click Start → type “Virus and Threat” Select “Manage Settings”, Under Exclusions select “Add or remove exclusions” click Folder and select the Mining folder in the desktop.

27) Download NBminer from this - https://github.com/NebuTech/NBMiner/releases/download/v40.1/NBMiner_40.1_Win.zip

28) Move NBminer to the Mining folder in the desktop and unzip it.

29) Shutdown the machine and Install the GPUs in the risers and connect the power cables to the GPUs.

30) Power on the machine and boot to windows.

31) Click start and type device manager, open device manager and ensure you can see all your GPUs listed under Display adapters. If you cannot see all your GPUs,

32) Shutdown the machine, unplug from power and

33) Ensure the GPU is seated properly in the riser.

34) The power cables are connected firmly.

35) The PCIe 1x card is connected firmly in the motherboard.

36) The USB cable is connected firmly in the PCIe1x card and in the riser.

37) To create an Ethereum wallet address.

38) Create an account in Kucoin or Binance Or use a wallet app like - Exodus or Metamask.

39) Get the ETH address.

40) Goto the mining folder in your desktop, goto NBMiner folder.

41) Right click on the start_eth.bat and click edit.

42) Delete the long hexadecimal value after -u and paste your ETH address.

43) Change from the default pool by removing the value after -o and before -u and replace it with - asia-eth.2miners.com:2020

44) Double click start_eth.bat this should start mining ethereum now.

45) Disable the login screen -  Google “Disable login screen windows 10” and follow the steps.
	- To make sure mining starts after booting automatically
	- Click Start, type run, open the run window and paste this, make sure to replace <user> with what you see in C:\Users.
	- C:\Users\<user>\Appdata\Roaming\Microsoft\Windows\Start Menu\Programs\Startup
	- Right click on start_eth.bat and select copy
	- In the startup folder, right click and select paste shortcut.
	- Overclock the GPU, Save the changes, and enable start on boot in MSI Afterburner.

46) To monitor the mining performance install [Minerstat](https://minerstat.com/software/windows) a crypto mining monitor and management software.
	
Happy Mining:)
