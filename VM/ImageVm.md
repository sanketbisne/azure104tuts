How to Create a Image of a Virtual machine ?

To avoid Data loss of currently running Virtual machine we are taking a snapshot of it, so that incase of any failures we can restore it upto that point of instance.

Step 1. Create a Virtual machine
We will take Windows Server

After that we will create a folder, And file and will be adding some ccontent inside that file

Step 2. Go to Azure Portal and Capture the State of Virtual Machine

Step 3 . The image is Created under Image section (all Services)

The VM will stop when image is been created

Step 4 .  Create the Virtual machine from image and Stop the previous VM (and deallocate it)


The  New Server has the previous data .


except the temporary Disk Data in which data is lost

