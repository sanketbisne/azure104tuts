How to Add extra Disk to Existing VM

1. Create VM
2. Go to the Disk associated with the Virtual machine.
3. Inside Settings-> Choose Disk -> for example -> 1000Gib
4. Give RDP
5. Go to Server Manager -> File And Storage
6. Go to Disk-> 1000Gib-> Create a Virtual machine


-----------------------------------------------------------------------------------------------

Go To VM / Disks
 ![Screenshot (558)](https://user-images.githubusercontent.com/38061560/110524774-d618ca80-8139-11eb-8a61-84e098470702.png)
 
 
 Create And Attach a new Disk
 
 LUN - 1
 Disk name - Extra Disk
 Storage Type - Premium SSD 
 Size - 100 GiB
 Max IOPS - 500
 
 MAx Throughput -100
 Changed to Read/Write.
 
 Demo_Disk Size we created Earlier - 127 Gib
 
 We added say 100 GB an



![Screenshot (559)](https://user-images.githubusercontent.com/38061560/110524836-e7fa6d80-8139-11eb-8d29-df060ac5da09.png)




Go To Our Windows Server 

Click On Disk - Take it Online From Wizard
![Screenshot (560)](https://user-images.githubusercontent.com/38061560/110524980-11b39480-813a-11eb-83b5-2316da6d18df.png)


Create a New Virual Disk

![Screenshot (561)](https://user-images.githubusercontent.com/38061560/110524981-12e4c180-813a-11eb-9250-2a7f4e6641f5.png)

![Screenshot (562)](https://user-images.githubusercontent.com/38061560/110524985-137d5800-813a-11eb-8416-4c37b2bd41d6.png)


Choose Sixe to be allocated 

You can choose any size < 100

![Screenshot (563)](https://user-images.githubusercontent.com/38061560/110524922-0496a580-813a-11eb-841b-a3a305359bf6.png)

Choose Disk letter Say( F )

![Screenshot (564)](https://user-images.githubusercontent.com/38061560/110524926-05c7d280-813a-11eb-8d6b-aac7d8227a47.png)



Choose File System say ( NTFS )

![Screenshot (565)](https://user-images.githubusercontent.com/38061560/110524929-06f8ff80-813a-11eb-850a-6abd8ea01576.png)


![Screenshot (566)](https://user-images.githubusercontent.com/38061560/110524935-082a2c80-813a-11eb-8ff9-4de024b56824.png)


You can Also Extend Volume 

Take New Size eg:50GB


![Screenshot (567)](https://user-images.githubusercontent.com/38061560/110524939-08c2c300-813a-11eb-9a17-0f9d7e516245.png)
![Screenshot (568)](https://user-images.githubusercontent.com/38061560/110524943-09f3f000-813a-11eb-9ec0-d6f7bd84460a.png)
![Screenshot (569)](https://user-images.githubusercontent.com/38061560/110524947-0a8c8680-813a-11eb-92ea-fddafb7f6580.png)

You can check the Volume is been created at This PC

New Volume (F)
![Screenshot (570)](https://user-images.githubusercontent.com/38061560/110524950-0bbdb380-813a-11eb-88e8-4813d1be72c8.png)

Thanks for Taking your Time to Read this .

