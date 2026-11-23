# Day 14

**What I did:** Got Ubuntu 24.04 LTS running under WSL 2.

**What confused me:** The install and dism commands kept failing. The cause turned out to be virtualization being off in the BIOS. [Confirm.]

**What worked:**
- Enabled the Virtual Machine Platform feature
- wsl -l -v shows Ubuntu running, version 2
- Logged into Ubuntu 24.04 LTS

**What I noticed:** The prompt ends in #, so I'm logged in as root. A normal user is the safer way to work.

**Next:** Create a normal user. Go through the recorded Linux class and practice the commands.
