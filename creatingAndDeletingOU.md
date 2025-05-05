# Creating and Deleting Organizational Units
### Description: 
In Active Directory, a Container is a structural object used to organize objects, while an Organizational Unit (OU) is a specific type of container that can have Group Policy objects (GPOs) applied to it. Containers are used for grouping objects, while OUs are used for applying policies and managing delegated administration. 

![Image](https://github.com/user-attachments/assets/6ca0b7b9-4bfc-4871-8d91-8370aa1a5d85)

## Project Walkthrough:
1. Select your OU. In my case, it is called Server Academy.
2. Right-click the OU, and select New > Organizational Unit.

![Image](https://github.com/user-attachments/assets/f523a88f-7b9c-4213-b145-f330c2723b8a)

3. Name the OU "Disable Users". This will be used for the next project.
4. Check the box that says "Protect container from accidental deletion."

![Image](https://github.com/user-attachments/assets/975106ae-6e01-4665-8555-2b5ad08118a3)

The OU should be created.<br>

If you right click on the OU you have created, and click on **delete**, you will receive an error message saying that you do not have permission or that the OU is protected from accidental deletion. To bypass this, you must do the following: 

5. Select View and turn on Advanced Features.

![Image](https://github.com/user-attachments/assets/dfe9c4ce-073a-41b6-960d-b7f355170c7c)

6. Re-navigate over to the Disabled Users folder, right-click and choose Properties.
7. Under Object and uncheck "Protect this object from accidental deletion."
8. Click on **Apply**

![Image](https://github.com/user-attachments/assets/55429406-5fbd-47c3-9b7c-a62261c10fa9)

Now you are able to delete the OU folder!
