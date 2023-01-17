# My notebook is a compilation of simple concepts, confusing thoughts, and summaries of essential ideas.  

ON LINUX

Linux History

1969 where Ken Thompson and Dennis Ritchie of Bell Laboratories developed the UNIX operating system. It was later rewritten in C to make it more portable and eventually became a widely used operating system. 
A decade or so later, Richard Stallman started working on the GNU (GNU is Not UNIX) project, the GNU kernel called Hurd, which unfortunately never came to completion. The GNU General Public License (GPL), a free software license, was also created as a result of this.
The kernel is the most important piece in the operating system. It allows the hardware to talk to the software. It also does a whole lot of other things, but we’ll dig into that in a different course. For now, just know that the kernel controls pretty much everything that happens on your system.


Linux powers more than half of the servers on the Internet, the majority of smartphones (via the Android system, which is built on top of Linux), more than 90 percent of the public cloud workload, and all of the world’s most powerful supercomputers.

Linus Distribution Family

The families and representative distributions we are using are: 
• Red Hat Family Systems (including CentOS and Fedora)
• SUSE Family Systems (including openSUSE)
• Debian Family Systems (including Ubuntu and Linux Mint)

Why Distribution

People see a need, and develop special configurations and utilities to respond to that need. Sometimes that effort creates a whole new distribution of Linux. Sometimes, that effort will leverage an existing distribution to expand the members of an existing family!

Linux FIlesystem

A filesystem is a method of storing/finding files on a hard disk (usually in a partition). 
One can think of a partition as a container in which a filesystem resides, although in some circumstances, a filesystem can span more than one partition if one uses symbolic links, which we will discuss much later.

/bin: Linux commands

/boot: Contains files that are not used by the operating system, but by its bootloader

/etc: Additional program and files (Configuration changes)

/lib: C programming library directory

/mnt: Mount directory, usually reserved for mounting filesystems

/opt: Optional add-on applications

/root: Root home directory. It's not the same as /

/sbin: System binaries

/proc: Running process (Tell you the different programs that are running

/tmp: Temporary directory

/home: User directory

/var: Directory for the system logs (where the system logs are created)


