<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create a Azure virtual machine with 2-4 vCPU 's
- Enable /install ISS in Windows alonge side CGI ,Common HTTP Features,  IIS Management Console
- Download and install  PHP Manager for IIS & Rewrite Module 
- Register PHP from within IIS
- Establish permissions and install OS Ticket

<h2>Installation Steps</h2>

![image](https://github.com/MrJJohnson20/osticket-prereqs/assets/127172324/91efdd9d-4cac-4088-a23d-916dcc117f31)

</p>
<p>
In the image above I go to Programs and Features to enable/install ISS ,CGI ,Common HTTP Features and IIS Management Console
  I also do the following steps 
</p>
</p> - Download and install PHP Manager for IIS & Rewrite Module 
</p> - Create the directory C:\PHP
</p> - Download PHP 7.3.8 and inzip the files into the directory of C:\PHP
</p> 
</p> 


<br />

![image](https://github.com/MrJJohnson20/osticket-prereqs/assets/127172324/51b4524f-2671-4751-98eb-51ec21ff1e94)

</p>
<p>
 In the image above after opening ISS as a admin I double click PHP Manager to Register PHP. After registering PHP 
  I  download osticket. Along wiTH the step above i also did the following
</p>   - Download and install VC_redist.x86.exe &  MySQL 5.5.62
</p>   - Copy and extract  upload foulder to c:\inetpub\wwwroot
</p>   - Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”
<br />
</p>
</p>


![image](https://github.com/MrJJohnson20/osticket-prereqs/assets/127172324/1446b69d-c870-49d0-aca7-74e8f168282b)


</p>
<p>
After succesfuly logging into osTicket I make sure I can to restart the server in ISS to make sure everything is working. 
After restarting the server enable some extenstion in PHP manager for some clean up along with Download & install HeidiSQL.
Then osticket to good to go.


</p> -
<br />
