---
layout: home
permalink: index.html

# Please update this with your repository name and title
repository-name: e18-co227 Poultry Feed Efficiency Tracking System Group-12
title:
---

[comment]: # "This is the standard layout for the project, but you can clean this and use your own template"

# Poultry Feed Efficiency Tracking System

---
## Project development repository URL:
[https://github.com/cepdnaclk/e18-co227-Poultry-Feed-Efficiency-Tracking-System/tree/development](https://github.com/cepdnaclk/e18-co227-Poultry-Feed-Efficiency-Tracking-System/tree/development)


---

![https://149520306.v2.pressablecdn.com/wp-content/uploads/2021/04/poultry.jpg](https://149520306.v2.pressablecdn.com/wp-content/uploads/2021/04/poultry.jpg)


## Team
-  E/18/017, Aarah J.F., [jfaarah12@gmail.com](mailto:jfaarah12@gmail.com)
-  E/18/177, Khan A.K.M.S., [shamilkhan414@gmail.com](mailto:shamilkhan414@gmail.com)
-  E/18/304, Rishad N.M., [nmrishad6747@gmail.com](mailto:nmrishad6747@gmail.com)

---

## Table of Content
  * [Introduction](#introduction)
  * [Problem Overview](#problem-overview)
      - [Problems in tracking poultry feed efficiency manually](#problems-in-tracking-poultry-feed-efficiency-manually)
      - [Advantages of electronic database approach](#advantages-of-electronic-database-approach)
      - [Why we need a mobile Application?](#why-we-need-a-mobile-application)
      - [Why can't we use existing mobile applications?](#why-cant-we-use-existing-mobile-applications)
  * [Proposed Solution](#proposed-solution)
  * [Features of our Application](#features-of-our-application)
  * [Technology Stack](#technology-stack)
  * [Plan of work](#plan-of-work)
  

## Introduction
poultry industry is the fastest growing livestock industry in Sri Lanka.
for the year 2020 poultry contribute to 0.61 of nominal GDP which is 64 % of the total GDP contribution of Sri Lankan livestock. 
in this scenario one of the most important challenges for this industry is to enhance the productivity while remaining economically and environmentally sustainable

## Problem Overview
As we are mainly focusing on chicken, feeding represents the major cost in raising of both broiler and layer chickens, thus it is a must to track the poultry feed efficiency in order to get the best out of it. 
but there are many problems in tracking this feed efficiency manually. 

#### Problems in tracking poultry feed efficiency manually
 - Difficult to maintain data manually
 - Expensive and time-consuming
 - Difficult to keep track of poultry feeding on daily basis
 - Difficult to compare and contrast between different flocks
 - Difficult to add, modify and search

so to overcome these problems we have planned to implement electronic database approach. Which has any Benefits.

#### Advantages of electronic database approach
 - Make it easier to query, search, filter and retrieve required data.
 - Data is validated before it is entered in electronic databases.
 - Allow centralised use of information.
 - Improved backup and recovery services
 - Improved security

so we are developing a mobile application which uses this kind of database. Now let's see why we need a mobile application?

#### Why we need a mobile Application?

 - Mobile application is portable
 - Easy to access information
 - Mobile notifications allow the user to keep in touch with the industry
 - Time saving solution
 - Mobile apps offer better personalization
 - Interactive engagement

here you may think why can't we use existing mobile applications for this purpose. Because, there are some problems in that.

#### Why can't we use existing mobile applications?
<img src="images/Slide7.PNG" width="600" >

 - Complex
    - Existing applications are not farmer friendly and it's hard to use.
 - Language
    - Existing applications are not in farmers' native language 
 - Native application
    - Exixting applications are not supported for both Android and IOS.
 - Not Customized
    - Existing applications are not customized according to our clients need.

So, in order to overcome these issues, we have proposed some solutions.

## Proposed Solution
<img src="images/Slide8.PNG" width="600" >

- Complex
    - We are designing a easy to use farmer friendly application.
 - Language
    - We are providing three languages to use
       - English
       - Tamil
       - Sinhala 
 - Hybrid application
    - We are developing a hybrid application that will be common for both Android and IOS.
 - Customized
    - We are designing the application in order to fulfull the clients' requirement

## Features of our Application
 - Login
     - Username -Password Login / Signup Page

 - Farmer Registration
     - Enter user’s details : Name , Contact Number (not compulsory)

 - Maintain Farm Details
     - Enter Details according to the following  Hierarchy.
         - Farm	
         - Farm Branch
         - Shed
         - Flock

     - Enter  flock details.
         - Birth date 
         - Start Date 
         - Type (Broilers or Layers)  
         - Strain 
         - Number of chicks,     


 - Monitor feed intake
    - Enter Feed Intake 
       - Flock 
       - Date
       - Food weight .
       System should suggest recommended weight  by calculating ( for that you have stored standard information for each strain . Then you know the standard food   weight for a chick in that strain  , number of chicks in the flock)

 - Maintain  Mortality
    - Enter the number of  deaths  of each flock with the date. 
    - Then the user knows the available chicks in the flock. 

 - Monitor number of eggs - Layers
    - Enter the number of eggs  in each flock per selected date.
    - Can suggest the expected number of eggs  per that flock according  to the strain and  the number of  hens

 - Monitor body weight - Broilers
    - Enter the number chicks and total weight can calculate average body weight  of the selected flock on the selected  date. (Why average weight : Farmers  don’t    try to  weight each chick  one by one , they will weight sample  of chicks and get the varage )


 - Calculate the FCR Layers
     - System should calculate and show FCR when selecting the particular flock using feeding data and number of eggs
  

 - Calculate the FCR Broilers 
     - System should calculate and show FCR when selecting the particular flock using feeding data and body weights

## Technology Stack 
<img src="images/Slide20.png" width="600" >

## Plan of work 
<img src="images/Slide21.png" width="700" >

## Demonstration
<img src="images/demo.gif" width="300" >

## Testing
<img src="images/test.gif" width="300" >
