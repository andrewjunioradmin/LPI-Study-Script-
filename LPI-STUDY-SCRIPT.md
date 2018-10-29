# LPI-Study-Script-
#!/bin/bash
## This script is a SysAdmin aptitude audit 

echo "Kenneth Withrow is the greatest, thanks Dad"

echo -e "How do you find disk space used?: "
read name

if [[ $name = "du" ]]; then
          echo "Correct"
else
	  echo "Error du is the the command for finding used disk space"
fi

echo -e "How do you edit user quotas?: "
read name

if [[ $name = "edquota" ]]; then
	   echo "Correct"
else
	   echo "Error edquota is the command for editing user quotas"
fi

echo -e "How do you display info on hardware?: "
read name

if [[ $name = "hwinfo" ]]; then
	    echo "Correct"
else
            echo "Error it's hwinfo"
fi

echo -e "How do you half  one large file into two?:"
read name

if [[ $name = "split" ]]; then
	    echo "Correct"
else
            echo "Negative it's split"
fi

echo -e "How are two lines of text put on the same field?:"
read name

if [[ $name = "join" ]]; then
	    echo "Correct"
else
	    echo "Nah it's join"
fi

echo -e "What is executed with a job to avoid it being killed on shutdown:"
read name

if [[ $name = "nohup" ]]; then
	    echo "Correct"
else
	    echo "Wrong it's nohup"
fi

echo -e "How do you uncompress a file that was compressed by gzip?:"
read name

if [[ $name = "gunzip" ]]; then
	    echo "Correct"
else
	    echo "Negative it's gunzip"
fi

echo -e "How do you display the end of a text file?:"
read name

if [[ $name = "tail" ]]; then
	   echo "Correct"
else
	   echo "Negative it's tail"
fi

echo -e " How would you interpret special characters?:"
read name

if [[ $name = "file globbing" ]]; then 
	   echo	"Correct"
else
	   echo " dude no it's file globbing"
fi

echo -e "How do you convert space characters to tab characters?:"
read name

if [[ $name = "unexpand" ]]; then
	    echo "Correct"
else
            echo "Nope, its unexpand"
fi

echo -e "How would you manipulate partitions?:"
read name

if [[ $name = "parted" ]]; then
	    
	echo "Correct"
else
	    echo "Negative parted would be your answer"
fi

echo -e "How do you specify runlevels and enable with chkconfig?:"
read name

if [[ $name = "sysvinit" ]]; then
	
	echo "Correct"
else
	echo "Negatory sysvinit is the command"
fi

echo -e "How would you load the initial ramdisk from a file?:"
read name

if [[ $name = "initrd" ]]; then
	
	echo "Correct"
else
	echo "Nah initrd my guy"
fi

echo -e "How would you show files to all logged in users pre shutdown"
read name

if [[ $name = "wall" ]]; then
	
	echo "Correct"
else
	echo "False tis wall command"
fi

echo -e "This particular systems target decides the system state and uses systemctl to start:"
read name

if [[ $name = "systemd" ]]; then
        
	echo "Correct"
else
	echo "Nope systemd"

fi

echo -e "How would you print system environment variables or run a utility?:"
read name

if [[ $name = "env"]]; then
	
	echo "Correct"
else
	echo "Nein ist env"

fi

echo -e "How will you delete variables in program execution?:"
read name

if [[ $name = "unset" ]]; then
	
	echo "Correct"
else
	echo "Negative boyo tis unset"
fi


echo -e "How will you display info on ext2/ext3/ext4?:"
read name

if [[ $name = "dumpe2fs" ]]; then
	
	echo "Correct"
else
	echo "Negative tis dumpe2fs"
fi

echo -e "How is the OS able to talk to the hardware?: "
read name

if [[ $name = "linux driver" ]]; then
	
	echo "Correct and is more secure if compiled to linux driver"
else
	echo "Negative its the linux driver"
fi

	 	 

echo -e "How do you enable disk quotas?"
read name

if [[ $name = "quotaon" ]]; then
	
	echo "Correct for the users"
else
	echo "Negative its quotaon"
fi

echo -e "How do you print shared library dependencies?:"
read name

if [[ $name = "ldd " ]]; then
	
	echo "Correct"
else
	echo "Negative its ldd "
fi


echo -e "What is the parent of all linux processes?:"
read name

if [[ $name = "init" ]]; then
	
	echo "Correct"
else
	echo "Negative its init"
fi


echo -e "How would you install or build packages?: "
read name

if [[ $name = "dpkg" ]]; then
	
	echo "Correct"
else
	echo "Negative tis dpkg"
fi

echo -e "How would you display info on all usb devices:?"
read name

if [[ $name = "lsusb" ]]; then
	
	echo "Correct"
else
	echo "Negatory its lsusb"
fi

echo -e "How do you compress single files without archiving ?:"
read name

if [[ $name = "bzip2" ]]; then
	
	echo "Correct"
else
	echo "No its "
fi


echo -e " How do you print the summary of disk usage?:"
read name

if [[ $name = "repquota" ]]; then
	
	echo "Correct"
else
	echo "No its repquota"
fi


echo -e "How do you show current partition tables?:"
read name

if [[ $name = "fdisk" ]]; then
	
	echo "Correct with a dash l"
else
	echo "No its fdisk "

fi

echo -e "How do you set hardware time to system time?:"
read name

if [[ $name = "hwclock -w" ]]; then
	
	echo "Correct"
else
	echo "No its hw clock -w "
fi

echo -e "How do you show current hw clock time?:"
read name

if [[ $name = "hwclock -r " ]]; then
	
	echo "Correct"
else
	echo "No its hwclock -r "
fi

echo -e "How do you print documents from cli?:"
read name

if [[ $name = "lp -d" ]]; then
	echo "Correct"
else
	echo "No its lp -d"
fi
echo -e "how do you find stream editor ?:"
read name

if [[ $name = "sed" ]]; then
	
	echo "Correct"
else
	echo "No its sed dummy "
fi


echo -e "How do you search process based on name?:"
read name

if [[ $name = "pgrep" ]]; then
	
	echo "Correct"
else
	echo "No its pgrep"
fi

echo -e "How do you cancel a print job?:"
read name

if [[ $name = "lprm" ]]; then
	
	echo "Correct"
else
	echo "No its lprm "
fi

echo -e "How do you see what process is running?:"
read name

if [[ $name = "ps" ]]; then
	
	echo "Correct"
else
	echo "No its ps"
fi

echo -e "How do you check disk designed for ext2?:"
read name

if [[ $name = "e2fsck" ]]; then
	
	echo "Correct"
else
	echo "No its e2fsck"
fi

echo -e "How do you make data human readable?:"
read name

if [[ $name = "od" ]]; then
	
	echo "Correct"
else
	echo "No its od for octal dump "
fi

echo -e "How do you ensure variables in the parent process are in the child process?:"
read name

if [[ $name = "export" ]]; then
	
	echo "Correct"
else
	echo "No its export"
fi

echo -e "How do you get more info on a module?:"
read name

if [[ $name = "modinfo" ]]; then
	
	echo "Correct"
else
	echo "No its modinfo.. "
fi

echo -e "How do show loaded modules?:"
read name

if [[ $name = "lsmod" ]]; then
	
	echo "Correct"
else
	echo "No its "
fi

echo -e "How do you convert files from standard input to standard output?:"
read name

if [[ $name = "cpio" ]]; then
	
	echo "Correct"
else
	echo "No its cpio cheif.. "
fi

echo -e "How do you print documents from cli?:"
read name

if [[ $name = "lp -d" ]]; then
	
	echo "Correct"
else
	echo "No its lp -d"
fi

echo "ssh does the following..."
sleep 2

echo "Allows remote access to terminals..."
sleep 2

echo "Requires authentification..."
sleep 2

echo "Allows forwarding of x server windows..."
sleep2



echo -e "What program loads the OS?:"
read name 

if [[ $name = "boot loader"]]; then

	echo "Correct"
else
	echo " Its the boot loader not the kernel"

fi

echo -e "How do you format text files that are human readable?:"
read name

if [[ $name = "fmt" ]]; then

	echo "Correct" 
else 
	echo "Nope it is actually fmt"

fi

echo -e "What programs don't detach?:"
read name

if [[ $name = "jobs" ]]; then

	echo "Correct"
else
	echo " Incorrect it is jobs"

fi

echo -e "How do you check ports?:"
read name

if [[ $name = "netstat -t" ]]; then

	echo "Correct"
else
	echo "Incorrect it is netstat -t"

fi

echo -e "How do you find the manual for various commands?:"
read name

if [[ $name = "man" ]]; then

	echo "Correct or --help"
else
	echo "Incorrect dude, man for man pages"

fi

echo -e "How do create a symlink or softlink?:"
read name

if [[ $name = "ln -s" ]]; then

	echo "Correct,example, ln -s ./libdonlibrary.so.5.3"

else
	echo "Incorrect its ln -s"

fi

echo -e "How do you create a hardlink?:"
read name

if [[ $name = "ln" ]]; then
	
	echo "Correct, hardlinks point to directly to data on the hard drive"
else
	echo "Incorrect, its ln, example ln /sbin/fsck ~/fsck"

fi


echo -e "How do you list current libraries?:"
read name

if [[ $name = "ldconfig -v" ]]; then
	
	echo "Correct"
else
	echo "Incorrect its ldconfig -v my guy"

fi

echo -e "How do you check library dependencies"
read name

if [[ $name = "ldd" ]]; then

	echo "Correct"
else
	echo "Incorrect, its ldd , example lld /bin/bash or ldd /bin/vim"

fi


echo "ld.so.conf.d/ to see third party libraries"

echo " Use the touch command to create an empty library that software can link to"

echo "Devops relies heavily on shared links for pre written code. This way they don't have to stat from scratch"
sleep 4

