*Lab Report detailing how to remotely connect to a remote dektop to edit and copy files* <br/>

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

Input **ssh cs15lwi22azz@ieng6.ucsd.edu** into your terminal and input your password when asked.
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
scp is a command to copy files from one location to another, in this case, from your desktop to a remote desktop.
The syntax top copy to the UCSD remote desktop is:<br/>
**scp filename cs15lwi22azz@ieng6.ucsd.edu:~/**<br/>
The system will then ask for password after which it will be copied.
Go into the remote desktop and input **ls** and it should show the copied file.
![image](../Photos/scp-success.png)

**5. SSH Key**<br>
Creates a key so password will not need to be inputted everytime we try to access the remote desktop.
Input **ssh-keygen** and a few prompts will appear,enter nothing for default setup for each prompt and then a key will be created.
![Image](../Photos/ssh-key.png)

**6. Extra Tips for Remote Access**<br/>
1. Run commands on server then exit<br/>
  -Use quotation marks with a command (" ") after **ssh cs15lwi22azz@ieng6.ucsd.edu** to run the command on the remote desktop<br/>
2. Semicolons ( **;** ) can be used to combine multiple command in a single line<br/>
3. Up arrow will go through previous commands that you have put in before
![Image](../Photos/extra.png)





