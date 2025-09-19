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
> Remember to save your changes regularly! 


for this Machine ill call it Kali purp  made by useing the new virtual machine and filling out the Required fields <br>
<img width="479" height="78" alt="image" src="https://github.com/user-attachments/assets/ca79bf38-4683-42db-b0c8-f14befbcd423" />
To Create use the new virtual machine 
<img width="249" height="64" alt="image" src="https://github.com/user-attachments/assets/79ab7878-9aff-4785-891c-7b6402d57420" />


under the Name and Opperating System Section 
<hr> </hr>
Name: kali purp
folder: (path to where Vm will be saved and launced From ) C:\Users\YourUserName\VirtualBox VMs <br>
Iso: ( Iso file instalation media used to install ) C:\Users\YourUserName\Downloads\kali-linux-2025.2-installer-purple-amd64.iso <br>
Type: (virtual Machine type to create ) Linux 
<br> sub type : ( Virtual machine sub type of os family ) Ubuntu
<br> Version: ( os version 64 bit or 32 bit ) Ubuntu 64 bit 
<hr></hr>







