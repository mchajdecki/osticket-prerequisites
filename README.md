# osticket-prereqs
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h1 id="vm">In This tutorial we will be creating the following resources in Microsoft Azure and proceed to Install OS Ticket Inside the Virtual Machine.</h1>

- Resource Group
- Windows Virtual Machine

<h3>For an in depth rundown on Microsoft Azure visit this <a href="https://github.com/mchajdecki/Microsoft-Azure">Microsoft Azure Full Tutorial</a>

  
<br>
<br>
<br>
<br>

<h2>This tutorial outlines the following</h2>
<ul>

<li><a href="#rg">Creating Resource Group</a></li>
<li><a href="#vm">Creating a Virtual Machine</a></li>
<li><a href="#lin">Logging Into Virtual Machine</a></li>
</ul>

<br/>


<h1 id="rg"><i>Creating a Resource Group</i></h1>
<h2>A Resource Group is a folder in the cloud that holds virtual machines, virtual networks, storage accounts and other created services.</h2>

<p>
  <ol type="1">
     <li>Navigate to Microsoft Azure main portal.</li>
    <li>Find the Resource Group option on the home page of the portal or type it in the search box.</li>
    <li>Click on the Resource Group option to continue.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osticket-prereqs/blob/65f7f852322784b0ae7525176b7943ac0527d8a7/images/Slide-1.jpg" alt="Creating a Resource Group - Slide_1"/>
</p>
<br>
<hr>



<p>
  <ol type="1">
    <li>Select the Subscription you are currently using.</li>
    <li>Name the Resource Group.(e.g. OSTicketRG)</li>
    <li>Select the appropriate time zone you are located in.</li>
    <li>Click Review + Create on the bottom of the page to continue.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osticket-prereqs/blob/36b2177a05f6300789dfdfec6acd77880098fc39/images/Slide-2.jpg" alt="Creating a Resource Group - Slide_2"/>
</p>
<br>
<hr>


<p>
  <ol type="1">
    <li>Click create again to continue.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osticket-prereqs/blob/50dbb2c9858e856a10fc07f769323e13172379e0/images/Slide-3.jpg" alt="Creating a Resource Group - Slide_3"/>
</p>
<br>
<hr>


<p>
  <ol type="1">
    <li>A prompt message will display that the resource group has been successfully created.</li>
    <li>The newly created Resource Group will show up on the Microsoft Azure main portal.</li>
    <li>The Resource Group has been created.</li>  
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/osticket-prereqs/blob/2bfa522500f3cfdb9765646739d904cfb447e5a1/images/Slide-4.jpg" alt="Creating a Resource Group - Slide_4"/>
</p>
<hr>
<br>
<br>
<br>

<h2>Logging Into a Virtual Machine</h2>

<p>
  <ol type="1">
    <li>Prior to logging into the Virtual Machine gather the log in credentials created and the public IP address associated with Virtual Machine. </li>
    <li>This information can be found in the created VM - head over to Virtual Machine and click on Connect.</li>
    <li>Copy the Public IP Address as you will need it for the Log In.</li>
  </ol>
</p>
<p>
  <img src="https://github.com/mchajdecki/Microsoft-Azure/blob/95a413af6ef9b1e1154c1f15583ceb2f53785d92/images/Slide_27.jpg" alt="LoggingIntoAVirtualMachine - Slide_27">
</p>
<br>
<hr>


<h3>The Virtual Machine that is accessed in this tutorial is from a Mac Computer to a Windows Virtual Machine. Towards the end of the tutorial the reverse will be shown.</h3>


<p>
  <ol type="1">
    <li>In the App Store on a Mac device search for the Windows App software.</li>
    <li>Proceed to download the software at it is necessary in order to log into the created Virtual Machine.</li>
    <li>Open the Windows App software.</li>
  </ol>
</p>
<p>
<img src="https://github.com/mchajdecki/Microsoft-Azure/blob/95a413af6ef9b1e1154c1f15583ceb2f53785d92/images/Slide_28.jpg" alt="LoggingIntoAVirtualMachine - Slide_28">
</p>
<br>
<hr>


<p>
  <ol type="1">
    <li>Click on the + sign in the right hand corner of the Windows App and observe a drop dowm menu appear.</li>
    <li>From the drop down menu click on Add PC to continue the log in process.</li>
  </ol>
</p>
<p>
  <img src="https://github.com/mchajdecki/Microsoft-Azure/blob/95a413af6ef9b1e1154c1f15583ceb2f53785d92/images/Slide_29.jpg" alt="LoggingIntoAVirtualMachine - Slide_29">
</p>
<br>
<hr>


<p>
  <ol type="1">
    <li>Add PC box will display.</li>
    <li>Copy and Paste The Public IP address that was created in the Virtual Machine.</li>
    <li>The add option will be available to click after typing in the IP address.</li>
    <li>Click add option to continue.</li>
  </ol>
</p>
<p>
  <img src="https://github.com/mchajdecki/Microsoft-Azure/blob/a9a63e5d632c2c84c56179cfeae2338a93bbe86b/images/Slide_30.jpg" alt="LoggingIntoAVirtualMachine - Slide_30">
</p>
<br>
<hr>


<p>
  <ol type="1">
    <li>After copying and pasting the Public IP the PC Box will display.</li>
    <li>Double click the saved PC box to continue.</li>
  </ol>
  </p>
<p>
  <img src="https://github.com/mchajdecki/Microsoft-Azure/blob/d134a7038cc557ec3e7700c8a626de602995620b/images/Slide_31.jpg" alt="LoggingIntoAVirtualMachine - Slide_31">
</p>
  <br>
  <hr>



  <p>
  <ol type="1">
    <li>Once the PC box is double clicked a pop up window will display.</li>
    <li>Here enter your usernam and password that was set up during the creation of the Virtual Machine.</li>
    <li>Enter the credentials and click continue.</li>
  </ol>
  </p>
<p>
  <img src="https://github.com/mchajdecki/Microsoft-Azure/blob/840983e9f13b0689b63328c7804e995fd2bd1276/images/Slide_32.jpg" alt="LoggingIntoAVirtualMachine - Slide_32">
</p>

  <br>
  <hr>




<p>
  <ol type="1">
    <li>A Welcome screen to the Windows Virtual Machine will display if all the steps were followed correctly.</li>
    <li>This is a Welcome display screen for a Windows VM that is used for this tutorial.</li>
  </ol>
  </p>
<p>
  <img src="https://github.com/mchajdecki/Microsoft-Azure/blob/75b52de34c4448a156a15b9b63ce50f0ea95360f/images/Slide_33.jpg" alt="LoggingIntoAVirtualMachine - Slide_33">
</p>
  <br>
  <hr>


<p>
 <ol type="1">
 <li>A privacy settings screen will display next.</li>
 <li>Check all the prompts to No.</li>
 <li>Click Accept to continue.</li>
 </ol>
 </p>
<p>
  <img src="https://github.com/mchajdecki/Microsoft-Azure/blob/b6787d44059598c2eade4fd3e1eacc516a37adfa/images/Slide_34.jpg" alt="LoggingIntoAVirtualMachine - Slide_34">
</p>
 <br>
 <hr>


<p>
 <ol type="1">
 <li>A Windows Virtual Machine home page displays.</li>
   <li>That is how you log into a Windows Virtual Machine from a Mac computer.</li>
 </ol>
 </p>
<p>
  <img src="https://github.com/mchajdecki/Microsoft-Azure/blob/0944ae8630442293e1598a0ee2d0ae9d4d6edf73/images/Slide_35.jpg" alt="LoggingIntoAVirtualMachine - Slide_35">
</p>
 <br>
 <br>
 <br>
 <hr>
