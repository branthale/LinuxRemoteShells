# LinuxRemoteShells

This is a collection of Linux Remote Access Shells.  It is primarly to study for the OSCP, but I want to share my progress and thoughts on the process.   As a secondary goal, I am working to extend my toolset for REDTEAM exercises specifically for the long haul APT type of group.  I am hoping to create a complement to the very useful Cobalt Strike application https://www.cobaltstrike.com/

I plan to start with netcat and ncat and have them interact with metasploit.  This may be very basic, but I feel it is a good place to start.

elf_shell.sh    is a small bash script to take input and use msfvenom to create the ELF executable to call a netcat listner
                I created this to test variable passing to bash in anticipation of a more robust tool.
