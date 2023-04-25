# Installing VScode
Go to visual studio code website [https://code.visualstudio.com/](https://code.visualstudio.com/) and download the latest stable build. Afterwards, open what 
you downloaded and following the installation instructions. 

* Download the most recent stable build by clicking in the box marked in red.
![img](Screen Shot 2023-04-24 at 9.17.52 PM.png)
* Next, extract the application from the zip file you just download and run it.
* You're done, VSCode should set up the default environment automatically!

Aftewards your VSCode should look like this 
![img1](Screen Shot 2023-04-06 at 2.25.19 PM.png)

# Remotely Connecting

* If you're using Windows, install [git bash](https://gitforwindows.org/), then follow the instructions [here](https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal/50527994#50527994) to use git bash in your VScode
  * Open VSCode, if not opened already, and press and hold `ctrl` + ` to open the terminal
  * Then open the command drop down menu by using `ctrl` + `shift` + `p`
  * Type - `Select Default Profile`
  * Select Git Bash
  * Then click on the `+` icon from the terminal window on the bottom right.
  * ![img10](Screen Shot 2023-04-24 at 9.25.36 PM.png)
  * The dropdown next to the `+` icon should say bash, and you can swap between zsh, powershell, bash anytime.


* Then, to connect to the UCSD computers: first open your terminal and type in the text below.
  1. `ssh` + `your cse15 account name` + `@ieng6.ucsd.edu`. As an example `ssh cs15lsp23kq@ieng6.ucsd.edu` 
  2. It will prompt you to say (yes/no/[fingerprint])? Type `yes`
  3. Then type in your password

It should look like this

![img2](Screen Shot 2023-04-06 at 3.32.14 PM.png)

After you've inputted your password correctly, this should appear. You're in!
![img3](Screen Shot 2023-04-06 at 3.32.37 PM.png)

Error:
If you receive this error message, inquire your TA about this. This is completely beyond your ability.
![img4](Screen Shot 2023-04-06 at 3.38.57 PM.png)


# Trying Some Commands

Afterwards, you can some of these commands on your **personal computer** and the **remote computer**

* cd ~
* cd
* ls -lat
* ls -a
* ls <directory> where <directory> is /home/linux/ieng6/cs15lsp23/cs15lsp23abc, where the abc is one of the other group members’ username
* cp /home/linux/ieng6/cs15lsp23/public/hello.txt ~/
* cat /home/linux/ieng6/cs15lsp23/public/hello.txt
  
Then, to log out of the remote computer on your personal computer's terminal
  
* Ctrl D
* type "exit"
