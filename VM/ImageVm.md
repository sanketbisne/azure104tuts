How to Create a Image of a Virtual machine ?

To avoid Data loss of currently running Virtual machine we are taking a snapshot of it, so that incase of any failures we can restore it upto that point of instance.

Step 1. Create a Virtual machine
We will take Windows Server


![Screenshot (546)](https://user-images.githubusercontent.com/38061560/110416426-b772ef00-80b9-11eb-93bb-64875f205519.png)



After that we will create a folder, And file and will be adding some content inside that file

1. Create a Folder Name - NewFolder / File- Permanent.txt / Add Content "Hello Everyone"



![Screenshot (547)](https://user-images.githubusercontent.com/38061560/110416431-bb9f0c80-80b9-11eb-9d49-04b223e0bac5.png)



2. Again Create a Folder Name - TempFolder / File -Temporaray.txt / Add Content "this is Temp file"

![Screenshot (548)](https://user-images.githubusercontent.com/38061560/110416728-3bc57200-80ba-11eb-904e-befdd3e24420.png)

Step 2. Go to Azure Portal and Capture the State of Virtual Machine


![Screenshot (549)](https://user-images.githubusercontent.com/38061560/110416981-b2626f80-80ba-11eb-9f44-8972dc2c7098.png)


![Screenshot (550)](https://user-images.githubusercontent.com/38061560/110417001-be4e3180-80ba-11eb-87e8-f455ac0f9611.png)

Step 3 . The image is Created under Image section (all Services)

![Screenshot (551)](https://user-images.githubusercontent.com/38061560/110417748-15a0d180-80bc-11eb-9310-4f99b8f7c8c7.png)


The VM will stop when image is been created

Step 4 .  Create the Virtual machine from image and Stop the previous VM (and deallocate it)


The  New Server has the previous data .


except the temporary Disk Data in which data is lost.


In this way we can create a image from Vm.

thanks For Your time.

