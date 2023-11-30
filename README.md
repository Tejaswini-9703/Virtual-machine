# Virtual-machine

 ifconfig - gives config. ,<br>
ls - list all files <br>
cat - show content inside file  <br>
scp - copy files from one vm to other  <br>
cd - change directory  <br>
mkdir - make new directory  <br>
touch - makes a new file  <br>
nano - editor inside linux  <br>



Let VM2 inet addr=172.168.2.5   and we want to transfer transfer.txt from VM1 to VM2<br>
ls/home                       VM2(vagrant may come as the output<br> 
ls/home/vagrant            -VM2<br>
scp transfer.txt vagrant@172.168.2.5:home/vagrant    -VM1<br>
ls/home/vagrant            -VM2
