Firenotes<br>
#https://cloud.google.com/appengine/docs/legacy/standard/python/authenticating-users-firebase-appengine<br>
#Virtual-machine

https://drive.google.com/drive/u/0/folders/1me_nJJh0fvdDOXX3ew2jzGQpoP7f_iFt<br>

New => Select type=Linux,   version: Ubuntu(64-bit)<br>
Go toTools=> Network =>NAT Networks => Create<br>
<br>Here IPV4 prefix: The VMs that are going to get inside Virtual Box and which will ask NAT engine of Virtual box to provide them a IP at the boot time, they will get IP in range of 10.0.2.1 to 10.0.2.255
Change network To NAT Network  <br>
gcloud init         to initialize google cloud CLI <br>
<br>
 ifconfig - gives config. ,<br>
ls - list all files <br>
cat - show content inside file  <br>
scp - copy files from one vm to other  <br>
cd - change directory  <br>
mkdir - make new directory  <br>
touch - makes a new file  <br>
nano - editor inside linux  <br>


 <pre>
Let VM2 inet addr=172.168.2.5   and we want to transfer transfer.txt from VM1 to VM2<br>
ls/home                       VM2(vagrant may come as the output<br>  
ls/home/vagrant            -VM2<br>
scp transfer.txt vagrant@172.168.2.5:home/vagrant    -VM1<br>
ls/home/vagrant            -VM2
 <pre>
