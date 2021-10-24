# VIRTUALISATION

### We need to have the basic understanding about our physical computers in order to know the perfect meaning of virtualisation.


 Our personal computers architecture is——
1) Having hardware such as storage, ram, cpu.
2) Next on the top of the hardware we do have the inbuilt os installed which manages the communication between software and hardware.
3) On the top of OS we have applications.

### Now what we can not do with that pc.
1) We cannot work on different environments/operating systems If we want to do then we need to buy those operating systems In the large scale that can cost huge amount of money.
2) Due to the restriction of single OS the efficiency  and productivity are much lower.
To overcome these we had created the concept of virtualisation.

### Concept of Virtualisation .
1) we create complete virtual computers that are not physical and tangible inside our personal computer such that they have the access to share the hardware resources of our pc.
2) We do that with the help of hypervisors(a piece of software such as virtual box). Basically hypervisors communicates with the operating system/hardware to allocate the resources for the created virtual machines.
3) The important thing is every virtual machine is completely isolated so if any error occurred in virtual machine doesn’t effect the host OS which results in higher security.
4) Now we can do anything in that VM and after that we can remove that which saves us lots of time and provides efficiency as VM cannot influence anything related to the original OS.

> Hypervisors are divided into two types, they are..

Type2 hypervisor (or) hosted hypervisor:

- In these types of hypervisors the architecture is
    Hardware->host OS->hypervisor->virtual machine
- These are used by end users to be more concise these are used for a single client by the user.
- These are more user friendly because these types of hypervisors are generally used to create less VM’s hence requires less power overall.

Type1 hypervisor (or) baremetal hypervisor:

- Now these are a bit different and powerful than the first type the main architecture is as follows
    Hardware->hypervisor->virtual machines
- Note here the host OS is missing so that the hypervisor can interact directly with hardware which improves the efficiency and security as there is no host OS in between them and these type of hypervisors are the foundations of cloud computing, on which the present world is depending upon.
- These hypervisors have the power to create large number of VM’s.
- Hence these are used by large scale companies and cloud service providers to provide hardware to various developers as VM’s.
