<h1>Creating the Domain Controller</h1>

## The first step is to Run VirtualBox. Click New to create a new virtual machine. We'll name it "DC" for Domain Controller. Our version for this machine will be "Other Windows (64-bit)." 

## Under Hardware, depending on the RAM of your host PC, you can adjust the Base Memory and Processors of your VM to your liking. I set mine to 4096 MB and 4 CPUs to reduce lag. Hit Continue up to Create, and create the VM (virtual machine).

## Let's adjust some settings on our new virtual machine. Highlight the VM and click Settings. Under the Advanced tab, change both dropdown menus to Bidirectional. This will help create seamless interaction between your host PC and VMs. 

## Under the Network tab on the left-hand side, select the Adapter 2 tab. Let's enable this adapter and select Internal under the dropdown menu. We now have Adapter 1 to connect to our home internet, and Adapter 2 to connect to our private internal network.

## Let's double click DC to power it on. At this point, we'll want to mount the Server 2019 ISO and boot the VM from there. The VM will now install the ISO. 

## Hit Install Now when the window appears. Let's select the Standard Evaluation (Desktop Experience) operating system and hit next until we reach an option to select installation type. Hit custom installation and hit next to continue to the installation.

## Once the VM restarts, we will have to create a password for our Administrator account. For simplicity's sake, we'll use "Password1" as every password in this lab. Hit finish.

## Let's log into the VM with our new password.

## To improve performance on the VM, let's quickly hit Devices at the top of the VirtualBox window containing the VM preview. Click "Insert Guest Additions CD Image." Open File Explorer and access the new CD drive. Run the file ending in "amd64" Hit Next until install. The VM will restart again.
	
