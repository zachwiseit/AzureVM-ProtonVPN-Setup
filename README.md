 ![image](https://github.com/user-attachments/assets/283b3ce1-ca1f-4f12-9d59-c9be2606d963)



<h1>Proton VPN Configuration</h1>
This tutorial will show the necessary steps to setup Proton VPN on a Windows 10 virtual Machine.<br />





<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Windows App
- Proton VPN
- https://whatismyipaddress.com

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 
- macOS Sonama 14.6.1

<h2>Configuration Steps</h2>

- Build Virtual Machines in Azure 
- Test IP address without a VPN 
- Configure Proton VPN 
- Compare the IP addresses
- Test different websites 

<h2>Deployment and Configuration Steps</h2>

First you will have to sign into Microsoft Azure and create a virtual machine with all the necessary resources. 

![image](https://github.com/user-attachments/assets/31439c5a-1241-42fe-a3d9-2b15d2ccc223)

After you sign in click on the Virtual Machines section. 

![image](https://github.com/user-attachments/assets/92addc01-7625-4e4e-b023-6cc7fc1d836a)

Click create on the left and from the drop down click on the first option "Azure virtual machine".

![image](https://github.com/user-attachments/assets/e44705cb-5f8b-45cd-8242-97a5edfac753)

In the resource group section click "Create new" and choose a name. 

![image](https://github.com/user-attachments/assets/f0bc7d72-4c51-4426-832b-a146bb6ad192)

For "Instance details" choose a virtual machine name and a region. 

![image](https://github.com/user-attachments/assets/12cbd73d-1bbb-45fa-a7fd-2ed2efde3062)

Scroll down to "Image" and make sure to choose a Windows operating system. 

![image](https://github.com/user-attachments/assets/3196ab89-fde4-403f-af39-7fe7e961a1e4)

Next for "size" choose any option with a minimum of 2 vcpus for ideal performance. 

Choose a username and password. (write it down) 

![image](https://github.com/user-attachments/assets/acf0e8be-d250-4a59-a777-077e6f7d0106)

Under Licensing make sure to check the box for Windows 10/11 licensing. After that click "Next : Disk".

![image](https://github.com/user-attachments/assets/10d40db6-4ac6-4e16-ae16-7d831e632dad)

Click "Next : Networking". 

![image](https://github.com/user-attachments/assets/abf01958-4b6e-4507-849b-1002b93261ab)

Click "Reveiw + create".

![image](https://github.com/user-attachments/assets/0b2b82d0-f6c4-44da-a548-453a904a60f3)

Now click "Create".

![image](https://github.com/user-attachments/assets/1c4f8d72-90ab-4cf1-8081-462ada588163)

Azure will now create and deploy all necessary resources for the virtual machine. 

![image](https://github.com/user-attachments/assets/75c03936-0233-4145-8c47-484ea2e3b5e9)

After the deployment is complete go back to the home page and click "Virtual machines".

![image](https://github.com/user-attachments/assets/ac00ae9d-270d-4d28-814e-76ac49be0a22)

From this page copy the public IP address for your virtual machine. 

![image](https://github.com/user-attachments/assets/763ddd6e-333c-433e-abc0-04931903f5bb)

Open the Windows APP. 

At the top right next to the plus icon click the down arrow. 

Click Add PC.

![image](https://github.com/user-attachments/assets/4f70284c-fecf-4ee4-b950-2f4e76fdb28b)

For "PC name" paste the public IP address.

![image](https://github.com/user-attachments/assets/5c693e9d-7395-4ffd-94f4-ee9b8b287ce8)



![image](https://github.com/user-attachments/assets/ca5fa26b-2f63-4a3c-b060-65fe3f8703e5)

![image](https://github.com/user-attachments/assets/7673bde5-1099-4977-8594-c9ac82959222)

![image](https://github.com/user-attachments/assets/8cc8464f-7b91-434a-b0aa-27a9ff6b6084)

![image](https://github.com/user-attachments/assets/1e2a7b7c-16b9-41f0-91be-f4f302d22b20)

![image](https://github.com/user-attachments/assets/c92cabc1-0afa-49cc-afdb-ce9821f25fcd)

![image](https://github.com/user-attachments/assets/1c6a008a-fd48-4e3c-af0c-174a963bbf4f)

![image](https://github.com/user-attachments/assets/9b33d5bb-1825-4916-86bc-127cd9a0da90)

![image](https://github.com/user-attachments/assets/3ddd8843-b7f1-4026-862f-e1c213d7ce96)

![image](https://github.com/user-attachments/assets/1e7c6da8-f036-471c-8bb2-9976f9b239ac)

![image](https://github.com/user-attachments/assets/07dd028f-d1bc-428c-a3c8-d44a9f402ede)

![image](https://github.com/user-attachments/assets/7e152634-ab0f-4673-aa1b-0a29b26fb3ca)

![image](https://github.com/user-attachments/assets/f1180b37-ef81-45a3-a137-2f92d04ebabf)

![image](https://github.com/user-attachments/assets/3b9e5162-f7c9-4e12-8512-52c09ee420a9)

![image](https://github.com/user-attachments/assets/7f08275c-229c-40a5-a612-b0cc7e3fbd2f)

![image](https://github.com/user-attachments/assets/3c03f7ed-0e93-42ab-85bb-32e6d54580a0)

![image](https://github.com/user-attachments/assets/c063ee02-79d0-46c2-8a68-683a1957447c)

![image](https://github.com/user-attachments/assets/4310aeb5-06e7-4b59-8f5f-9e9a9f14e3b3)



With the free version you can't choose the location but with a paid subscription you can.

![image](https://github.com/user-attachments/assets/17afd775-3216-4fc8-abe0-316ee89b9b99)

If you go back to https://whatismyipaddress.com/ it will now show your new IP address and location. 

![image](https://github.com/user-attachments/assets/5480acff-d669-4932-a029-9ff5cfad25fc)

With a paid subscription you can choose specific servers in a country or a different country entirely.

![image](https://github.com/user-attachments/assets/be065cd6-20bf-491a-bbb5-e6d40df3d50a)

Next try going to websites you would normaly use like Amazon or Nteflix and see the difference. 

![image](https://github.com/user-attachments/assets/426d7f34-2e1f-46b4-a38b-8e671b257fa2)

Now I have access to Frances Amazon store and their version of Netflix. 

![image](https://github.com/user-attachments/assets/63b10c8d-6b4f-42f0-95a0-196d49ee5632)

Dont forget to go back to Azure and delete all resource groups to prevent any unnecessary charges.

![image](https://github.com/user-attachments/assets/92652485-3d0a-4dd9-838e-68e876b4da93)

![image](https://github.com/user-attachments/assets/be165b43-66ee-4d95-ab5c-3be5d836d565)

![image](https://github.com/user-attachments/assets/1fe83fd2-a689-4ba0-ba70-e65593cf9bdb)

![image](https://github.com/user-attachments/assets/473c92f3-48e1-4bb4-9914-09d9434ce9d2)

![image](https://github.com/user-attachments/assets/f4d38113-14db-4bc4-916a-cfe1c25910cd)

![image](https://github.com/user-attachments/assets/c332d532-2b94-448c-8233-7ee342a64068)

![image](https://github.com/user-attachments/assets/d3a906fd-6642-4568-a4ca-fddb5ebb05a3)
