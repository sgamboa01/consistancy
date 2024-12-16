# Consistency App
The purpose of the Consistency application is to help users create and maintain healthy habits by applying social accountability to motivate the user to keep up with their goals. 

# Section 1: Document Roadmap #

## 1.1	Purpose of the Document
The purpose of this document is to define the Consistency application software design, intended for individuals seeking assistance with maintaining goals and building communities for increase goal achievement. The document contains the following information:
•	Scope: Description of the problem statement.

•	System Overview: Provides context to the goals that the system is attempting to achieve. It highlights the business goals and non-functional requirements.

•	UML Diagrams: Visual representations for the system interactions, classes, deployment, message flow, and more.

•	Design Pattern: Overall rational for design choices.

## 1.2	References:

Newland, S. (2018, November 27). The Power of Accountability. AFCPE. https://www.afcpe.org/news-and-publications/the-standard/2018-3/the-power-of-accountability/ 
## 1.3	Scope

This system seeks to provide a design solution to a social problem. It can be difficult to find motivation on our own to complete, maintain, and achieve goals, like eating healthily or constantly going to the gym. According to research by AFCPE, a national non-profit organization focused on coaching and education, studies show that working with a group increases productivity and the likelihood of a person’s chances of success by 95%. The following are core actions that researchers found:

•	Having an idea or goal: 10% likely to complete the goal

•	Consciously deciding that you will do it: 25%

•	Deciding when you will do it: 40%

•	Planning how to do it: 50%

•	Committing to someone that you will do it: 65%

•	Having a specific accountability appointment with someone you’ve committed to 95%

The purpose of the Consistency application is to help users create and maintain healthy habits by applying social accountability to motivate the user to keep up with their goals. The application intends to connect users with other users who have the same goal and motivates users to engage with each other through consistency streaks and progress posts. The design incorporates various collaborative features and a responsive environment. The application will allow users to share their progress, process, and knowledge to help others achieve their goals. 

# Section 2: System Overview
## 2.1 Business Goals
![image](https://github.com/user-attachments/assets/bfcd8deb-bb90-4d84-b67d-eedd6607d638)

## 2.2	 Non-Functional Requirements
**1	Performance** </br>
1.1	The app should have a response time of less than 3 seconds for most user interactions.  </br>
1.2	The app should be able to support scalability to accommodate an abundant number of users.  </br>
1.3	The app should support real-time updates on goal progress, streaks, and shared content.  </br>


**2	Availability**  </br>
2.1	The app should always maintain 99% uptime. </br>
2.2	The app should have regular interval backups and a disaster recovery plan to prevent data loss. </br>

**3	Security**  </br>
3.1	The app shall use secure authentication methods to protect user accounts. </br>
3.2	The app shall support data encryption for all user data. </br>
3.3	The app shall support user access control to ensure only desired people have access to their goals and progress. </br>

**4	Usability**  </br>
4.1	The app shall maintain an intuitive and user-friendly interface and navigation.  </br>
4.2	The app shall follow WCAG (Web Content Accessibility Guidelines).  </br>
4.3	The app shall support multi-platform use and provide a constant experience across all platforms.  </br>

**5	Maintainability**  </br>
5.1	The app shall be organized in a way that allows quick bug fixes, updates, and new features. </br>
5.2	The app shall be able to handle errors and display helpful error messages to users. </br>

**6	Interoperability**  </br>
6.1	The app shall support integration with third-party platforms to help users track progress. </br>

**7	Compliance**  </br>
7.1	The app must comply with industry security standards for user data privacy and security  </br>

**8	Analytics**  </br>
8.1	The app shall be able to collect data on user progress and provide statistics  </br>
8.2	The app shall provide users with personalized tips and notifications </br>

# Section 3: UML Diagrams
## 3.1 Use Cases

1.	Create user account
2.	Request to join an established Community group
3.	Search for a community
4.	Establish your own community group
5.	Create list of goals and habits
6.	Start a streak with individual or group
7.	Notify users of streak status
8.	Notify users when a new person joins a common community
9.	Create progress status post
10.	Track goal/ habit status
11.	Set goal target completion date
12.	Provide positive reinforcement through in app rewards
13.	Comment on group posts
14.	React to another user’s post
15.	Provide users with daily motivational affirmations
16.	Create and establish routines
17.	Connect to fit devices 
18.	Set individual streak conditions per goal.

## 3.2 Use-Case View

![image](https://github.com/user-attachments/assets/18fa862c-65bb-4260-8899-cb9a72b7399a)

## 3.2 Domain Model

![image](https://github.com/user-attachments/assets/852bde95-0772-476c-a801-965382210ca4)

## 3.3 Class Diagram

![image](https://github.com/user-attachments/assets/c46860bc-e6b4-45e1-be81-25cbfb8b79f9)

## 3.4 Sequence Diagram

UC1: Request to join an established Community group

![image](https://github.com/user-attachments/assets/2e25b2a9-4643-4232-a62a-015d7e02e04a)



UC2: Create New Community group

![image](https://github.com/user-attachments/assets/93c08062-22bd-44ec-abba-47ad6d2e3426)


UC3: Add a new goal.

![image](https://github.com/user-attachments/assets/151ed420-0573-4783-9aa0-9d5bec07312d)

UC 4: Start New Streak with a friend or group
![image](https://github.com/user-attachments/assets/040c7892-475e-427d-a5ed-551512040c0a)

UC 5: Create a new post:
![image](https://github.com/user-attachments/assets/a03eab76-0c97-4413-99bd-d9473a3a9c0c)

## 3.5 State Diagram

The state diagram below maps out the primary states that the application can be in, along with the events and conditions that trigger transitions between the states.

![image](https://github.com/user-attachments/assets/7c2f54bf-180e-4c8c-a910-a910b3ba9229)

## 3.6 Activity Diagram
The activity diagram below shows the activity and flow for a user creating a new goal in the Consistency Application.

![image](https://github.com/user-attachments/assets/7c1c81aa-09e1-4c84-8516-40efd8585add)

## 3.7 Component Diagram

![image](https://github.com/user-attachments/assets/2015dbb8-14c1-4bb8-b2c9-f28159437205)


## 3.8 Cloud Deployment Diagram
![image](https://github.com/user-attachments/assets/f421005d-a73d-4f0f-85fd-bc8d182fb01b)

## 3.9 Skeleton Classes and Tables Definition

![image](https://github.com/user-attachments/assets/4d92ad2c-74f3-4751-97bf-65ef130dbd18)
![image](https://github.com/user-attachments/assets/15421bed-d9ca-4c65-965e-8075aecd7e63)
![image](https://github.com/user-attachments/assets/21fc93ab-42c5-4bd6-bd40-644b3276d396)
![image](https://github.com/user-attachments/assets/c40ae28e-adea-46f0-8a2e-b33873bc66ea)
![image](https://github.com/user-attachments/assets/feee0461-f197-443a-96c6-da892a764f79)
![image](https://github.com/user-attachments/assets/26e6cba0-f4e4-452c-b660-1adb4198b2bc)
![image](https://github.com/user-attachments/assets/f2125494-9da6-40f9-8074-98d58f84d112)
![image](https://github.com/user-attachments/assets/7c9563e5-9db5-433a-b268-7d05cf57984b)

## Prototype
![image](https://github.com/user-attachments/assets/81ecea61-3a48-425f-9482-bf900959243b)
![image](https://github.com/user-attachments/assets/c7877588-011d-4f09-8744-dcc24b3071ca)



## Section 4: Design Pattern
The Consistency App follows a layered microservice architecture design pattern and uses the General Responsibility Assignment Software Pattern. As shown in the components diagram, my application follows the information expert and controller pattern with the use of the subsystem components, like UserManagement, Habit Management, Goal Management, and SystemDatabase. UserManagement components handle information that concerns the users access to their session and profile. Habit Management and Goal Management components manage the habits and goals. This includes managing logic and acting as use-case controllers for creating and maintaining said habits and goals. The application design also illustrates the low coupling by separating external components from the core system logic and isolating the database.








