# How to install on virtualbox

## Extraction

Once the download is complete, extract the “.rar” file. The folder contains the following files:

![alt text](image.png)

## Installation

Create a new machine in Virtual Box.
Set a name of your choice for your VM, select “Linux” & select a computer architecture.

![alt text](image-1.png)

Define the minimum memory size to 1024 MB and Next.

![alt text](image-2.png)

Select “Do not add a virtual hard disk”.

![alt text](image-3.png)

Acept all.

![alt text](image-4.png)

After creating, wait for your VM to appear in your VM.

### Create a NAT Network

If you didn't it before, you must do it now.

![alt text](image-5.png)

Click on Tools > Network 

![alt text](image-6.png)

select tab: Nat Networks > Create

![alt text](image-7.png)

Edit properties.

![alt text](image-8.png)

## Config the VM KIOPTRIX

Go to the main menu. Select the machine and before Network

![alt text](image-9.png)

Change the conection to Nat Network.

![alt text](image-10.png)

Select Storage ->Controller: IDE-> “Add Hard disk” button->“Choose Existing Disk”.->Search and add the Kioptrix VMDK disk file.

![alt text](image-14.png)

![alt text](image-12.png)

![alt text](image-15.png)

![alt text](image-16.png)