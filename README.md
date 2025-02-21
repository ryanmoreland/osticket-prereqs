<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
Here is an overview of the prerequisites and installation steps I followed for the open-source help desk ticketing system, osTicket. This process involves setting up a compatible web server environment, configuring necessary PHP extensions, and meeting all system requirements to ensure optimal performance.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create osTicket server on Azure
- enable internat information services (IIS) in Windows
- Install PHP Manager for IIS
- Install the Rewrite Module
- Install Visual C++ Redistributable (VC redist)
- Install MySQL

<h2>Installation Steps</h2>

<p>
  Create osTicket server in Azure
 
  This is the ticketing system that runs the Browser it will require a web server
and a data base to be installed and configured.

<img src="https://i.imgur.com/hEMPHFd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


</p>
<br />

<p>
  
  Enable Internet Information services(IIS) in Windows

  This is The web server that I install to run on my divice. I enable IIS with Common Gateway Interface(CGI) this allows external applications to interact with information servers on the internet.

<img src="https://i.imgur.com/n4ghwKJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

 
</p>
<br />

<p>

  Install PHP Manager for IIS 

  This is a tool for managing hypertext preprocessor. It is used to interact with databases, manage sessions, and proccess form data. Basically this is a backend web server language.
  
<img src="https://i.imgur.com/OlVIgX0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


</p>
<br />

<p>

  Install the Rewrite Module

  This allows URL rewritting, meaning it can modify URLs to make them more user-friendly.
  
<img src="https://i.imgur.com/JO6wTht.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


</p>
<br />
<p>

  Install VC redist.

  Microsoft Visual C++ redistributeable(VC redist.) is a set of files that help run programs made with Vc Redist. Many apps need it to work properly because it provides essential system files.
  
<img src="https://i.imgur.com/kyIuNHC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


</p>
<br />
<p>
  Install MySQL

  This is the data base osTicket uses to store all of the data. It efficiently organizes data into tables and allows users to retrieve, update, and manage information.
  
<img src="https://i.imgur.com/4RF2or9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />
