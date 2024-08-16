<h1>Password Reset</h1>



<h2>Description</h2>
Project consists of searching for users and resetting passwords of the desired users on Active Directory.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Active Directory Users and Computers</b> 

<h2>Environments Used </h2>

- <b>Windows Server 2022</b>

<h2>Program walk-through:</h2>


press the start menu -> open Windows Administrative Tools -> launch Active Directory Users and Computers: <br/>


![Part 1](https://github.com/user-attachments/assets/3d955789-5ce1-4789-b1e6-7653585e29ad)


____


Find the location of the user in your domain -> right click user -> reset password:<br/>

<br />

![Part 2A](https://github.com/user-attachments/assets/bc52c4cd-e87a-448c-be75-8db6ac368a22)


</p>

____


You can also use the search function if you aren't sure which OU the user is in; click the action tab -> click find....



![Part 2B](https://github.com/user-attachments/assets/d01a5af4-0b6c-4648-9485-d756101227d1)




____


in the second dropdown for location, you can select either an OU or domain name; enter the name of the user



![Part 2C](https://github.com/user-attachments/assets/fdb381f4-9105-42ec-886a-0e0aa276e828)



____



then click find now; from the search results, right click the user -> reset password


![Part 2D](https://github.com/user-attachments/assets/c0f0dacb-5dab-48c4-ae14-389fe10c81c7)




____



input and confirm a temporary password for the user; check the box for change password at next login; advise the user to log off and on if user is in use


check the box "unlock the user's account" if account lockout status text appears as "locked"; click OK



![Part 2E](https://github.com/user-attachments/assets/6eb14391-29d4-4704-b770-93277476c4a4)





____

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
