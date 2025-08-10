In this activity, I learned about Amazon EC2, which is basically a virtual computer that runs in the cloud.
Instead of having a physical computer in front of me, AWS gives me a server that I can control completely, but it’s stored in their data centers.
I can start it, stop it, restart it, or even delete it whenever I want.
The main idea of EC2 is that it works like a normal computer, but it is flexible.
I can choose what operating system it has (Linux, Windows, etc.), how powerful it should be (more CPU, more RAM, etc.), and how much storage it needs.
AWS charges based on how much I use it, but there is also a Free Tier that allows beginners like me to try it without paying (for limited resources).
While learning EC2, I understood some important concepts:
AMI (Amazon Machine Image): This is like a template for my instance. It decides the operating system and base software installed.
Instance Type: This is where I choose the hardware power for my virtual machine. For example, t2.micro is small but free.
Key Pair: A special file that acts like a password, but more secure. It is needed to connect to the instance using SSH (for Linux) or RDP (for Windows).
Security Group: Works like a firewall that controls what kind of network traffic is allowed into my instance. For example, I can allow HTTP for websites or SSH for remote login.
Elastic IP: A static public IP that I can attach to my instance so it has the same address even after restarting.
Stopping vs. Terminating: Stopping pauses the instance (and I can start it again), while terminating deletes it permanently.
Overall, I learned that EC2 is very powerful because I can create and configure servers quickly without worrying about buying hardware.
It is very useful for hosting websites, running applications, or even experimenting with programming and networking.
