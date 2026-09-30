# Requirements

This document will cover the requirements for the basic setup of the website. In a nutshell, we're going to be using a java web application that will be deployed to a VM on Azure and eventually connect to a database for full functionality.

## Details

Lightstone Digital is an online consulting agency that offers digital services for small business owners. This web application is going to have a home page, about, locations and contact information, an online store, ect. Customers need to be able to register, log in, look up their purchase history, ubdate their profile. The online store needs to include a purchasing function that accepts payments, allows customers to leave reviews, and has controlled inventory. While this project as a whole will eventually integrate with the relational database project, for now this focuses on the basic set up. This set up will include for now a maven/java web application, our GitHub repo, GitHub actions to deploy a pipeline, a Web server on Microsoft Azure, Java JDK/JRE for running the Web App, Tomcat installed on the server for running the Web App, and logs in our repo to record issues.

This portion of the project simply focuses on the initial setup in GitHub, Azure, ect. This does not include any html or css. That will be the next portion that will focus on designing the look and feel.