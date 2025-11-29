# Adventures-SysAdmin_automation_sec_tasks

# Project Overview
Discover/learn/practice a select method to automate several essential IT security activities routinely performed by System Administrators (SysAdmins). Create an environment between multiple virtual machines (VMs), designating one as the SysAdmin workstation. This will be Windows based as it is often perceived as having a graphical user interface/ operating system (OS) that is more user friendly. While the remaining VMs that will be targeted by the automated tasks use Ubuntu, a distribution of Linux, based OS.   

# Project Relevance
Exploring how environments (physical, cloud, or hybrid setups) are created and connected is an imperative skillset in today’s Information Technology/Cybersecurity arena. Lack of understanding for how things connect, and function complicates the ability of IT security professionals to secure critical systems and networks. As the attack surface has increased over time it is not enough to rely on one type of security measure, such as perimeter defense (Firewall). Today’s workplaces operate within or touch global cyberspaces that are ever changing and unsecure. There is the need to leverage multiple modalities to defend and protect systems by combing perimeter defense, limited access as only needed, real time intrusion/ anomaly detection, and monitoring processes that compile logs routinely.     

# Methodology

- **Tools:**  VirtualBox-7.2.4, Oracle_VirtualBox_Extension_Pack-7.2.4, Windows 10 ISO, Ubuntu 24.04.3 (64-bit) ISO, Windows Powershell ISE, Bash (commands & scripts), RDP (Remote Desktop Protocol), WSL (Linux)

- **Environment Setup:**  Using RDP via PowerShell cmdlets the SysAdmin VM remotely connects to the FariyLand VM and the DwarvesLand VM.   

- [Process Steps](https://github.com/mwlibrarian/

# Results
Not a success in the ability to fully realize the intent for this project. However, it was a deeply interesting opportunity to explore areas in Windows (areas within the Windows Security settings, Firewall settings, lesser known areas beneath the surface of the Control Panel settings) and Ubuntu (exploration of WSL in Windows to use a Linux distro), plus a lot closer look at ports and ip addressing while attempting methods for connecting remotely. Therefore, the absolute end result was a good learning experience with plenty of "food for thought" and questions to spur more learning adventures for System Administration tasks specifically those for securing virtual environments.


# Conclusion
After multiple configuration missteps, the VMs were able to function and interact for the purpose of this project. While there are several other ways and more efficient ways to automate SysAdmin tasks, such as using “Ansible.” This project was an invaluable opportunity for learning via trials and errors the fundamentals for setting up, testing, starting setup again, testing more, and finally achieving a somewhat acceptable end that at least was an advancement of prior knowledge.

Some of the hardest parts of this project were narrowing what to focus problem-solving and research on when things did not work as anticipated. Beyond using class notes, slides, and recommended readings; there are numerous resources (Microsoft, Oracle, Ubuntu, along with others with hit-or-miss legitimacy/accuracy) available online. However, it is difficult to know what to trust outside of official sites when exploring the topics needed in this project. Something posted on “Stack Overflow” or “Geeks for Geeks” does not mean it is always useful or correct. However, to keep the project progressing past each project dooming dysfunctional roadblock, the afore various resources were used. Ultimately this took exponentially more time than planned for to construct and execute the cmdlets and bash scripts for automation, thus the project scope shrank accordingly and narrowed a lot.    
