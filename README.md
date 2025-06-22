# React-js-Full-project
Creating a virtual Id 
![image](https://github.com/user-attachments/assets/a371406c-645f-4623-b752-fadadb61678e)

How does the first page work
-	This is the welcome page that tells the user about the system, and it also has the navigation to link.
-	What you would want to do is register your account first

![image](https://github.com/user-attachments/assets/545f92ce-1d14-46a4-b4f9-f8776ffd3357)
How does the second page work
-	So here the user will register their account, but everything about applicant is on the mock home affairs database so the user will be required to enter the ID. Upon entering the Id the system will fetch all the user data from the database and populate on the mock home affairs.
Lets say user has already created an account the following will show.
   ![image](https://github.com/user-attachments/assets/b3db7211-1295-48b0-9ec5-4a8fbeeaa286)

Lets say the user’s Id is not on the mock home affairs Database.
    ![image](https://github.com/user-attachments/assets/e1c2dfb8-cec7-4b39-ae41-221cbd95682c)
Let’s say the user’s id is valid and on the system. It will populate all the field then what a user must do is enter a valid email and create a passsword
    ![image](https://github.com/user-attachments/assets/090b2a05-f496-4699-b442-e9d73680ad2c)
Enter email and password then registers.
    ![image](https://github.com/user-attachments/assets/9f83d1da-2375-49cd-89b2-3e0a6341be71)
After successfully Registered the pop will appear telling a user that their account was created.
    ![image](https://github.com/user-attachments/assets/2ea7c6a4-29f9-480c-bdbe-a67f61260788)
User will login using their details and say the user forgot their password they can press the forgot-password link and the will be directed to the following pages.
    ![image](https://github.com/user-attachments/assets/98454dc0-f39f-465d-b3e4-d8ef7ee99392)

The user will then enter their email address to get the verification token then the system will store that token on the database. 
If the user enters an invalid email the system will show.
After the user verifies their email and the system is done verifying they will be taken to a page where they will enter token sent via email and the system will compare and take the user to the reset password page:
   ![image](https://github.com/user-attachments/assets/f309f8ae-9303-4a74-9cde-a582803bb0e9)
   ![image](https://github.com/user-attachments/assets/c5159047-d127-4ff3-b150-37c1332653b5)
   ![image](https://github.com/user-attachments/assets/5506cfe2-fb97-423f-b923-5904ffa95b94)
Then it will take the user to the login page where the user will login with their new password. Then if verified it will take the user to the Dashboard this is how the dashboard looks like.
   
This dashboard has the 3 button which is the apply for id, generate id and view profile.
So when the generated id will be disabled if the user hasn’t applied for an ID. So when the user press apply for id they will get the following page.
![image](https://github.com/user-attachments/assets/80e62a2e-126f-4109-9097-6ebf8a5b465a)

![image](https://github.com/user-attachments/assets/d578b5f9-bc4c-4f29-8e19-426fe78468f3)
As you can see some field are auto populated, the user won’t need to enter some fields as the user records are already on the Mock home affairs database even the parents details. 
And then we have a feature for taking an ID photo, the user may/not take the picture it depends on if the user prefers to use the photo stored on the database or take a new one.

Should the user decide to take a new photo they will be asked to take a picture and it will be varied with the picture in the database should they match then the user will be allowed to user should not the user will get the message from the system. So here there is face recognition feature.
![image](https://github.com/user-attachments/assets/a7daa2e6-f0d9-4a44-b3f8-99170b592d6c)
![image](https://github.com/user-attachments/assets/bed86086-f4c7-4d3d-a753-01839d0ab7c9)
And after the face recognition feature the user will click submit and they will be taken to the processing page where they have to wait for the specific period before they can get their ID. 
![image](https://github.com/user-attachments/assets/6d412963-98aa-4a2a-a43a-db0ac6b0c781)
Right after the time has elapsed the user will be taken to the generate id page and if they press it they will be taken to id page, this is where the ID will be generated and automatically downloaded to the user machine, so we made it in such a way that the ID can be generated once off then the user may just view on their pc.

![image](https://github.com/user-attachments/assets/209a4280-6391-4685-94d4-cdde4db5103f)

Then the user will be taken back to the dashboard then when they press view profile, they can get their profile details, and they can be able to delete their profile/edit their profile.
![image](https://github.com/user-attachments/assets/58532587-218f-4c0d-b757-bc99c160df5d)

On the welcome page there is a button for analytics where the admin can get the reports about which user registered, which user applied for id, age ranges and everything a user might need to create a report and they can also download as CSV file(Excel).
So the admin will login and see the following two pages.
![image](https://github.com/user-attachments/assets/af1df59d-97a9-4b2d-9c35-85a40ce8a31f)

![image](https://github.com/user-attachments/assets/2c67374f-2558-4bd1-b4d6-0413500ecd42)

The user can use the dropdown to filter based on the following category.
![image](https://github.com/user-attachments/assets/63d98301-cd88-4cfd-a543-9969dd1a107f)
![image](https://github.com/user-attachments/assets/a1ae2db1-ae13-4e9f-994f-ed4534d2bfc6)

You can even search for the is you want.
The report for Tracking applications in the system.
![image](https://github.com/user-attachments/assets/3b624c7c-7df8-49a5-8920-f7230422ae1b)
Here we can filter based on the dates and they can search for the id they want.


















  


