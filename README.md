<p align="center">
<img src="https://github.com/user-attachments/assets/43c72d56-c6e4-4971-8cab-7544bb84a933" 
</p>

<h1>Creating A Virtual Machine In Microsoft Azure</h1>
This tutorial will go over how to create and connect to a Virtual Machine in Microsoft Azure.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop


<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)
- Ubuntu Server 22.4

<h2>VM Creation Guide</h2>

- Create a Microsoft Azure account 
- Create a Resourse Group
- Create Virtual Machine  
- Use Windows Remote Desktop to connect to Virtual Machine 

<h2>Deployment and Configuration Steps</h2>

Start by creating a Resourse Group. 
![image](https://github.com/user-attachments/assets/8ca778e7-54b4-4b26-a813-ae43b79eac6a)

Next you will create your Virtual Machine. Put the Virtual Machine in the Resourse Group made in the previous step as well as the same region.
If you are creating a Windows Virtual Machine you will use Windows 10 pro for the image. If you are creating a Windows VM Server you will select Windows server 2022.
If creating a Linux Virtual Machine you will select Ubuntu server22/24.

![image](https://github.com/user-attachments/assets/1d969712-4993-447c-9361-416dbcf03ab3)



![image](https://github.com/user-attachments/assets/354b9de9-df4a-429a-b523-4bbf9e546726)


It is recommended but not required to use at least 2 vcpus when creating your Virtual Machine for smoother connectivity and processing.
You can then review and create your Virtual Machine. Once created it will create its own Virtual Network.


After creating your Virtual Machine find the Public IP Address.
![image](https://github.com/user-attachments/assets/5b3f054f-b405-4ab7-9c5d-eacf4459fd3d)

</p>

</p>
</p>

<p>

  
</p>

<p>
Open Remote Desktop and enter the Public IP Address, Username and Password of the Virtual Machine and connect. 

  
![image](https://github.com/user-attachments/assets/1de21bdb-31d5-4bc6-ae3d-8618a064d8a5)

<p>
When you are finished with the Virtual Machine you can delete it, or you can initiate the Stop command to turn the Virtual Machine off for later use.
</p>
<p>
  <p align="center">
That was a tutorial on creating a Virtual Machine in Microsoft Azure.
</p>
<br />
