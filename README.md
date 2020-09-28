# Install-Linux-Ubuntu-
Installing Ubuntu operating system  

- ## Downlaod Ubuntu
https://ubuntu.com/download/desktop

![6](https://user-images.githubusercontent.com/39980537/94357265-3adcde80-004c-11eb-9281-836caea246f6.png)

- ## Download Vitualbox to host linux operating system on your computer
https://www.virtualbox.org/

![VitualBox](https://user-images.githubusercontent.com/39980537/94356771-f569e280-0046-11eb-931b-8de8864080ee.png)

- ## Select as per your host machine(window host)

![Screenshot 2020-09-26 222542](https://user-images.githubusercontent.com/39980537/94356825-7f19b000-0047-11eb-9ee8-6a782594faeb.png)

- ## Open virtualbox and hit New to create a new VMs

![New](https://user-images.githubusercontent.com/39980537/94356876-50e8a000-0048-11eb-9675-375fc2fc9eef.png)

- ## Fill the name, type and version of the operating system

![filltheform](https://user-images.githubusercontent.com/39980537/94356918-c81e3400-0048-11eb-9ccf-a0d1c69b2615.png)

- ## Aloacte memory to the vm and create virtual hard disk
![memory](https://user-images.githubusercontent.com/39980537/94357000-dcaefc00-0049-11eb-92df-37897bc4bceb.png)

![harddisk](https://user-images.githubusercontent.com/39980537/94357035-27307880-004a-11eb-98db-24a5c852ee63.png)

- ## Virtual machine is setup

![installed](https://user-images.githubusercontent.com/39980537/94357089-a4f48400-004a-11eb-9b9f-7d32d6f2d619.png)

- ## Double click on the virtual machine, and click on the folder to navigate disk image of ubuntu 

![image](https://user-images.githubusercontent.com/39980537/94357153-1fbd9f00-004b-11eb-8b8f-998906b81168.png)

![4](https://user-images.githubusercontent.com/39980537/94357205-922e7f00-004b-11eb-9f81-3f91b192468d.png)

![7](https://user-images.githubusercontent.com/39980537/94357553-a7f17380-004e-11eb-9ab4-b16462fbc9cc.png)

- ## Ubuntu Installed
![8](https://user-images.githubusercontent.com/39980537/94357568-cce5e680-004e-11eb-89c3-2aa676fc1b2e.png)

## When you maximize your screen, you will get this result. 

![1](https://user-images.githubusercontent.com/39980537/94393286-72608f00-010f-11eb-95b0-e657ab0b28f0.png)

## To get the full screen, you will have to run the following command in the terminal to install packages
sudo apt install build-essential dkms linux-hearders-$(uname -r)

## After installing the packages, hit Devices(Top toolbar), hit "Insert Guest Addition CD Image", hit run, and restart it.

![2](https://user-images.githubusercontent.com/39980537/94394085-4fcf7580-0111-11eb-876d-272e7edcd550.png)

## Make sure that the status should have the blue icon, not the turtle icon. If you have the turtle icon, it make your hyoer-v is enable. You will have to disable the Hyper-v Hypervision. Otherwise, your installation keeps crashing. 

![2](https://user-images.githubusercontent.com/39980537/94394925-5959dd00-0113-11eb-811f-38a832beb872.png)


# Basic Commands

## To update password

pkexec passwd $USER

## Change these advance settings to "Bidirectional" to copy paste across both operating system

![2](https://user-images.githubusercontent.com/39980537/94394507-5ad6d580-0112-11eb-9588-dbf4b796a41c.png)










