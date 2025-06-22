# CS 499 Portfolio

## Introduction

  Hello, my name is Brigitte McColl, and I started to complete my computer science degree at SNHU about two years ago. I previously had a minor in computer science and I decided to complete it after working in the field for a couple of years. This a portfolio of my previous projects and the enhancements that I made to them afer reviewing them again. 

## Self-Assessment

  Throughout this program and the creation of this portfolio has taught me how I can review my code and make changes to it so that my code will be more efficient. This portfolio helped me showcase my skills in thinking about the security of my projects. Over the course of this program I have become more and more interested in adding security measures such as JUnit Testing and also running other tests. I always liked running my projects and debugging and fixing them. I think that these projects where I got to work on my testing and debugging skills that it helped me figure out what kind of job that I would want in the future. In class that the first artifact and second artifact is from helped me understand that I like learning about security measures for applications and how we should be thinking about security throughout the creation of the project. For example, thinking about input validation while writing the code instead of thinking about it after the entire project has been created. 

  When it comes to collaborating in a team environment, I keep reinforcing the need to have others look at my code. I have had some problems with my code in the past that I asked for help with and it was a small fix that I just wasn't seeing so having the extra pair of eyes look at it helped me fix it. I also found that sometimes explaining the project that I am trying to create to someone who doesn't know anything about coding helped me understand my code more and help me simplify some of the functionalities that I had to write. In this program, I have also learned how to talk to stakeholders to get a better understanding of what they would want in their project. Being able to speak to them and explain some of the more technical information to them in a way that they understand is a great skill that I have learned. When it comes to talking with stakeholders about their project, knowing how to ask questions to understand what they want their project to look like was another skill that I have learned throughout this program. 


## Artifacts

The artifacts and code review below showcase my ability to take the review of my code that I did and make the enhancements that I wanted to make. There are three artifacts below that cover these three categories: software design and engineering, algorithms and data structures, and databases. You are able to read a description of the artifacts and the enhancements that I made to them. 

## Code Review

[Link to Code Review Youtube Video](https://youtu.be/6Lf3Znu4wfs)

### Artifact One: Software Design and Engineering 

  This artifact was introduced in CS 320: Software Testing, Automation, and Quality Assurance in project 1. In this project we needed to have three different objects with their own service to produce create, read, update, and delete (C.R.U.D.) functionalities. With these objects and their services there will also be Junit tests that are done on the code to make sure that it is working correctly. 

  The reason that I selected this artifact was because it can show a variety of different skills such as thinking about any type of validation, Junit testing, and error handling. In the original project we had to make sure that we had 80% code coverage so there were still some parts of the code that wasn’t tested and some validations that needed to be added. When I was looking at what to enhance I saw that I could add in more tests and add in validation to the objects to make sure that there aren’t multiple contacts, tasks, or appointments that are exactly the same. I chose to enhance the amount of tests that I was running on the code to make sure that I had closer to 100% code coverage. I looked at all of my code and made sure all the lines that needed to be covered was covered by Junit tests. Unfortunately I was unable to add in the validation because it was causing more lines that were previously covered to not be covered by the tests that I wrote so I ended up not being able to add in the input validation. 

  Before enhancing this artifact, I pointed out the course outcomes for this artifact as developing a security mindset. Since I was thinking about adding in more validation and Junit tests, I was thinking about the security of the project so that there couldn’t be ways to get into the system. I know I met the outcome of adding in Junit testing, but I was unable to hit the validation. I do think that I could add in two more outcomes to this artifact being: Employ strategies for building collaborative environments and demonstrating an ability to use well-founded and innovative techniques, skills, and tools. I can see myself meeting these outcomes through the comments that I leave on my code allowing for anyone that sees my code to understand what the code does. I can also see myself meeting the innovative techniques outcome by the type of Junit tests that I am running and how I will implement the validation. 

  The more I do Junit tests the better I get at writing them. Working on this artifact is helping me learn more about Junit tests and understand how to write them properly to cover the code. The main challenges that I faced was with certain tests failing and I wasn’t able to fix every test that failed because I am still confused on how to fix the tests at the moment. The other challenge that I faced was with the validation and trying to understand why when I add it, it causes more code to not be covered again. I hope to keep working on this to make sure I add in the validation and that all the tests are running correctly. 

[Link to Original Artifact](https://github.com/brigittemc/brigittemc.github.io/blob/main/Original/Software%20Design%20and%20Engineering%20Artifact.zip)

[Link to Enhanced Artifact](https://github.com/brigittemc/brigittemc.github.io/blob/main/Enhanced/Software%20Design%20and%20Engineering%20-%20Updated%20Artifact.zip)


### Artifact Two: Algorithms and Data Structure 

  The artifact that I have enhanced was introduced in CS 320: Software Testing, Automation, and Quality Assurance in project 1. In this project we needed to have three different objects with their own service to produce create, read, update, and delete (C.R.U.D.) functionalities. With these objects and their services there will also be Junit tests that are done on the code to make sure that it is working correctly. 
The reason that I selected this artifact was because it can show a variety of different skills such as being able to enhance data structures and algorithms. This artifact shows that I can optimize a project to run smoother and faster. In the original project the data structure that was used was an Array List that could make the system run slower because when trying to find the contact, appointment, or task requires going through the entire list. Since I was using an Array List data structure it caused my algorithms running C.R.U.D. functionalities to run slower if they have to find a contact, an appointment, or a task. The component of the data structure was improved by using a Hash Map to hold all of the contacts, appointments, and tasks. This makes it easier to find certain items in the map because we can just search for the unique Id to find the item compared to searching through an entire list. Once I updated the data structure to a Hash Map I needed to update the C.R.U.D. functionalities to search using the Hash Map. This cleaned up the code making it simpler to see what the code it doing and optimized searching for the different items by using their unique ids.

  Before enhancing this artifact, I pointed out the course outcomes for this artifact as using well-founded and innovative techniques, skills, tools and design and evaluate solutions that solve a given problem. I met the first outcome by using innovative techniques of implementing a Hash Map and the Hash Map search functionalities to optimize the system. The second outcome was met by how I evaluated a problem with the runtime of the application and designed a solution to optimize the runtime by making the project run faster. Another outcome that I covered in this artifact is to employ strategies for building collaborative environments that enable diverse audiences to support organizational decision-making in the field of computer science.  I show this in the comments that I add to my coding showing what each part of the code is doing so that if anyone reads my code they know what the code is doing and what each part of the code does. 

  In the past, I have been introduced to Hash Maps, but I haven’t really used them in this way so when enhancing this artifact, I learned more about how to implement Hash Maps. I did have to do some research on some of the different ways of getting information from a Hash Map and any other built-in functionalities that come with using a Hash Map. Even though I needed to look up some information about Hash Maps, I did know exactly where I needed to put them and what changes to the code that needed to happen. The main challenge that I faced was making sure that I use the correct Hash Map functionalities to make sure that it runs smoothly.  

[Link to Original Artifact](https://github.com/brigittemc/brigittemc.github.io/blob/main/Original/Algorithms%20and%20Data%20Structures%20Artifact.zip)

[Link to Enhanced Artifact](https://github.com/brigittemc/brigittemc.github.io/blob/main/Enhanced/Algorithms%20and%20Data%20Structures%20-%20Updated%20Artifact.zip)


### Artifact Three: Databases

  This artifact was introduced in CS 465: Full Stack Development. This artifact is a travel website that allows users to log into the system and look at a list of trips that they can go on. Once they are logged in they can add or edit the trips’ information. This project was included because the website gets and sends its information in a Mongo database which showcases my experience in working with databases.  The main components that shows my skill is that I can connect my application to a mongo database and be able to write and update the database. Besides adding and updating it also showcases my ability to add in security measures when it comes to logging into the system through my use of JWT Interceptor creating tokens. This artifact was improved by adding in roles so that only admins have access to making changes to the trips. The other enhancement that was added was that admins are able to delete trips if they don’t offer that trip anymore. 

  The course outcomes that I met is demonstrating an ability to use well-founded and innovative techniques, skills, and tools, design and evaluate solutions that solve a given problem. I met the innovative techniques by adding in more functions to be able to check if the user was an admin or not. I evaluated solutions that solve a given problem by looking at what I wanted to add, roles, and figuring out a way to create functions to check and also make sure when an admin it logged in that they can see certain buttons that a customer wouldn't see such as an edit button.

  In the process of enhancing this artifact, I learned more about how I can go about getting the information from the server and through the JWT token. This is where a lot of my challenges came from because I tried a couple of ways doing it and it never made sense. I was able to use some online MongoDB forums and StackOverflow to help with these challenges. Another challenge that I faced was when I was trying to run my program. I kept getting errors when I tried to run it so I turned to StackOverflow to help me solve my problem with running the program. 

[Link to Original Artifact](https://github.com/brigittemc/brigittemc.github.io/blob/main/Original/Databases%20Artifact.zip)

[Link to Enhanced Artifact](https://github.com/brigittemc/brigittemc.github.io/blob/main/Enhanced/Databases%20-%20Updated%20Artifact.zip)





