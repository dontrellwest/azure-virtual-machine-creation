.<p align="center">
<img src="https://i.imgur.com/VvEfgCC.jpeg" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />

<h1>Networking Using Virtual Machines in Micorsoft Azure</h1>


<h2>Description</h2>
Utilize Microsoft Azure to create Windows and Linux virtual machines and monitor network traffic between them using Remote Desktop and Wireshark. 
<br />


<h2>Environments and Utilities Used</h2>

- <b>Microsoft Azure</b>
- <b>Virtual Machines</b>
- <b>Remote Desktop Connection</b> 
- <b>Wireshark</b>
- <b>Various Network Protocols (ICMP, SSH, DHCP, DNS)</b>
- <b>Command-Line Tools</b>

<h2>Operating Systems Used </h2>

- <b>Windows 10</b>
- <b>Ubuntu 24.04</b>

<h2>Project Walk-through:</h2>

<img width="1899" alt="Step 1a - Create Resource Group" src="https://github.com/user-attachments/assets/a1025ba8-cad2-4d78-b298-6ca29f344cf1" />
<img width="1917" alt="Step 1b - Create Resource Group" src="https://github.com/user-attachments/assets/e0e99020-5608-4fd4-9303-678eb929ae9e" />
<img width="1912" alt="Step 1c - Create Resource Group" src="https://github.com/user-attachments/assets/f7dc5f31-98dc-4ca9-9d74-ffe8d44e5666" />
<img width="1914" alt="Step 1d - Create Resource Group" src="https://github.com/user-attachments/assets/0dbe2657-6855-448c-8bf8-6695f7868c7f" />
<img width="1696" alt="Step 2a - Create Virtual machines" src="https://github.com/user-attachments/assets/d6ad95e4-5aa8-4017-8910-a6ed0b8e74e2" />
<img width="1915" alt="Step 2b - Create Virtual machines" src="https://github.com/user-attachments/assets/4e631b07-757b-4e97-b125-74946d4c0af3" />
<img width="1900" alt="Step 2c - Create Virtual machines" src="https://github.com/user-attachments/assets/a4359908-0914-4461-b921-f6689db65c54" />
<img width="1916" alt="Step 2d - Create Virtual machines" src="https://github.com/user-attachments/assets/fb949f0b-942b-4199-99c6-7c26546b16d7" />
<img width="1912" alt="Step 2e - Create Virtual machines" src="https://github.com/user-attachments/assets/12d5f042-6fac-4eb0-9521-f219ff4a94a5" />
<img width="1917" alt="Step 2f - Create Virtual machines" src="https://github.com/user-attachments/assets/0c67e053-1b79-438c-b763-96e42344d44a" />
<img width="1918" alt="Step 2g - Create Virtual machines" src="https://github.com/user-attachments/assets/b14c272c-e63a-41ea-8061-25531f3bf425" />
<img width="1913" alt="Step 2h - Create Virtual machines" src="https://github.com/user-attachments/assets/12d67c7c-5efb-4e79-9e6c-d10f131f390f" />
<img width="1918" alt="Step 2i - Create Virtual machines" src="https://github.com/user-attachments/assets/9a35ca0a-1dec-4c14-9f54-d273e12964cb" />
<img width="1918" alt="Step 2j - Create Virtual machines" src="https://github.com/user-attachments/assets/8b20811d-bca2-4bfe-8e1c-7007b421f450" />
<img width="1922" alt="Step 2k - Create Virtual machines" src="https://github.com/user-attachments/assets/e790f921-f79a-4ce6-aaa8-e2f620d207eb" />
<img width="1913" alt="Step 3a - Create Virtual machines" src="https://github.com/user-attachments/assets/63baf3f6-4056-499e-8d82-8eaf25b663c6" />
<img width="1916" alt="Step 3b - Create Virtual machines" src="https://github.com/user-attachments/assets/87bd6f8a-b3ec-4621-830f-5e82ac8d16e5" />
<img width="1913" alt="Step 3c - Create Virtual machines" src="https://github.com/user-attachments/assets/574615b3-ca76-40ca-a5e7-1dc033f95e3c" />
<img width="1650" alt="Step 3d - Create Virtual machines" src="https://github.com/user-attachments/assets/7465a8c1-dcc4-498e-bded-5e088e3069ff" />
<img width="1915" alt="Step 3e - Create Virtual machines" src="https://github.com/user-attachments/assets/fba7a051-978c-4f09-b4ae-48d3d2adea16" />
<img width="1913" alt="Step 3f - Create Virtual machines" src="https://github.com/user-attachments/assets/a87266e1-dce9-4088-94c5-6c876ba35dbd" />
<img width="1916" alt="Step 3g - Create Virtual machines" src="https://github.com/user-attachments/assets/04ad4853-e6c9-4cf4-aacc-20be8636299f" />
<img width="1917" alt="Step 3h - Create Virtual machines" src="https://github.com/user-attachments/assets/6334c085-a7fc-425b-97d8-0723d2461dc1" />



<p align="center">
Navigate to Microsoft Azure and create a resource group: <br/>
<img src="https://i.imgur.com/Nq0B5A5.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Once my resource group is created, next I'll create the first virtual machine:  <br/>
<img src="https://i.imgur.com/aYzQfAh.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Setting up the first virtual machine:  <br/>
<img src="https://i.imgur.com/i5ztDtu.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<img src="https://i.imgur.com/brgIyMT.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
I'll leave all other settings to default and create this VM:  <br/>
<img src="https://i.imgur.com/OrrgUQv.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Now Azure has set up a VM, an IP for the VM, a network security group, a virtual network, a disk, and a NIC (Network Interface Card):  <br/>
<img src="https://i.imgur.com/gIWv0pv.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Second VM setup:  <br/>
<img src="https://i.imgur.com/vfUOJaG.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<img src="https://i.imgur.com/keOWo28.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
In the "Networking" tab I want to ensure this VM will be on the same virtual network as the first one I made. So, I'll select the one already made for "VM1" instead of creating a new virtual network:  <br/>
<img src="https://i.imgur.com/QXLXthz.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Now if I go back to my resource group we can see that Azure created everything for VM2 as it did for VM1. Notice how there is only one network, however. This is because the two VMs are on the same network:  <br/>
<img src="https://i.imgur.com/gIWv0pv.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
I use VM1's public IP to connect to it using RDP:  <br/>
<img src="https://i.imgur.com/uBvHBXK.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Once my computer has connected to VM1 I will download Wireshark on the VM:  <br/>
<img src="https://i.imgur.com/lfj12DA.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Once Wireshark has downloaded and opened I will select "Ethernet" to observe network traffic:  <br/>
<img src="https://i.imgur.com/qCIJYSG.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
To filter for ICMP (Internet Control Message Protocol) traffic I type "ICMP" at the top of wireshark. To make traffic I will get the private IP address of VM2 and ping it from PowerShell:  <br/>
<img src="https://i.imgur.com/gFeHSRf.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<img src="https://i.imgur.com/MG6FzdI.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Now we can make some firewall configurations to deny any ICMP traffic. To do this I will enter a perpetual ping command into PowerShell:  <br/>
<img src="https://i.imgur.com/HGNy9PE.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Next, I will go to VM2's network security group and create a new inbound security rule denying all ICMP traffic making sure to put its priorty highest, so it will take precedence before all other rules:  <br/>
<img src="https://i.imgur.com/H2zVFyt.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Going back to our VM we can see that the ICMP echo requests aren't getting any responses due to the security change:  <br/>
<img src="https://i.imgur.com/MoFJ39C.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
To revert the change I can either switch the inbound rule to "Allow" instead of "Deny" or delete the rule:  <br/>
<img src="https://i.imgur.com/4tetl2l.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Now ICMP echo requests are back to getting responses:  <br/>
<img src="https://i.imgur.com/FPXmXdY.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Now I will filter to only show SSH (Secure Shell) traffic by typing SSH into the bar at the top and I will SSH into VM2 using PowerShell:  <br/>
<img src="https://i.imgur.com/blrFX07.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
I can type commands like pwd (print working directory) and observe the traffic:  <br/>
<img src="https://i.imgur.com/Corgjvn.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
After filtering for DHCP (Dynamic Host Configuration Protocol) traffic, I attempted to get a new IP address by using the ipconfig /renew command:  <br/>
<img src="https://i.imgur.com/Zq7X1Zv.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Filtering for DNS (Domain Name System) traffic, I can use nslookup to find IP addresses for domain names like "www.google.com" and "www.amazon.com":  <br/>
<img src="https://i.imgur.com/3cGR7xZ.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Finally, I'll observe RDP (Remote Desktop Protocol) traffic by typing in "tcp.port == 3389" in the top bar. You'll notice there is traffic happening without us doing anything. This is because I used RDP to connect to this machine from my own computer and RDP shows us a constant live stream of whats happening:  <br/>
<img src="https://i.imgur.com/0eQAkky.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
