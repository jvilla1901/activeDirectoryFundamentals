# Creating Active Directory Users 
### Before we get started: 
Before we get started, I highly recommend checking out my other lab to create an on-premise lab so you can make a virtual machine and install Windows Server (2016-2022) on your current computer and practice Active Directory. The link to the lab would be right here!<br>
<br> Big shout-out to Server Academy, which is where I learn Active Directory. I have downloaded their presets of a domain, domain names, and users. Unfortunately, I cannot provide the presets. However, I am planning to make a tutorial on how to add thousands of fake Users and create domains so you can simulate working in a big organization with lots of employees. </br>
## Lab Walkthrough: 
1. Open up Server Manager

![Image](https://github.com/user-attachments/assets/ad1832a9-e67e-4184-9314-3cc13d08f624)

2. Select Tools in the top right-hand corner of the screen and we are going to select Active Directory Users and Computers.

![Image](https://github.com/user-attachments/assets/4cfd135f-d75d-49be-9967-6cba8939930d)

3. Select the domain. In my case, it is called "ad.serveracademy.com".
4. Select the organizational unit, (or OU), that you want to add users. In my case, it is called "Server Academy".
5. I will create a new user in the Domain User folder so I will click on "Domain Folder".

![Image](https://github.com/user-attachments/assets/52ac1674-f365-4856-b6b9-abf1227768d6)

6. Right-click on the OU and choose New User. Or we can right-click once we've opened the Organizational Unit and select New User.

![Image](https://github.com/user-attachments/assets/ce553a48-50e5-4fb5-b51a-019f21f8a95c)

7. A new pop-up will appear, and what we will do here is just type in the user's information. I will use my instructor's name from Server Academy, so that will be Paul Hill, and we'll call it paul.hill as the username.

![Image](https://github.com/user-attachments/assets/b2fe420a-a0a8-4899-8d25-89ad6f427868)

8. Once I've done that, I am going to go ahead and click Next and I’ll type and confirm the password here. (*creating an account and having it disabled is a good practice because if the account is created but not immediately needed, someone could log in before it's properly configured*)

![Image](https://github.com/user-attachments/assets/f45bd458-b27f-4be5-97ee-fc366d9e031c)

9. You will get a pop-up summarizing the new User you just created. Click Finish. <br>
<br> You should see the new User on the OU you haved picked. </br> 
<br> Don't forget we have disable the new account, let's enable the account! </br>

10. Right click the new user, then click "Enable Account"

![Image](https://github.com/user-attachments/assets/15befbf5-946f-4241-95cb-9d1958ae58da)

That is all we have to do to create users on Active Directory! 
