# osTicket-Working-a-Ticket


<h2>Description</h2>
This project demonstrates how you would create a ticket from a user's perspective and how to work a ticket from an agent's perspective.


<h2>Languages and Utilities Used</h2>

- <b>osTicket</b>


<h2>Environments Used </h2>

- <b>Windows 10 Pro</b> 

<h2>Program walk-through:</h2>

<p align="center">
Once you log in, navigate to the top right corner and make sure you are in the Admin panel, if you can see "Agent Panel" then that means you are in the Admin panel. Click  <br/>
  
![image](https://github.com/user-attachments/assets/d238d96a-8344-452c-9fb6-2ce95a4a4f49)







<br />
<br />


Once you get to this window, select "add features" and keep the box checked that says "include management tools," then click next. <br/>

![image](https://github.com/user-attachments/assets/fb60a298-32fb-442e-98a6-f762486109fb)





<br />
<br />


Confirm installation selections and allow automatic restarts. Check the box that shows "Restart the destination server automatically if required.":  <br/>

![image](https://github.com/user-attachments/assets/8bc14b8e-2dbd-42bf-9bd6-258719bed652)




<br />
<br />
The Installation process will then start, wait a few moment for it to complete.   <br/>

![image](https://github.com/user-attachments/assets/a8d8ce27-6908-4069-b8a0-6e1ac3359353)




<br />
<br />
The Installation process is now complete but we still must promote the server to a domain controller.  <br/>

![image](https://github.com/user-attachments/assets/708a107c-8f71-4d9f-8864-48442478d798)





<br />
<br />
Select the flag icon in the top right corner of the window and under "post deployment configuration" click "promote this server to a domain controller."  <br/>

![image](https://github.com/user-attachments/assets/26e4d3b5-747c-4e76-a3e5-014ddba5646b)




In this window, select add a new forrest and name it "mydomain.com", then select next.  <br/>

![image](https://github.com/user-attachments/assets/eccd87c9-5e91-4eba-b5c5-207159f9fcd2)



Under domain controller options, leave everything the way it is besides the password. Create a password and confirm it. This is the password for non-local users to log in with for the new domain.  <br/>

![image](https://github.com/user-attachments/assets/12d87155-a9eb-4343-94a5-012fe71efafe)




Deselect the box, "create DNS delegation" and select next.  <br/>

![image](https://github.com/user-attachments/assets/59230ea6-138a-4a11-ac6b-af77b18c08e4)



The Prerequisites check will take a few moments to finish.  <br/>

![image](https://github.com/user-attachments/assets/920f4150-0f09-4dda-9054-79b193494681)



Installation will now begin, wait a few moments for completion.  <br/>

![image](https://github.com/user-attachments/assets/0dd0db4c-afb5-4891-a187-180ddaaec684)



As soon as the installation is complete, the computer will automatically restart.  <br/>

![image](https://github.com/user-attachments/assets/7194de76-156d-4dff-9f18-4f65b8654359)



Log back in to dc-1 as your domain, in this case it is "mydomain.com\user." Once you are logged in, press the start button in the bottom left corner, and search for "active directory users and computers." If it shows up, then active directory has been properly installed.  <br/>

![image](https://github.com/user-attachments/assets/4fd574af-ef9c-4a7a-a13c-ade28457d6b3)


Log back in to dc-1 as your domain, in this case it is "mydomain.com\user." Once you are logged in, press the start button in the bottom left corner, and search for "active directory users and computers." If it shows up, then active directory has been properly installed.  <br/>

![image](https://github.com/user-attachments/assets/0d797817-a330-4d65-8964-c1a0000ca6a1)


Log back in to dc-1 as your domain, in this case it is "mydomain.com\user." Once you are logged in, press the start button in the bottom left corner, and search for "active directory users and computers." If it shows up, then active directory has been properly installed.  <br/>

![image](https://github.com/user-attachments/assets/82574882-9d3e-458f-a0d3-73bd459540d8)


