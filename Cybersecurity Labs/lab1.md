Cybersecurity home lab 

1.	Retrieve available updates

    ![updates](./images/1.png)
2.	Upgrade the System
    ![upgrade](./images/2.png)
3.	Reboot the VM
    ![reboot](./images/3.png)

USER TASKS:
4.	Switch to the root user

    ![root](./images/4.png)
5.	Create new users(useradd vs adduser)
    ![useradduser](./images/5.png)
6.	Switch to the user dog
 ![switch](./images/6.png)

7.	Attempt to create a new user logged in as user – dog
![newuser](./images/7.png)
 

8.	Return to my main account and delete user – cat
![deluser](./images/8.png)
 

9.	Change the password for user – dog

 ![passwduser](./images/9.png)

10.	Why staying logged in as root is bad practice
a.	The root user can execute destructive commands without confirmation
b.	High risk of accidental system damage
c.	Violates least-privilege security standards

11.	Command to see user id

 ![userid](./images/11.png)

GROUP  TASKS

12.	View Groups

 ![groups](./images/12.png)

13.	Giving user – dog sudo privileges and switching into the account

 ![sudo](./images/13.png)

14.	Creating a new group called cybersec

 ![group](./images/14.png)

15.	Add user – dog to the cybersec group
 ![group](./images/15.png)

16.	Checking what groups does user – dog belong to  

![groups](./images/16.png)

17.	Creating a new directory and checking permissions

 ![newdir](./images/17.png)

18.	Creating a bash script called helloworld

 ![BASH](./images/18.1.png)
 ![SCRIPT](./images/18.2.png)

19.	Checking file permissions and changing the permissions so that even the group has write and execute permissions	
 ![ACL](./images/19.png)

20.	Viewing Access Control Lists of the file using getfacl

 ![getfacl](./images/20.png)

21.	Giving user – dog permission to read and write using setfacl
 
![setfacl](./images/21.png)
