# cybersecurity-linux-cmdlinehacker
Cyber security command line hacker tutorial course as done by ITSteve

This is my Journey through the Linux fundamentals in command line 
I am creating this to keep track of learning and have version control on notes etc as I learn and add to my skill set as well as have a real portfolio 


## Linux Pre face -Instalation 
This is for the beggining to install kalli linux  and add to virtual box  as this provides a safe space to allow creation of virtual machines that are isolated form Windows / Mac /Linux  Host systems 
this adds value as it allows course to be followed and also ensures that virtual pcs are in place to work with the system as well as protect the host form accidental data loss , as well as allow filming of items and Exersizes  please note this isnot a full install virual box form scratch  this is install kali vm in virtual box once you have it up and running  For transparency this will use Current version at time of recording . 
<img width="485" height="383" alt="image" src="https://github.com/user-attachments/assets/c3fc2dc6-0e76-4da7-9099-cc6e7e9efc50" />

to be recoreded in Real time . To install the Kaliy Virtual box applicence 
go to kali linux website 

https://www.kali.org/get-kali/#kali-platforms

#Virtual Machine   INSTALATION  - virtual box  option
This option allows for Vm install via virtual box  the web site used was  to get the virtual machine was 
https://www.kali.org/get-kali/#kali-virtual-machines
please note the password  for default usage is 

>[!NOTE]
> Default Virtual machine credentials <br>
> username : **kali** <br>
>password : **kali** 
<br>
For best Practice Change the user name to a secure name as well as set stong passwords based on combinations of letters numbers special charters and avoid comman passwords and reuseing passwords
to install i have followed the Guide posted on the following web site 

https://www.kali.org/docs/virtualization/import-premade-virtualbox/

><br>
MY Install process 
<br>
>[!TIP]
> this was run on windows host for virtual box
> the machine is 3gb approx and ram is 2 gb 
<br>
go to kali web site go to get kali  then got to virtual machines 
<br>
<img width="1519" height="878" alt="image" src="https://github.com/user-attachments/assets/d6326186-f57a-4644-9729-2389625a8a26" />
<br>
select the kali vm for virtual box then click on th down load icon 
<img width="287" height="247" alt="image" src="https://github.com/user-attachments/assets/b1f4eebf-0915-4234-a501-917e3abe0af1" />
<br>
I have Downloaded and in windows selcted to keep default location in wondows C:\downloads\
then I have  then extracted useing winrar but 7zip is also acceptable , then I have clicked on the extracted file to launch the machine and create the applience in virtual box
<img width="653" height="233" alt="image" src="https://github.com/user-attachments/assets/09a61722-73d6-40d6-9f91-d22efe779607" />
 
> [!TIP]
> The Blue Icon  is the manfest file this tells virtual box how big the machine is to be what parmiters ar been used CPU , Ram , IO ,Hdd location 
> <br>
> the red is the actual file that runs as a Virtual Hdd volume that will carry out the machine opperations and act as the isolated system , all command will be processed and parsed and run 
<br>
to launch the vm double click on the blue manafest file  that was extracted form the kalivm down load zip file that was extracted . 
<br>
this will Launch Virtual box as by default .vbox files are associated by the Host Machine  as open with virtual box  if you are running on another hyper visor or other mehtord results may vary and
are out side the scope of this walk through. 

> [!Caution]
> the virtual machine will be created by the blue manafest and will also have the red file associated with the Virtual machine in virtual box if the file is deleted then the virtual machine is Gone.<br>
abd will delete the machine from the 
> confirm that you have the files before deleting any thing.

<br>
This is the irtual Box default spaces with out any virtual machines in opperation 
<img width="956" height="515" alt="image" src="https://github.com/user-attachments/assets/21354c4b-b51a-415f-b80d-ce01b801e800" />
For this install iam Useing the Add Function as the kali image i downloaded is in .vbox file extention and if you try to import it does not see th files as it looks <br>
for .ova virtual machine appliences , this can help 

> [!TIP]
> This is a example of installing kali purple with out useing the premade virtual Machine  we will set the same parameters <br>
> cpu: 4 core Hdd:3GB Ram:2096 MB <br>
> User Kali <br>
User pwd Kali :warning: do not use in live Production change password to someting better :warning:
> Remember to save your changes regularly! <br>


For this Machine ill call it Kali purp  made by useing the new virtual machine and filling out the Required fields <br>
<img width="479" height="78" alt="image" src="https://github.com/user-attachments/assets/ca79bf38-4683-42db-b0c8-f14befbcd423" />
<br>To Create use the new virtual machine  option  this will launch the wizzard 
<img width="597" height="411" alt="image" src="https://github.com/user-attachments/assets/c0557635-53d6-4d16-b22e-a47a02b125a0" />
<br>

<hr> </hr>
<img width="1192" height="832" alt="image" src="https://github.com/user-attachments/assets/a45077d2-0c53-4c3d-b527-60d721cd4d2d" />
please note the user name has been redacted in the White sections please make sure that the user name appears as your name that your loggin to the<br> 
computer as .
Name: kali purp
folder: (path to where Vm will be saved and launced From ) C:\Users\YourUserName\VirtualBox VMs <br>
Iso: ( Iso file instalation media used to install ) C:\Users\YourUserName\Downloads\kali-linux-2025.2-installer-purple-amd64.iso <br>
Type: (virtual Machine type to create ) Linux 
<br> sub type : ( Virtual machine sub type of os family ) Ubuntu
<br> Version: ( os version 64 bit or 32 bit ) Ubuntu 64 bit 
<hr></hr>
This Section is the Unattened instalation <br> 
advanced install techniques can be used to setup user name as well as product keys and also other user settings and guest opperating systems 
< br> 
leave this section un editied 
<img width="1192" height="822" alt="image" src="https://github.com/user-attachments/assets/f77a9050-6f74-4274-bde0-4b35a459e217" />
<hr> </hr>
This section is for the hardware allocated  to the Vm 
<br> 
we will set the base mem (ram ) to 2048 mb by typein the box or dragging the slider  to install <br>
we will set the Processor cores to 4 core , this can be done by the entering the value in the box or dragging the slider 
<img width="599" height="414" alt="image" src="https://github.com/user-attachments/assets/112e9dd5-bc15-448f-a8cd-2de56071073c" />

> [!CAUTION]
> the slider bar will show green to red this is virtual box reading the host operating system and allowing you to provision items .
> Please note if you go in to the red you can crash your system as the Guest will use more resoureces then the host pc can run  causein pc to lose data and require reset

<hr> </hr> 
This Final Section is for the Hard Disk the Sapce that the Virtual Machine will Use
This allows you to select the type of hdd format  in this cae we are leaving the default Virtual box  , but this can be used forother formats like vmds that allow vmware access <Br> 
we will leave the default to accept create the Virtual machin Hdd in default location , this can be changed to suite your prefrences <Br> 
we will use the slider to select the 3 GB Required <br>
once loaded the system can be re booted <br>
<img width="475" height="296" alt="image" src="https://github.com/user-attachments/assets/32aa62cc-6d4e-4f35-b1ca-9936b2c419e9" />
<Br> 
<hr></hr>
<h2>Step 2 Language selection </h2>
This is the Install Language  and language used through out the system 
<br> 
Iam setting to english but you can set as needed please note that the language selected is the system language  <br>
<img width="403" height="302" alt="image" src="https://github.com/user-attachments/assets/c5a78937-38f4-46fd-9c75-9fb57db43c56" />
<br>
<h2>Step 3 Location selection </h2>
This is the Regional setting and location in this case i have marked Australia but any region is acceptable 
<img width="407" height="305" alt="image" src="https://github.com/user-attachments/assets/2ee28445-d9c1-4773-a7b6-bd04b989edcb" />
<br>
<h2>Step 3 Keyboard selection</h2>
This is the Keyboard  this is set to us english as this is the qwerty keyboard <br> 
this can be set to other languages to allow for symbols and extra punctuation <br>
<img width="400" height="302" alt="image" src="https://github.com/user-attachments/assets/d14b1cc6-4b90-4254-b9c6-7170c0f5dbf8" /><br>
once selected the system will go through few background file installation tasks <br>

<img width="397" height="301" alt="image" src="https://github.com/user-attachments/assets/df1dd32a-f689-4ce4-9354-0c6b5e03ef65" />
<br>
<hr> </hr>
<br>
<h2>Step 4 Hostname Selection </h2>
<br> 
the host name identifies the device name localy and also to the network <br>
This can be set to any thing but the hostname can not have spaces <br> 
<img width="404" height="302" alt="image" src="https://github.com/user-attachments/assets/8e0bd17c-667b-4cc8-a1ab-7fcc67874056" />
<br> 
I have amdended host name to Kali-purple as this variant installs both temas tooling in one unit <br> 
Teams refers to Blue Team , Security , Adminis , Netowrk users  Read Team is Hackeers and Pentesters and Cyber actors <br> 
<br>
<hr></hr>
<h2>Step 5 Domain name </h2>
<br> 
This seting allows the System to have its own dns record to identify for DNS and domain usage as this is is Lab with a single terminal that contact the internet <br> 
no DNS will be required . 
<img width="403" height="301" alt="image" src="https://github.com/user-attachments/assets/0ff01c03-e6e2-4d55-98c3-409e0fdb3018" />
<br>
<hr></Hr>
<h2>Step 6 Local user account / Non Root user Account Full name  </h2>
<br> 
This Setting is for the loacl account Full name  as this system is not connected to domain and can not authenticate via MFA or other means <br> 
the first account is added to the local AdminsGroup and can be used to perform commands and run as part of <i>SUDO</i> users Group 
as this is a lab we will use the defaults that Kail Uses for name and password  <b>THIS IS A DEAFULT PASSWORD AND USER NAME AND Should not be used in Production Environment </b><br> 
by default this is empty So enter kali For the user name <BR> 
<img width="401" height="314" alt="image" src="https://github.com/user-attachments/assets/7a941284-8ec8-4c4f-9a30-3fc3302ddcea" />
<Br> 
<HR> <hr> 
<h2> Step 7 New User Account </h2>
<br> 
This Account is the User name to log in to the system , this is the first account and will be added to local admin <br> 
For this user We Will use the<br> Default username: <b>Kali </b> all lower case<br>
Password: <b>kali</b><br> 
This is a Lab environment machine with Minimal risk data and if this gerts damaged then the Machine can be backed up and restored From Snap Shot <br> 
<B> Rember this is a <u>HOME LAB ONLY</u></B> the data used is is for lab training and can be replaced if lost  with minimal down time 
<img width="395" height="310" alt="image" src="https://github.com/user-attachments/assets/2c2dedc4-f7fb-4c74-b073-af3be16950cb" />
<br>
I have cliked next and got to the enter password for account and i have also ticked the check box to make it clear <br> 
<img width="403" height="302" alt="image" src="https://github.com/user-attachments/assets/9067b234-8a44-45b0-b8c6-450c5cc76109" />
<br> 
please rember in Production Passwors should have mixed phrases not be pet names have capitials and special charters and be a mess for any one else to read <br> 
but be meorable for user . 
<hr></hr>
<h2>Step 8 Time zone Settings </h2>
<br> 
This setting controllsthe time zone to allow the device to synch to time and allow functionality as timeing is a major player for normal network operations.
<br>
In this example Australia does not have many time zones depending country selected the time zone list may be large as this covers multiple zones <br>
<img width="407" height="305" alt="image" src="https://github.com/user-attachments/assets/6c172468-c85a-4dbc-8ffa-87bcce8c5006" />
<br> 
Make sure that you select the appropriate time zone closest to you  to make sure things run smooth <br> 
<hr> </hr>
<br>
<h2>Step 9 Partitioning Setting up hdd </h2>
This section Determins how the Hdd is setup and where the boot loader will be made up <br> 
There Are Differnt settings used to perform setups for different purposes  as this is a training lab with no dat that is confidential or secret <BR>
we can use the Guided option - Use Entire disk <br> 
Guided -use entiredisk and setup LVM  is used to set up Hdd for LVM  Machines and is out side of Scope  the Guided Creat and setup Encrypted disk <BR> 
will create the system and setup encryption keypair and will encrypt the drive form the beggining , once active the DRIVE will not allow to be read if removed and connected any pc With out the encryption password been added <br> 
While this is a Great security Measure protection form loss or theft of drive the draw back is if the encrytpion password is lost  the disk will not be able to be decrypted and readable and data can be perminatly lost <br>
<img width="400" height="304" alt="image" src="https://github.com/user-attachments/assets/02c695e8-be5a-4240-baf0-7b957845d815" />
<br>














