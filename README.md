Download Link: https://assignmentchef.com/product/solved-csc3320-lab-1-part-1-and-2
<br>
<span class="kksr-muted">Rate this product</span>

Purpose: Learn how to use a terminal emulator PuTTY to control the sever remotely. Review the commands to get a Java program run.

Part A: Get connected to the server in PuTTY using SSH.(1) Download PuTTY under following link. https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html

Note:If your windows system is 32-bit version, please download the 32-bit putty.exe instead.

(2) Go to Desktop and start PuTTY by double-clicking its icon.

(3) When a window of PuTTY shows up, select the Session from the Category panel on the left. In the Host Name field enter the server name“snowball.cs.gsu.edu”. In the Post field keep the default setting “22”. Select SSH

as the Connection type. Click on Open.

<table>

 <tbody>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

 </tbody>

</table>

(3) In the new dialog box enter your username and password.

Note:

<ul>

 <li>The username is your campus ID and the password is the password for your campus ID, which is used to log into your PAWS.</li>

 <li>When you finish typing, press “Enter”.</li>

 <li>When entering the password, you will not see the password on the screen. So make sure that you are typing the correct password.</li>

</ul>

(4) When the following window pops up for the Public Key User Authentication, hit YES.

(5) Once you see the prompt “$”, you are connected to the server.

(6) Attach a screenshot like in the figure of step (5) to show that your connection to snowball server has succeeded. Name your screenshot file as

L1_P1_ FirstnameLastname.png (or .jpg). E.g. L1_P1_FilRondel.png Note : Screenshot shortcut in Mac OS cmd + shift + 4; in Windows use snipping tool.

Purpose: Know how to install a Unix system in a virtual machine. Part A: Environment Configuration for Unix system.

Install a virtual machine and Ubuntu in your operating system. x For Windows users, please follow guide VirtualBox and Vmware Player.

x For Mac users, please follow guide VirtualBox

Part B: Test your SSH connection in Ubuntu(1) Log in to your Ubuntu system, and open “Terminal”.

Click Dash Home and search “Terminal”. Then select “Terminal” and open it. In “Terminal”, use command ssh to connect server snowball.cs.gsu.edu.

Ssh <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="c0a3a1adb0b5b389a480b3aeafb7a2a1acaceea3b3eea7b3b5eea5a4b5">[email protected]</a>E.g. my camps Id is frondel1, so I use ssh <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="680e1a07060c0d0459281b06071f0a090404460b1b460f1b1d460d0c1d">[email protected]</a>

Note:You can also refer to the video under link belowFor Mac OS https://www.youtube.com/watch?v=_42JLz2izBU For Windows https://www.youtube.com/watch?v=ncA85gRAJxk

Note:1. Your password for camps Id should be the password for this server.2. If the server warns you that the authenticity of host cannot be established and ask you if you

want to continue connecting, please enter “yes”.3. Remember to hit “Enter” once you input the command after the prompt ‘$’.

(3) Attach a screen shot like following figure in your report. Name your screenshot file as L1_P2_ FirstnameLastname.png (or .jpg). E.g. L1_P2_FilRondel.png

This figure includes your “terminal” and ssh connection.

Note : Screen shot short cut in Mac OS, command + shift + 4; in windows, use key PrintScreen.

Submission:• Upload the screenshots required in Part B to Google Classroom.

Appendix:To check the ssh connection

x For a Mac user, you can also try the utility “Terminal” in Mac OS.

x For a Windows user, you can also try the terminal emulators, e.g. PuTTY, Xshell . Note: In the connection configuration, host name is snowball.cs.gsu.edu, login account name is your campus Id, protocol is ssh, and port is usually 22.

Useful links:1. Download Xshell