The project is all about installing the centos operating system on the VMware virtual machine .

1.First of all you need to download the CentOS-7-x86_64-DVD-2207-02.iso file from the internet .
Once done , you need to now go on VM Wire and proceed.

2. Now you need to click  on the Create a new virtual machine option in the VMware  platform.

3. Now under the installer image disc file click on the C:\Users\Lenovo\Downloads\CentOS-7-x86_64-DVD-2207-02.iso option under the browse part. Now click on next option.

4.Now i had set the virtual machine name to The Lampstack centos
Then set the memory space to 30 gb and select the option of splitting virtual disk into multiple files.

5. Now select customise hardware option and then perform a number of steps
a) Set the memory space to 4gb
b)Go in the network adapter part and select the Bridged:connected directly to the physical port option and then under it select the Replicate physical network connection state.

6. Now select the close part .  new virtual machine window will be opened which would be asking to install centos and it would be reading as (about to reboot automatically in 60 seconds).

7. Then it would be asking to press the enter key in order to continue the installation process.

8. Now a window would appear saying "Welcomme to Centos 7"
it would ask you to select a language of your liking and convenience.
I had selected the english(United states option and moved on )

9. Now a page would open up  which would be containing the installation summary.

10. Under the software selection part under the same Installation summary, select Software selection and under it select the gnome desktop part.

11. Now select the start Installation option . the select the user creation part . Enter the full name and the enter a username for the local host .In my case it was lampstack and the enter a strong password for the same as well.
SEt a root password also for the same and now wait for the installation to proceed.

12. Now when the process is complete, u will be directed towards the actual Operating system that is the Cent os . The installation part is now complete and u would be required to type in the local host user name as well as the password for the user to log in.
So This is the whole procedure for setting up the CentOs-7 operating system under the Lampwire virtual machine.
