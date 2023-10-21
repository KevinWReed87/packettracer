<img src="https://i.imgur.com/rbIuaia.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>



<h1>Packet Tracer Lab: Build Simple Home Network</h1>

I'll be making a simple home network using the cisco packet tracer tool.

<h2>Add network devices to the workspace</h2>

- First step I'll start off in the workspace by adding a pc, laptop and cable modem.

<img src="https://i.imgur.com/5kf6Ucc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/7dsYmPN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

<h2>Change display names of the devices</h2>

- Click on device that needs to be changed
- Click config
- Enter the new name of the newly added device into the display name field

<img src="https://i.imgur.com/Xi9vjHY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/LrS1DYl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

<h2>Add the cables between the devices in the workspace</h2>

- I will use a copper straight-through cable to connect the pc to the wireless router.
- I will connect the cable to the fast ethernet port on the pc.
- Connect the cable to the Ethernet 1 port on the router.
- Devices connected

<img src="https://i.imgur.com/3TDyc8d.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/dvJEiy6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/1elVJh3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

- Now I will connect the wireless router to the cable modem.
- I will use port 1 one the modem
- Internet port on the router

<img src="https://i.imgur.com/Pwx717F.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/UznWit1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

- Now I will connect the modem to the cloud with a coaxial cable.
- Use port 0 for the modem
- Use coaxial 7 for the cloud connection

<img src="https://i.imgur.com/1RhUUz2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/XlNjWDQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/SgheCQI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

<h2>Configure the End Devices and Verify Connectivity</h2>

- Configure the pc
- Clicked on pc and opened desktop tab then ip configuration
- Closed out of ip configuration then clicked on command prompt

<img src="https://i.imgur.com/3RkFzRD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/SrHI96B.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/gFGW0hw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

- In command prompt type ipconfig/all to review the IPv4 info

<img src="https://i.imgur.com/Zl2z75C.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

- Going to test connectivity to the cisco.srv from the PC
- In command prompt type ping cisco.srv
- Ping successful

<img src="https://i.imgur.com/YX7LEba.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

- Configure the laptop.
- Click laptop and select physicl tab.
- We're going to remove the ethernet module and replace it with a wireless module
- Remove ethernet module

<img src="https://i.imgur.com/eWEXq7K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/AiNwUvn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/BWVovEL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

- Install wireless module
- Power on laptop

<img src="https://i.imgur.com/2IafeWx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

- With module instaleed we need to connect laptop to the network
- Click the laptop go to desktop then select pc wireless
- Click the connect tab
- Home Network
- Then connect

<img src="https://i.imgur.com/qn2aAVp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/Y5fmYVl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/kj0WqAV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>

- Close PC Wireless. Select Web Browser in the Desktop tab.
- In the Web Browser, navigate to cisco.srv.
- Connection successful to cisco.srv through laptop.

<img src="https://i.imgur.com/cSt4JZg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/wNkV2Vq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>
<img src="https://i.imgur.com/3jfx1BN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/></p>


