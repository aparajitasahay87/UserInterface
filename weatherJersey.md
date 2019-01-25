# **Case Study: Weather Jersey**

## **PROJECT GOAL**
Design a mobile application that recommends activities to do in and around a location as per the weather and users’ interest. 

## **CHALLENGE**
Weather plays an important role in making decision on where to go for recreational activity on weekends or when we are traveling. Going for a weather supportive activity enhances the enjoyment experience of a person, however, finding the activity online and referring many applications at the same time such as weather apps, user’s interest and things to do – navigation and switching between so many apps become time consuming and frustrating. 
Weather jersey is a mobile application that will suggest user list of activities to do in an area depending on weather condition and their interest. 
The major task for the design interface is
1.	clear and intuitive navigation 
2.	easy interaction and relevant information.
3.	Creating a flexible layout architecture that can be easily scalable in future. 

## **PROCESS**
A user centered design philosophy has been followed to address this problem. It consists of following phases:
1.	Research
2.	Ideation
3.	Design and prototype
4.	Conclusion 

### **1.RESEARCH**
Once the goal of the project was clear, I started learning about the similar application that recommends events or activities such as Eventbrite, yelp, Facebook locals. After going through each application, I learnt that there is no application that caters the scenario of recommending activities as per the weather and the user’s interest. 
After finding all the competitors and their features and types of users, I started interviewing people (friends and family) to learn about
•	Who will use this application?
•	Who is it about and what experience does it address?
•	How will it be shared? 
After talking to different people, I created two personas and tried to find their pain points and how this application can solve their problem. 
I worked in a team: one and other college mate. 
A project for a course during master’s degree. 
Advisor: professor and clients were all the class mates. 
#### **Personas:**  
1. Name: Vivian
* Occupation: Software engineers and a mother of 3-year-old girl
* Age: 33 years
* Hobbies: traveling, biking, exploring new activities, blogging about her daughter activities and milestones. 
She loves going out to do new activity with family and friend
* Location: Living in Seattle for almost 5 years..
* Goal:  
     1. She would like to find activities on weekend which is weather friendly.
     2. She would like to find a place depending of her interest. 
     3. She wants search activity process as easy as possible and using one application.
* Pain points:  
    1. She finds it difficult to find activities as per her interest.
    2. She finds it tedious to switch to two applications weather application and recommendation system application to  
       find activities to do.
    3. She finds it difficult to share it with her friends.  
2. Name: Rob  
* Occupation: works in a bank  
* Age: 40 years   
* Hobbies: traveling, hiking and social work  
* Location: Living in San Francisco    
* Goal:  
     1. When he is traveling to a new city as a tourist, he wants to enjoy the activity  
        that is weather supported.  
     2. Also, he wants to find places to visit in a new city depending on his interest. 
* Pain Points:
     1. Cannot quickly find things to do in a new city with weather in mind.
     2. Spends a lot of time to search new activity for a day if the weather is not suitable  
        for planned activity. 
     3.No application provides recommendation depending on his interest accurately, recommendations are not personized. 
#### **User scenarios: (situation, motivation, outcome)**
1.	Eric is visiting San Francisco in his winter break. He wants to visit all the tourist places and wants to find activities  
    depending on his interest. But he is constantly checking weather condition on his phone before making any plans for the next day,  
    since bad weather can ruin his experience for the travel. So, he wants to quickly find activities in SFO which is best suited for  
    a day depending on the weather and his interest.
2.	Sara lives in Seattle and wants to go for a hike any day this month. She wants to find a day that is best suited (weather wise) to  
    go for a hike in coming few weekends. 
3.	Sara wants to share a nice activity that best suites her interest and the weather with her friends who share similar interest.

    After interviews, I came across following **pain point** among multiple people.  
    1. Where to find quick information about the most appropriate activity/events depending on weather and user interest.
    2. Switching between multiple applications to find activities is time consuming.
    3. How to share the information about the event with friends or family.

### **2.IDEATION**
Given the different personas my challenge was how to design an application which can cater the needs of the users from different  
perspective i.e. a tourist and a local.As per the interview with the locals and the tourist, weather was important factor to find  
the activity. However, for the tourist time was the limitation and wanted to cover more touristy places under given time constraints.  
For the locals, time was not a constraint but finding activities as per his or her interest. However, in both the cases **weather**  
plays a crucial role before making any decisions on finding and going for an activity.  
I employed the brute force approach over the course of time to design and iterate quickly upon ideas. After each stage of fidelity,  
I sent it out to my friends to gather feedback and make changes. Used paper prototyping initially for quick prototyping of the idea.  
And once first ideation was over shifted to Balsamiq for the quick design and share among friends for the feedback. 
Once the general lines were established, a brainstorming session was held to see the functionalities the application could have: -  
Then, **I prioritized the ideas following MoSCoW matrix.**   
* **Must have**
  1. Mobile app.  
  2. Capturing user’s interest.   
  3. Tracking weather.     
* **Should** 
 1.	Option of sharing the information with the friends.
 2.	Adding the activity in the calendar.  
* **Could**_
 1. Suggest the activities without manually gathering user’s interest. 
 2. Option of changing the user type from tourist and local.
 3. It could have a VUI (Voice User Interface). This would allow a quick consultation of information without having to touch the  
    screen and interrupt daily tasks.    
    
**The main functionalities of the solution are:**
1. It must be a mobile app, because our users make intensive use of this device.
2. It must make it possible to recommend activities depending on user’s interest and weather. 
3. Sharing the information with the friends.
4. Adding the activity in the calendar.
5. Capturing user’s interest.
6. Option to update the filters to find new recommendations.

### **3.PROTOTYPE**
#### **PAPER PROTOTYPE**
![paperprotoype](https://github.com/aparajitasahay87/UserInterface/blob/master/paperProtype.jpg)  

**DESIGN PROTOTYPE**
 ![welcome](https://github.com/aparajitasahay87/UserInterface/blob/master/Untitled.png)    

Default option to choose your current location while signing up. Tell the system about the interest by clicking few options/choices. By default, application will suggest places depending on current location and current weather.
 
![landingPage](https://github.com/aparajitasahay87/UserInterface/blob/master/landingPage.png)  
Since, the application is a recommendation system which suggest activities to the user as per their interest and weather I followed few **UX guidelines for Recommended content**:-    
  **1.Separate Categories of Recommendations**:    
      Weather jersey suggest list of activities depending on interest and weather. Users can have multiple interest and if the personalized suggestions are too diverse, making sense of them will be difficult, and people will be less likely to interact with them — whether through browsing or through actively editing the suggestions. So, to reduce the cognitive load, I made sure to display recommendation in categories and more specific categories of recommendations first.  
  **2.Allow Users to Fine-Tune Suggestions**: 
The ability to provide feedback to the system about the recommendation will allow the system to learn more about the user. And user can also tweet his or her interest and provide feedback to the suggestion that will help system to be smarter. It will also allow user to be more engaged to the application.  
**3. Update Recommendations Quickly and Often**: 
It is also important for the application to quickly incorporate the feedback and the changes made by the users. Responsive application will allow user to trust the system.  
**4.Progressive disclosure**:
The content of each recommendation is divided into categories. Result will show minimum details of a recommendation at beginning if user wants, they can elaborate more details if needed. Progressive disclosure technique is used to solve the problem of complexity by making information or features available only when users need them. Progressive disclosure can help reduce cognitive load and improve comprehension of the interface.  
5.User will always have the option to update the filters to looks for a new recommendation. Hamburger menu on the landing page/main page will allow the option to fine-tune the filters and see their activity calendars.

### 4.**CONCLUSION**
Good recommendations help users quickly identify items that interest them. Providing methods to interact with the suggested items empowers users to reach their goals. Separating personalized suggestions into clear categories and providing methods for users to give feedback will also encourage increased engagement with the application. 

