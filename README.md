# The Language Hub 
--------------------------
This is a website for people of all ages looking to learn English online or face-to-face.  
They can have their English tested and or book one of our courses with a British Council accredited teacher. 


### UX
------

**Client Stories:**

1. As a visitor to the site, I want to be able to navigate with ease.
2. As a visitor, I want to be able to view the courses available. 
3. As a visitor, I want to be able to feel confident I'm in the right hands when it comes to learning English.
4. As a potential student, I want to know what other students think of the school and teaching. 
5. As a potential student, I want to be able to book a course, view times and or make an enquiry. 
6. As an Interested student, I want to be able to Immeadiately book a course. 
7. As an Interested student, I want to be able to complete a contact form. 
8. As an Interested student, I want to be able to follow the school on social media. 

**Mock up:**

Mock ups created as part of the design process can be found here 

(https://balsamiq.cloud/sqnux27/ph73mzl/r2278)

(../assets/images/New Wireframe1.png) 

or see images section for mock ups

### Features
------------

1. The simplicity of the website, the fact that it is minimalistic and I've tried to make it less crowded should enable the user to navigate with ease. 
2. The user is quickly able to view the courses by pressing the courses tab on the top right hand corner which will lead them to a new page and display the courses.
3. A short description on the homepage as to why they should choose us should make them feel confident in using our services. 
4. Having a testimonial on the homepage towards the bottom allows the students to read and see what other students have said about the language centre. 
5. The user can book their course via the book button on the hero image or navigate to the booking page by clicking sign up on the top right. They can also view the courses tab which will bring up all the courses. They can make an inquiry by completing the contact form on the sign up page.
6. The user can immeadiately navigate to the booking page via the book button on the hero image.  
7. Contact form is available on the sign up page.
8. There are social media links on each page at the bottom which the user can click on.


### Technologies used
---------------------

HTML 
CSS

### Testing 

Websites used to validate my code are:

1. Lighthouse > to identify and fix common problems affecting my sites performance, accessibility and user experience. By right clicking the mouse choosing inspect and viewing elements I was able to view and edit my code before making permanent changes.  

Desktop Performance

![Desktop Performance](https://user-images.githubusercontent.com/80712910/119034293-1ef4c700-b9a6-11eb-84e7-bb4d1ad37833.PNG)

Mobile Performance

![Mobile performance](https://user-images.githubusercontent.com/80712910/119034873-cd007100-b9a6-11eb-8af8-7962cfbbbf98.PNG)

The performance on the mobile is 82 because I have some issues with the images, they are static. I'm aware of this and trying to figure out how I can change this. I think the images are not responsive and absolute. 

2. W3C Validator 

No errors or warnings to show

![w3c validator](https://user-images.githubusercontent.com/80712910/119045176-050db100-b9b3-11eb-9bfd-326b4dee9f1b.PNG)

3. Jigsaw Validator

CSS code passed through the official (Jigsaw) validator with no issues

![jigsaw validation](https://user-images.githubusercontent.com/80712910/119045836-df34dc00-b9b3-11eb-9430-f8728334f3b0.PNG)



All navigation links checked and they work > Logo reverts user back to homepaage. The nav links home, courses and sign up work. 
The book now and test your english buttons work. 

Checking my user stories

1. As a visitor to the site, I want to be able to navigate with ease.

![Navigation links](https://user-images.githubusercontent.com/80712910/119036001-27e69800-b9a8-11eb-9226-25eacaaa07af.PNG)

2. As a visitor, I want to be able to view the courses available. 

They can do this by clicking on the courses tab.

3. As a visitor, I want to be able to feel confident I'm in the right hands when it comes to learning English.

![testimonial](https://user-images.githubusercontent.com/80712910/119036437-a5120d00-b9a8-11eb-855d-6f2b4d1db98f.PNG)

4. As a potential student, I want to know what other students think of the school and teaching. 

See above and social media links below

5. As a potential student, I want to be able to book a course, view times and or make an enquiry. 

![sign up](https://user-images.githubusercontent.com/80712910/119036696-f15d4d00-b9a8-11eb-8763-734acc80e1c2.PNG)


6. As an Interested student, I want to be able to Immeadiately book a course. 

![book now](https://user-images.githubusercontent.com/80712910/119036683-eaced580-b9a8-11eb-9ed2-c9b6dcdd2164.PNG)

7. As an Interested student, I want to be able to complete a contact form. 


![sign up](https://user-images.githubusercontent.com/80712910/119036696-f15d4d00-b9a8-11eb-8763-734acc80e1c2.PNG)

8. As an Interested student, I want to be able to follow the school on social media. 

![social media links](https://user-images.githubusercontent.com/80712910/119037048-6761b400-b9a9-11eb-98c1-fb63ba1e6f63.PNG)


Contact form:

Error message when trying to submit form

![empty form](https://user-images.githubusercontent.com/80712910/119037242-a132ba80-b9a9-11eb-99a3-bb29ac3e2aa1.PNG)

Email error message

![email error](https://user-images.githubusercontent.com/80712910/119037532-fec70700-b9a9-11eb-98cd-0c0fcb8fea18.PNG)





EXPECTED
TESTING USING
RESULT
FIX

Automated testing
Validation services
Website for testing 

**Bugs discovered**

I couldn't upload a hero image succesfully - the image was to big and wouldn't fit on the page. I tried changing the code, height, width, position etc, nothing would work. I then did some research and found out from the image properties that the pixels were to large and I had to compress the image. I found pixabay useful for this because it enables you to enter the image size. I uploaded the image, entered a height and width and it seemed to work. I still don't feel confident uploading pictures but with practice i should get better.  

Still having trouble with pictures - testimnial section was an issue sorting out (see footer bug image)

When creating a link for the find your course button the text was highlighted blue - found out that i already had a class named active so i had to rename the class add to css and style. 

### Deployment 
--------------

1.	Log into GitHub
2.	From the list of repositories on the screen select The Language Hub
3.	From the menu items near the top of the page select settings
4.	Scroll down to the GitHub pages section
5.	Under source, click the drop-down menu labelled ‘None’ and select master branch 
6.	On selecting master branch, the page is automatically refreshed, the website is now deployed
7.	Scroll back down o the GitHub pages section to reference the link 

How to run this project locally:

1.	A GitHub account - create an account
2.	Use the chrome browser
3.	Install the Gitpod extensions for chrome
4.	Restart the browser
5.	Login to Gitpod with your Github account
6.	Navigate to the project GitHub repository
7.	Click the green Gitpod button top right-hand corner
8.	This will trigger a new Gitpod workspace to be created from the code where you can work locally


### Credits
-----------

**Content** / **Media**

The images were sourced from pixabay.com

Testimonial image link: https://pixabay.com/photos/concentration-curiosity-curious-16032/
Why learn English image link: https://pixabay.com/photos/students-computers-laptops-smiling-1807505/
Hero image link: https://pixabay.com/photos/teacher-property-plant-and-teaching-3765909/

**Code**

Colors for the courses taken from: https://www.w3schools.com/colors/colors_picker.asp

Code for logo copied/taken from google fonts

**Acknowledgements**

I received inspiration for this project from the mini project Love Running and my current part-time work as an English teacher. 