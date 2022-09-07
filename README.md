# Shadow-Vulnerable

Shadow-Vulnerable is a custom operating system written in assembly (FASM) designed to be vulnerable and teach you to think outside the box. This system can be compromised in many different ways if you even compromise it one time you have demonstrated high outside the box capability. Shadow-Vulnerable is part of the larger ShadowSecuritySuite and is designed to teach you to think outside the box and compromise foreign operating systems. Shadow-Vulnerable is made with one rule: Forget about all security in operating system development. We also provide internet access and allow you to harden the system to see how well it defends against threats. Baremetal is not supported, use this operating system in virtual machines. This project should also teach you that in security you do not need to think hard about making something vulnerable, defending is the hard part.

㊙️ "The more silent you are, the more you can silence." ㊙️

# Warning:

Treat this operating system as already compromised otherwise you likely will get infected.

# Why did we write the entire project in assembly?

Because we believe writing the entire thing in assembly would make it the most vulnerable and abstract due to being able to make more mistakes than higher level languages, therefore making it more vulnerable and also because this is a learning project for us. There is also another aspect we value, speed and while speed may not be the most important value in a vulnerable system it can make the difference in a low level attack as having speed in attacks allows you to work faster and smarter. Why did I not write this in machine code? I did not write this in true machine code because it offers little speed benefits over assembly.

# THANKS TO:

💖 Made possible thanks to these projects 💖

```
https://github.com/
https://git-lfs.github.com/ (git lfs track "./**" && git add .gitattributes && git add .gitignore && && https://stackoverflow.com/questions/63301080/how-can-i-fix-git-bash-not-working-on-windows && git pull --rebase && https://git-scm.com/docs/git-rebase)
https://kolibrios.org/en/ && http://websvn.kolibrios.org/listing.php?repname=Kolibri+OS (Fetched over http to lower security) (Our Operating System Base, chosen because it is fully FOSS.) (We periodically update to upstream every 5 years to ensure maximum vulnerability, we also allow internet access so disconnect the network driver from the VM if you think you will get main network compromised or isolate, every 5 years we also do a full FASM machine code rebase.)
https://tortoisesvn.net/ && svn://kolibrios.org
https://wiki.osdev.org/Main_Page
https://www.reddit.com/r/osdev/
https://www.vulnhub.com/ (Like DVL but has more operating systems) (Community supported, so do not trust everything)
https://flatassembler.net/ (What our operating system is wrote in)
https://mh-nexus.de/en/hxd/ (Hexadecimal Editor)
https://www.gitkraken.com/
```
# Requesting a feature

If you would like a feature to be added to Shadow-Vulnerable please request it by opening a issue on GitHub and explaning why it would be of use to the project.

# DISCLAIMER

BY USING THIS SHADOWSECURITYSUITE YOU AGREE TO THE LICENSES OF THIS PROJECT AND/OR THE LICENSES OF THE OTHER PROJECTS INCLUDED IN SHADOWSECURITYSUITE. BY USING SHADOWSECURITYSUITE YOU HEREBY AGREE THAT YOU ARE RESPONSIBLE FOR YOUR ACTIONS WITH SHADOWSECURITYSUITE AND WILL BE PUNISHED ACCORDINGLY IF UNETHICAL ACTS ARE WITHDRAWN FROM USING THIS SUITE. 

Copyright (c) 2022 CY83R-3X71NC710N
