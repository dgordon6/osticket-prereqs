# Active Directory - Unlocking an end-users account and resetting password<p align="center">
<img width="2500" height="415" alt="image" src="https://github.com/user-attachments/assets/dd1a99e7-ea88-4890-9b1e-53fba21f3d5f" />

</p>

<h1>Active Directory</h1>
This tutorial outlines how to reset and unlock an end-users account by using Active Directory.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Reset End-Users Password Using Active Directory](https://youtu.be/V5ZH58WnaUs)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory
- Group Policy Management Editor

<h2>Operating Systems Used </h2>

- Windows 11</b> 

<h2>List of Prerequisites</h2>

- Microsoft Azure
- Remote Desktop Connection
- Active Directory
- Virtual Machines
- Group Policy Management Editor

<h2>Installation Steps</h2>

<p>
<img width="2533" height="1315" alt="Screenshot 2025-09-26 174940" src="https://github.com/user-attachments/assets/21ba1d03-f0dd-4c8e-8501-a4d7034a097a" />

</p>
<p>
Open "Active Directory Users and Computers" and locate the folder with the stored users. 
</p>
<br />

<p>
<img width="2546" height="1316" alt="Screenshot 2025-09-26 175311" src="https://github.com/user-attachments/assets/619f4b0d-f0cb-4193-9cdc-7895ea9bcf3f" />

</p>
<p>
Search for the specific user that needs their account unlocked or password reset. Double-click on their username and go to the "Account" tab. There is a box which can be selected that will allow the end-users account to be unlocked. In the case that they want their password reset, within "Account Options" ensure that "User must change password at next logon" is selected. Then, right-click on the users name and select "Reset Password". 
</p>
<br />

<p>
<img width="2534" height="1316" alt="Screenshot 2025-09-26 175619" src="https://github.com/user-attachments/assets/9786398e-cce0-4476-90b4-e4c752eaee41" />

</p>
<p>
Within the "Reset Password" window, a new temporary password may be given. Due to the setting to have the user change password at next logon selected, the end-user is able to logon using the temporary password that was set, and then reset their own password once they are logged on.
</p>
<br />
