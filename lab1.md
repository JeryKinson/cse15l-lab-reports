# Report for Lab 1

##Written by *Kinson Liang*


**1. Installing Vscode**
<br />
Go to google and try to search VScode. Then download the VScode from the offical website. Also install it on you local desktop.
<img width="1015" alt="Screen Shot 2022-04-09 at 16 58 49" src="https://user-images.githubusercontent.com/46670042/162647618-575629f1-4375-46b6-b583-d9eef9941ea1.png">
<img width="513" alt="Screen Shot 2022-04-10 at 17 46 02" src="https://user-images.githubusercontent.com/46670042/162647892-63853686-0702-461f-bb85-2ec8e63f3ebe.png">
<br /><br /><br /><br />

**2. Remotely Connecting**
<br />
First you need to get your remote access account. On windows we also need to install OpenSSH. Then open the terminal on your laptop or search it. Since we need to use SSH to get remote access so try to type in the command *ssh xxx(your account name)@ieng6.ucsd.edu*.
<img width="575" alt="Screen Shot 2022-04-10 at 17 47 44" src="https://user-images.githubusercontent.com/46670042/162648062-ded4f71a-e3c1-4938-a49d-0bf1d28a87a0.png">
<br /><br /><br /><br />

**3. Trying Some Commands**
<br />
After we are on the remote access to our account, try some common commands which are very useful. Like *cd* or *cd..*, this command will lead you move to a child directory or back to a parent directory. And also *ls* or *ls -a* will show the list of the file or the list including the hidden file. Other commands you may try like *cat*, *touch*, *rm*, *cp* and so on.
<img width="630" alt="Screen Shot 2022-04-10 at 17 47 55" src="https://user-images.githubusercontent.com/46670042/162648071-9af99c74-2606-4083-a67e-8cead3ca7766.png">
<br /><br /><br /><br />

**4. Moving Files with scp**
<br />
I tried to do the compile on my desktop and the server both. And we could see since all the information printed is from the System where it compiled the java file. Since I compiled it on my mac and the server of the school, I got different user systems, user names and different paths from my laptop and the server.
<img width="627" alt="Screen Shot 2022-04-10 at 17 48 08" src="https://user-images.githubusercontent.com/46670042/162648088-32c49012-6b20-413d-af45-ab1c42836a4c.png">
<br /><br /><br /><br />

**5. Setting an SSH Key**
<br />
We need to use the command ssh-keygen to copy the public key to the server and a private key on the client. After that, the ssh command will help you use the pairs of the password so that we do not need to type in the server password each time.
<img width="574" alt="Screen Shot 2022-04-10 at 17 48 21" src="https://user-images.githubusercontent.com/46670042/162648101-15e4072e-290c-4824-9e8f-d4d479afd66b.png">
<br /><br /><br /><br />

**6. Optimizing Remote Running**
<br />
The point is that we need to know use *;* to let the terminal excute mutiple commands at the same time. When we excute on a ssh command, remember to add "xxx(command)". And after excute the commands, the terminal will log out the server automatically.
<img width="697" alt="Screen Shot 2022-04-10 at 17 54 04" src="https://user-images.githubusercontent.com/46670042/162648327-91d6bea0-ba42-4834-8c86-e61b23df3e16.png">
<br /><br /><br /><br />
