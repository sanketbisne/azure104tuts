In this Lab , we will create a virtual machine in azure 
Before Creating a Virtual machine Lets take a look over Some Basic Concepts

Choose any plan as per your requirement

Basic Tier ( For Dev / Test Workloads )
Standard Tier ( For Production Workloads )

> Step 1. Click on free Trial

> Step 2. Select a Resource group 

Resource group is like a container where all the resources can be stored 
Suppose in our company there are multiple Departments so it will be easily to manage among this.

> Step 3. Choose the Disktype

There are 3 versions availabel
-Standard HDD
-Standard SSD
-Premium SSD

> Step 4. Networking
You can choose among Virtual network , subnet, public ip address and NSG(network security groups)
to allow which port to allow to enhance security of your instance

> Step 5 . Guest Config 

If suppose you have to Write automated script as soon as vm launches for eg: say if you want to launch a Apache web server then you can write a script inside the text space provided.

> Step 6. Tags

By Tags we can give the name to our Virtual machine
say VM Name is Server1

7. Review and Create

You are now able to see the Virtual machine Deployed under Resources Group section



So, Lets Start Creating  a VM

Go to Top Search bar 

Type -> Virtual Machine

![Screenshot (503)](https://user-images.githubusercontent.com/38061560/110242989-77f3b800-7f7e-11eb-9416-3404db03124c.png)



You can also Create VM without using GUI by simplying installing Azure CLI or Right in your Cloud shell


We will be creating VM by GUI here
![Screenshot (504)](https://user-images.githubusercontent.com/38061560/110243039-b9846300-7f7e-11eb-9428-5085d576156c.png)


----------------------
![Screenshot (505)](https://user-images.githubusercontent.com/38061560/110243045-c012da80-7f7e-11eb-86bb-4517648ddc68.png)

------------------------

Click on Virtual Machine

![Screenshot (506)](https://user-images.githubusercontent.com/38061560/110243046-c1dc9e00-7f7e-11eb-95e1-26b29fbe9a63.png)

Add instance details

Virtual machine name

Region to deploy

Select the closest region in your country because of latency and cost relaibility.

We will Choose Central india

![Screenshot (507)](https://user-images.githubusercontent.com/38061560/110243052-c86b1580-7f7e-11eb-8966-599f4aad53fb.png)

Select VM Size ( we will use  General Purpose minimum size 1gb ram  ie for 320iops) 

![Screenshot (508)](https://user-images.githubusercontent.com/38061560/110243053-c99c4280-7f7e-11eb-8a6d-1e264f325d52.png)

Choose any image as per your compatibility

Select Windows Server  Image 

![Screenshot (509)](https://user-images.githubusercontent.com/38061560/110243055-cbfe9c80-7f7e-11eb-9714-eb164dc48187.png)

Select the type 
SSH or password

I have choosed password 

Enter Username

Enter Password

![Screenshot (510)](https://user-images.githubusercontent.com/38061560/110243060-cd2fc980-7f7e-11eb-9e66-7ce4c0e6f7fe.png)

Disks

Now Choose among the 3 Disks as per requirement 
I have taken Standard HDD for minimum IOPS Workloads

Leave all Default

![Screenshot (511)](https://user-images.githubusercontent.com/38061560/110243065-d3be4100-7f7e-11eb-84ae-69fdbaa05e58.png)

Network interface

- Choose Vnet -> Default or we can create a new
- Allow Port (RDP) / http / https

![Screenshot (512)](https://user-images.githubusercontent.com/38061560/110243067-d4ef6e00-7f7e-11eb-8c48-af8644ee9e91.png)


![Screenshot (513)](https://user-images.githubusercontent.com/38061560/110243069-d6b93180-7f7e-11eb-801b-acf5782fce51.png)




![Screenshot (514)](https://user-images.githubusercontent.com/38061560/110243070-d882f500-7f7e-11eb-8a3c-f6fd1b771a01.png)


Leave setting Default

We can also Add a script to install Apache . Nginx webserver , etc in the text box
Tags


![Screenshot (515)](https://user-images.githubusercontent.com/38061560/110243073-dae54f00-7f7e-11eb-8758-8e389a12d514.png)


To name Your VM we can add Tags to it

Name : Windows SERVER

![Screenshot (516)](https://user-images.githubusercontent.com/38061560/110243076-dd47a900-7f7e-11eb-84f8-a3761bd078cf.png)

Azure will charge your VM Per Hr basis
Click on Review + Create

![Screenshot (517)](https://user-images.githubusercontent.com/38061560/110243078-de78d600-7f7e-11eb-81ad-750722c46079.png)

Review before actual deployment

![Screenshot (518)](https://user-images.githubusercontent.com/38061560/110243080-e0429980-7f7e-11eb-9fdd-df50b35e90f4.png)

Your Deployment is in progress


![Screenshot (519)](https://user-images.githubusercontent.com/38061560/110243081-e2a4f380-7f7e-11eb-8611-bffe6d34173a.png)


Go to Resource Group and we will able to see the Status of Your Virtual machine

Your Deployment is Complete

![Screenshot (520)](https://user-images.githubusercontent.com/38061560/110243083-e46eb700-7f7e-11eb-9352-46f0a127575a.png)

Copy Your IP address

Go to the Windows Remote Desktop

![Screenshot (521)](https://user-images.githubusercontent.com/38061560/110243086-e6387a80-7f7e-11eb-99cb-6b5773a67caa.png)


You will be Prompted to See the Credential page 
Add Username and Password


Login to RDP 
![Screenshot (523)](https://user-images.githubusercontent.com/38061560/110243096-edf81f00-7f7e-11eb-985b-59eeaf5f1508.png)

Do some Work and then after successfully completion of work Disconnect the session
![Screenshot (524)](https://user-images.githubusercontent.com/38061560/110243100-f18ba600-7f7e-11eb-93ef-2146d5579f3a.png)
![Screenshot (525)](https://user-images.githubusercontent.com/38061560/110243102-f3556980-7f7e-11eb-94ac-8c181e8ddbd3.png)

Go to Virtual Machine and Disconnect  Delete all Resources Associated with it

![Screenshot (527)](https://user-images.githubusercontent.com/38061560/110243036-b8533600-7f7e-11eb-8f06-97de986973d2.png)

![Screenshot (526)](https://user-images.githubusercontent.com/38061560/110243034-b5f0dc00-7f7e-11eb-98c9-c8bdf0708a37.png)

Thanks 



