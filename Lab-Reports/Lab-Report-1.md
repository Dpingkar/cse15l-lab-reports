*Lab Report detailing how to remotely connect to edit and copy files* <br/>

**1. Install and get certain things**<br/>
1. **VSCODE**<br/>
 Download on [link](https://code.visualstudio.com/)<br/>
 After installation, should get:![image](../Photos/vscode.png)
2. **JAVA**<br/>
Download latest version of JDK on Oracle
3. **OpenSSH**<br/>
In **Apps --> Optional Features**. Search for OpenSSH CLient and Open SSH Server
4. **Username**<br/>
Open this [link](https://sdacs.ucsd.edu/~icc/index.php) to get the course specific username for cse15Lwi22azz@ieng6.ucsd.edu (zz will be different for each person)

**2. Connecting to Host**<br/>

Input **ssh cse15lwi22azz@ieng6.ucsd.edu** into your terminal and input your password when asked.
You will see this once you are successfull:
![Image](../Photos/ssh-success.jpg)<br/>
To exit the remote desktop, input **exit** or **logout**

**3. Commands to know**<br/>

1. **ls** - list down files and folders in directory
2. **pwd** - prints out path to current location
3. **cd** - change directory: <br/>
   1. **..** - change to parent directory
   2. **~** - change to home
   3. **(folder name)** - change to folder specified
4. **mkdir** - make new directory with name after the command

**Photo of ouput of ls and pwd**<br/>
![image](../Photos/commands.png)

**4. SCP**<br/>
scp is a command to copy files from one location to another, in this case from your desktop to a remote desktop.
The syntax top copy to the ucsd remote desktop is:<br/>
**scp filename cse15lwi22azz@ieng6.ucsd.edu:~/**<br/>
The system will then ask for password and a successfull copy will show:<br/>

**5. SSH Key**





