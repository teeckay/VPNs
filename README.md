<p align="center">
  
![image](https://github.com/teeckay/VPNs/assets/64244011/108f9f40-4a04-4d0f-9749-1122ceb518a7)


</p>

<h1>Making a VPN connection, Hiding Your IP Address and Changing Geolocations</h1>

This exercise will show how a VPN works by hiding your real IP address, securing your internet connection and changing your geolocation as well. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Windows Virtual Machine)
- Remote Desktop
- VPN Service 

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)


<h2>High-Level Steps</h2>

- Step 1: Verify your IP address.
- Step 2: Create a Virtual Machine in Azure.
- Step 3: Use a VPN service ( Free version of ProtonVPN in this exercise) and test the VPN connection

<h2>Actions and Observations</h2>

<h3>Step1: Verify your IP address.</h3>

<p>
  
Begin by checking your PCs IP address. You can do this by visiting www.whatismyipaddress.com. Mine shows that it is 71.88.22.33 in Chicopee Massachusetts, United States.
</p>
<p>
  
![image](https://github.com/teeckay/VPNs/assets/64244011/8f0b7bbd-5e92-4091-86ca-b7a51a10587a)
  
</p>
<br />

<h3>Step 2: Create a Virtual Machine in Azure.</h3>

<p>
  
Next, I set up a Windows virtual machine in Azure and picked its location to be South Africa to have a different geographical location. Then I log into the virtual machine with Remote Desktop and browse to www.whatismyipaddress.com to see the IP address of the virtual machine. Showing that it is 102.37.152.221 in Johannesburg, South Africa.
</p>
<p>
  
![image](https://github.com/teeckay/VPNs/assets/64244011/6c763110-a16c-40d7-8464-814eedefd073)
  
</p>
<br />

<h3>Step 3: Use a VPN service ( Free version of ProtonVPN in this exercise) and test the VPN connection.</h3>

<p>
  
Next I download protonvpn and install it in the Windows virtual machine.

</p>
<p>
  
![image](https://github.com/teeckay/VPNs/assets/64244011/0ae0a14d-5038-4dd6-acca-12fdecc15bc4)
  
</p>
<br />

<p>
  
Next I connect to a VPN server in Japan from the Windows virtual machine using the Proton VPN service.
</p>
<p>
  
![image](https://github.com/teeckay/VPNs/assets/64244011/1e40895b-6587-4caf-ad0f-1acfbedc734c)
  
</p>
<br />

<p>
  
Next, after connecting to the VPN server in Japan. I visit www.whatismyipaddress.com  for the  third time and my IP address is now showing it is now 138.199.21.202  located in Tokyo Japan.
</p>
<p>
  
![image](https://github.com/teeckay/VPNs/assets/64244011/884a504e-75ab-4cab-b480-2a355562a89f)
  
</p>
<br />

<p>
  
We can now see how a Virtual Private Network provides security and privacy: not only by encrypting the data being sent back and forth, but also by hiding the location of the client and their IP address. 

</p>
