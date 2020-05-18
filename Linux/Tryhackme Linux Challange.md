# Questions with  Answers Of The linux Challange
-------------------------

## TASK 1
**Linux Challenges Introduction** 
1. How many visible files can you see in garrys home directory? 
    
     _flag = 3_

## TASK 2

**The Basics**

- This set of tasks will go over the basic linux commands.
Each question might require you to switch between another user to find the answer!

1.   What is flag 1?

     _flag = f40dc0cff080ad38a6ba9a1c2c038bb2c_

<!-- username =bob password = linuxrules -->
2.   Log into bob's account using the credentials shown in flag 1.
What is flag 2 ?

     _flag = e255dfa51c9cce67420d2386tcede596_

3.   Flag 3 is located where bob's bash history gets stored.
   _flag = 9daf3281745c2d75fc6e992ccfdedfcd_
4.  Flag 4 is located where cron jobs are created.
      
       _flag = dcd5d1dcfac0578c99b7e7a6437827f3_
5. 	Find and retrieve flag 5.
     <!-- 
     /lib/terminfo/E/flag5.txt -->
    _flag = bd8f33216075e5ba07c9ed41261d1703_

6. "Grep" through flag 6 and find the flag. The first 2 characters of the flag is c9.
_flag = c9e142a1e25b24a837b98db589b08be5_
<!--/home/flag6.txt  
command = grep c9 flag6.txt -->

7. Look at the systems processes. What is flag 7.
    
    _flag = 274adb75b337307bd57807c005ee6358_
<!-- command = ps -aux 
output = root     1389  0.0  0.0   6008   312 ?        
S    17:07   0:00 flag7:274adb75b337307bd57807c005ee6358 1000000
 -->
 8. De-compress and get flag 8.

    _flag = 75f5edb76fe98dd5fc9f577a3f5de9bc_
 <!--tar -xf flag8.tar.gz
 flag8.txt = 75f5edb76fe98dd5fc9f577a3f5de9bc
 -->

9. By look in your hosts file, locate and retrieve flag 9.
 
    _flag = dcf50ad844f9fe06339041ccc0d6e280_

<!--to find it hosts file you can use it the "find " command.-->

10. Find all other users on the system. What is flag 10.
    _flag = 5e23deecfe3a7292970ee48ff1b6d00c_
    <!-- users information located at etc/passwd -->


## TASK 3

**Linux Functionality**

1. Run the command flag11. Locate where your command alias are stored and get flag 11.

    _flag = _







