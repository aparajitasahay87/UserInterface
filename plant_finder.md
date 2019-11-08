# **Case Study : Plant Finder**

##
**Project Goal**
The goal of the application is to enable user to carry a phone having plantFinder and get the information about the plant in real time. 

## **Project Challenge**
For inquisitive people who wish to be knowledgeable about the plant around them, gathering information about unknown plants manually is time consuming. To gather information, they either go to their local nursery, read books or research in the internet by uploading the picture. 
It would be great if we can find the name of the plant just in one click wherever we are present currently.
A user centered design philosophy has been followed to address this problem. It consists of following phases: -
1.	Research
2.	Ideation
3.	Design and prototype
4.	Testing and conclusion 

### **1.RESEARCH**
Research began with a series of question on “what” the application would be. In this case, I wanted it to be a phone application. So that the application is always available with the user in his or her phone so that they get the information instantly. 
After discussing about the application with my friends and professors I came to an initial hypothesis about who will be the user of this application: -
1.	School student 
2.	Gardner enthusiast
3.	Biologist and scientist. 
The main goal of PlantFinder application would be to retrieve real time information about any plant that a user sees in day to day life without spending time exclusively on internet. 
PlantFinder application will enable user to take the picture of the plant in real time and in one click application will return the most close matched result to the user in real time. 

#### **User Persona and journey**   
As a result of these findings, I created two user personas and their corresponding customer journey. This allowed me to put the users at the center of the whole process and focus on their main pain points. 
#### **Personas:** 
##### **1.	School student**
* Name: Meera  
* Age: 14 years.   
* Behavior: inquisitive, attentive  
* About: A 10-year-old girl. She studies in lake hills school. She walks every day to school with her mother. She loves biking and traveling. Loves mostly outdoor activities. 
* Goals:  
        1. She would like to learn about the plants in her area.  
        2. She would like to share the plant information with her friends in other school.    
        3. She wants the search process to be simple and quick.  
* Pain point:     
         1. It is time consuming for her to learn about any plant in real time.   
         2. Cannot share her findings about the species and plant with her friends in other school area.  

##### **2.	Hobbyist gardener** 
 * Name: Daisy   
 * Age: 28     
 * Behavior: Loves hiking, biking and traveling the world. She is passsionate about her hobbies and wants to spend more time with people who shares similar interest. 
 * About: She is a software engineer. She works 9 - 5 pm and sometime in weekends. She loves going for a hike, enjoys travelling and does indoor gardening at her home. 
 * Goals:   
        1.	She wants to spend more time with nature.   
        2.	She wants to grow different plants at her home.  
        3.	She wants to share her findings of new plant in her garden and around her with her friends who shares similar interest.   
        4.	She wants to build her own library/catalog of plants and its information which she has seen while traveling around.   
  * Pain point:  
        1.	Learning about each plant is time consuming. Have to go to nursery or search online which takes time and not instant.  
        2.	Sharing her journey about plants which she loves is a tedious job for her.  
        3.	Maintaining a catalog of the plants and trees she has seen so far is not consistent.  
        
After surveys and interviews I came across following **pain point** among multiple people.  

1.	Doesn’t know where to find information about the plant quickly in few minutes / instantly.  
2.	How to share the information about the plant with friends.  
3.	Where to add the information about each plant they have seen so far.   
Once the personas were created, I built following user stories from the perspective of the end user.  

#### **User Stories**:  

    1.	We the group of children are going to a field tour with our teachers to learn more about the plants and tree in and around our area. I quickly want information about the plant such as it's name, plants species etc. , so that I can be more aware about the nature.    
    2.	When I am going for a hike and see some interesting plants while walking , I want to learn about the plant so that I can share the  
        plants information with all my friends who share similar information.   
    3.	As a garner enthusiast, I want to look back to a catalog where I can see and refer some plants information which I have seen in the  
        past.   
        
At this point, the challenge of the application is **“to offer a solution that brings information on demand”**.  
Tackle three pain points:  
  1.	Instantly finding information of a plant in real time.  
  2.	Sharing the information about the plant with friends.  
  3.	Creating a catalog of plants searched so far.  

### **2.IDEATION**  
Once the general lines were established, a brainstorming session was held to see the functionalities the application could have. 
Then, **I prioritized the ideas following MoSCoW matrix**. ![MoSCoW method](https://en.wikipedia.org/wiki/MoSCoW_method)
* **Must have** 
1.	Mobile app  
2.	Image recognition system   
* **Should**
1.	Option of sharing the information with the friends.  
2.	Creating a catalog of plant searched so far.  
* **Could** 
1.	Suggestions for plants that are found and can be grown in user’s current location.  
2.	It could have a VUI (Voice User Interface). This would allow a quick consultation of information without having to touch the screen and interrupt daily tasks.  

**The main functionalities of the solution are:**   
1. It must be a mobile app, because our users make intensive use of this device.  
2. It must make it possible to recognize objects with the camera and get information in a visual way.  
3. Adding plant seen so far in a catalog.  
4. Sharing the information with the friends.  
5. Finding the search history in a map view that shows location where plant was found.  

### **3.PROTOTYPE**

#### **PAPER PROTOTYPE**  

![paperprototype](https://github.com/aparajitasahay87/UserInterface/blob/master/IMG_20190127_000324.jpg)   

#### **DESIGN PROTOTYPE** 

![welcomePage](https://github.com/aparajitasahay87/UserInterface/blob/master/plantFinder_landingPage.png)  

For the first time user, application will provide the option to learn more about how the application works and the option to sign in. However, even if the user does not want to provide credentials for the sign in application for the first time and wants to test the application before providing credentials, user can make 5(limited) request form his/her device. The advantage of sign in option will be it will give more personalized options such as building a catalog, sharing the plant information and map view of past search.     

![searching](https://github.com/aparajitasahay87/UserInterface/blob/master/plantFinder_search.png)  

In one page, user will be given all the main functionality of the application.   
**1.	My catalog**  
      User can store all the plants detail found so far and store it in an online library and see it whenever user wants.   
**2.	Upload Icon**  
      User will be given the option to upload image from the phone’s gallery.  
**3.	Menu option**  
      A quick option which allow user to find the search history, map view of the plants, and logout option.   
**4.	Visibility of the system status**    
      As per **Jakob Neilsen – 10 usability Heuristic for User Interface design**, status of the image processing will be always shown to user till the result is given to the user. Start button icon will have query processing status.    
**5.	User control and freedom**    
      At any point of time between query image processing and result generation, user will always have the option to exit the image processing by clicking the stop button in between the start icon.  

![landingPageDetails](https://github.com/aparajitasahay87/UserInterface/blob/master/plantFinder_details.png)  

Once the image processing is complete, user will find the result.
There will be top 3 most probable result. At any point of time, query image will always be in front of user’s eye just to compare the correctness of the result manually and visually.   
Each result will have plants name, species and brief 2 lines information about the plant. Matched visual image from the database and option to share the information with their family/friends, add it to the catalog, tag the location. 
**Progressive disclosure:-**
To split between **initial and secondary feature** I divided the result data into these sections. **Initial information is a high-level view** of what is expected from the application i.e. plant’s name, option to quickly share it with friends and adding it to the catalog and referring it later. **Secondary feature** - they might not need all the detailed information at an instant such as where it is found, cultivation details etc. So, putting that information in secondary feature.
By showing the most important options upfront, *progressive discloser reduces the cognitive load from the user and helps to maintain the user’s attention by reducing clutter and confusion.* 
**Users Feedback:-** To make the system smarter and more accurate, user feedback can be helpful. Without deviating the user from their goal, application can take their input with a pop up in footer of the user interface. User will always have an option to ignore it or respond to a one-line feedback.  

![description](https://github.com/aparajitasahay87/UserInterface/blob/master/plantFinder_detailsOnePage.png)     

In the **detailed section** of the plantFinder application, user will find all the information associated with the plant. Since, each plant can have plethora of details I divided the data into categories such as **description** – contains plant name , species , fun facts etc. , **cultivation -how it can be grown** which contains all the geographical information such as soil type, weather, water etc. and **where** section which shows all the places in the world where they are found regions and locations.
Also, **the user interface will always have a query image just to compare what they have searched from the real-world plant with the database image**. Visually comparing query image and result image can help user to validate the accuracy of the system.  

![errormsg](https://github.com/aparajitasahay87/UserInterface/blob/master/plantFinder_errorMessage.png)  

Application will help users recognize, diagnose, and recover from errors: If there is problem in retrieving the right result, a easy to understand error message will be given to the user precisely indicate the problem, and constructively suggest a solution. In the plantFinder user interface a try again button is shown to suggest the next step and an error message is provided to tell the problem in simple language such as cannot capture the image due to brightness, network error or not a plant type image etc. 

![catalog](https://github.com/aparajitasahay87/UserInterface/blob/master/plantFinder_catalog.png)  

### **4.TESTING**   
I **tested** the usability of the application by following **10 Usability Heuristics for User Interface Design**:-  
1.	**Visibility of system status**   
    In the image recognition application such as plantFinder, I made sure to tell the user about the status from querying the image till the result generation state. I used status button icon to tell the user about the status.  
2.	**Match between system and the real world**  
    Simple to understand words and components are used to let user (kids and adult) know about the features of the application. The user interface is designed considering the end users of the applications and by considering their pain points.  
3.	**User control and freedom**  
    The main functionality of the plant finder application is to do image processing and return the result to the user. The query page is designed to allow user to exit the image processing state by clicking the stop button. It supports redo option.  
4.	**Consistency and standards**  
    All the icons and component, naming convention, colors text is consistent through out the pages.   
5.	**Error prevention**  
    To prevent the error while requesting for a query (plant information) in the application, user is given a defined place where image needs to be put and a constant message in the background without distracting the user is provided in  the form of pop up below the screen.  
6.	**Recognition rather than recall**  
    All the main functionality of the application i.e. query plant image, catalog, share, map view, detail information is visible to the user at every stage of the interaction.   
7.	**Aesthetic and minimalist design**  
    The goal of the application is to provide the result with minimum number of steps between the user and their goals.   
8.	**Help users recognize, diagnose, and recover from errors**  
    Error message is provided by the application while querying the image and a next step is also suggested to reduce the confusion and provide the clarity  
9.	**Help and documentation**
    For the first-time users the goal of the application is stated by categorizing the actions into steps  
10.	**Flexibility and efficiency of use**  
    How to use the application instruction is given to the user in the beginning.   
    
### **5. CONCLUSION**  
In this case study, we present a user interface design of a phone application for
leaf species identification. The leaf identification process
makes this application useful to amateur stakeholders as well
as experts.Using this application, user can photograph a single
leaf on a white colored background and submit it as the input
que!)' image. Application will then analyze features of the leaf
and identify the plant species at real time.
