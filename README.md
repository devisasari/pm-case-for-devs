# PM Case For Developers

## About

## PM Case For Developers
In your first project at Havas Company, you are positioned in the front-end development of a website for a local, global money transfer and payment platform. The website includes the following functionalities:
1. User Login Screen 
- An Individual Login button will be added to the main page of the website. The customer will login by entering his/her cell phone or e-mail address and password.
- There should be Get Password / Forgot Password options for mobile phone and E-mail login, 'Remember Me' for Unremembered User login, and 'Forget Me' for Remembered User login.
       2. Forgot Password Flow
- The Forgot Password screen will be entered by selecting the Forgot Password option from the user login screen. To create a password, the customer enters his/her TR ID and mobile phone number and a verification code is sent to his/her phone. The customer who enters the verification code is directed to the new password creation screen.
- On the new password creation screen, the customer enters the new password and the new password repetition. The customer is shown a confirmation screen that the password has been successfully changed.
     3. Language Option
- It is also desired to offer 3 language options to the customer on the website login screens. The login screen should be updated in the language chosen by the customer.
     4. Home Screen (Dashboard)
- The homepage screen of the website should have a menu structure where the customer can access all functions, areas where the customer can view all accounts and account balances, exchange rates, campaigns, notifications, a search field where the customer can search, a button to log out, last successful and failed login fields.
     5. Exchange Rate Display
- Exchange rate information should be accessible to users on the home page.
- Customers should be able to access EUR/TRY, USD/TRY, GBP/TRY and EUR/USD information via the Currency field. 
- Last Update and Date/Time should be available.
    6. Campaigns
- When the customer clicks on the Campaign icon on the main page, all defined campaigns will be listed with a visual and a description below. With the "All Campaigns" button at the bottom, a page specially prepared for Campaigns will open. On this page, customer-specific campaigns and general campaigns will be shown in separate sections.
    7. My Settings (Password Update, Information Update)
- When the My Settings step on the home page is clicked, the customer will be presented with the Notification Settings, Information Update and Password Update options.
- On the Password Update screen, the customer will enter the Current Password, New Password and New Password (Again) respectively. Customers who enter the Current Password correctly and meet the New Password conditions will have their password changed.
- In the Information Update step, customers are asked to update their Personal Information, Contact Information and Address Information on the website. On the Personal Information screen, the customer fills in the Education Status, Social Security Institution, Type of Work, Work Area and Position sections and selects the Next option. After selecting Next, the customer is directed to the Completed Transaction screen. On the Contact Information screen, the customer fills in the Mobile Phone, Home Phone, Work Phone and E-mail Address sections. After selecting Next, the customer is directed to the Your Transaction is Completed screen. In the Address Information section, the customer can update the address in the system or add a new address from the Add Address option. After clicking Next, you will be redirected to the Completed Transaction screen.
      8. Money Transfer
- With the money transfer feature, member customers can transfer money between themselves 24/7, free of charge in TRY, USD and EUR currencies. Money is sent by entering the Mobile Phone or Account Number. When the transaction is successful, the Transaction Success screen is displayed.
- There should be a structure where saved transactions can be viewed and deleted.
      9. Domestic Transfer
- With Domestic Money Transfer, customers can make TL EFT to the account and card, and 24/7 FX Money Transfer to USD and EUR accounts at contracted domestic banks.
     10. International Transfer (Name-to-Account)
- The user first selects the country. The user selects one of the Send to Account and Send to Name options. If the "Send to Name" option is selected, the user selects the account and the amount to which the money will be sent, then enters the Recipient's Name and Surname, Mobile Phone and Description. The transaction is executed. If the "Send to Account" option is selected, the user enters the Recipient Account Number. Recipient Cell Phone and Description. These fields are optional. -After the entries are made, a confirmation screen opens. Recipient Name and Surname, Description, Transaction Amount, Expense, Applied Exchange Rate, Total Amount to be taken from the Account and Amount to be paid to the Recipient are displayed. All information will be passive on the screen, the user gives confirmation.

11. Cash Check
- With the Cash Check feature, customers can create a unique reference number and withdraw money from authorized branches in Turkey and abroad.
     12. Request Money by Message
- The user enters the amount they will request on the website, the membership account number and phone number of the person they will request. After confirming the transaction, a notification goes to the person from whom money is requested. When the requested person enters the system and confirms the transaction, the requested amount is sent to the user's account.
     13. Where is My Money?
- The customer can query the status of his/her transaction by entering a reference number with the Where's My Money feature.
      14. Bill Payments
- By adding the "Invoice Payments" function to the brand website, the customer will be able to pay the invoices of the contracted institutions instantly by using their membership accounts, save their invoice payments and make instant payments from their saved payments.
XXX payment systems project can be characterized as a project where requests can change frequently during the development process due to the new establishment of the company. It is foreseen that a new function will be added to the website during the development process of the project. The scope of the feature to be added is not yet clear.
Additional Function: QR Payment
- The customer can scan the QR generated on this screen or select from the Gallery and scan the QR.
- After scanning the QR, on the next screen, the customer determines from which account he/she will make the payment and writes a transaction description if he/she wishes. If the transaction amount and the account from which the money will be received are different, the FX model is run and the applied exchange rate information is displayed on the screen. (For example: If the payment of a QR of 150TL is made from a USD account, the "Amount to be Received from Account" is shown as 10 USD and the applied exchange rate is 15.00). On the next screen, the transaction details are shown and confirmation is given and the successful screen is displayed.

REQUIREMENTS 
1) How should the "Tech Stack" of the project be created?
2) Which project management methodology should be used for the XXX Web site project?  Explain your choice with reasons.
3) A project plan needs to be drawn up for the XXX website development. You should draw up efforts for the functions involved in the project and submit them to your project manager. The project plan should include the order in which the functions should be developed and how long they should be developed.
4) Determine the length and number of sprints for the XXX website.

## SOLVING THE CASE

### Table of Contents

TECH STACK ............................................................................................................................................. 2
Why React.js? ...................................................................................................................................... 3
Why not Vue.js or Angular?................................................................................................................. 3
Why Node.js? ...................................................................................................................................... 4
Why Express.js? ................................................................................................................................... 4
Why MongoDB? .................................................................................................................................. 5
Why AWS? ........................................................................................................................................... 6
PROJECT MANAGEMENT METODOLOGY: AGILE ..................................................................................... 8
STORY POINTS ....................................................................................................................................... 10
SPRINTS ................................................................................................................................................. 17
BONUS: USER STORIES .......................................................................................................................... 18

TECH STACK

For www.flexchange.com, a tech stack that includes the following components should be used: 

Front-end: HTML, CSS, JavaScript, React.js, Redux
Back-end: Node.js, Express.js
Database: MongoDB
Cloud Platform: AWS (Amazon Web Services)

The front-end technologies chosen for this tech stack are HTML, CSS, and JavaScript, as they are the most widely used and established web development technologies. React.js and Redux are chosen for their scalability and flexibility, allowing for the rapid development of complex user interfaces.

The back-end technologies chosen for this tech stack are Node.js and Express.js. Node.js is a powerful JavaScript framework that allows for fast and efficient development of web applications. Express.js is a popular web application framework that is used for building dynamic websites and web applications.

The database chosen for this tech stack is MongoDB. MongoDB is a powerful and reliable NoSQL database that is well suited for web applications. 

The cloud platform chosen for this tech stack is AWS (Amazon Web Services). AWS provides a comprehensive and reliable cloud computing platform that is suitable for web applications of all sizes.

Why React.js?

1. React.js is fast and lightweight, making it ideal for developing dynamic web applications.
2. React.js is highly extensible, allowing developers to easily add custom features and functionality to their applications.
3. React.js is open source and free to use, making it a cost-effective solution for web development.
4. React.js provides a powerful component-based architecture that makes it easy to create and maintain complex user interfaces.
5. React.js allows developers to create reusable components, making it easy to quickly develop and maintain web applications.
6. React.js uses a virtual DOM (Document Object Model), making it fast and efficient when rendering large amounts of data.
7. React.js is well-documented, making it easy for developers to quickly learn and start building with React.
8. React.js is supported by a large and active community of developers, making it easy to find help and support.
9. React.js is built on top of JavaScript, allowing developers to take advantage of the features of JavaScript in their applications.
10. React.js supports server-side rendering, making it easy to create SEO-friendly web applications.

Why not Vue.js or Angular?

1. React.js is more flexible than Vue.js and Angular, allowing developers to easily customize their web applications.
2. React.js has a large and active community of developers, making it easy to find help and support for web development projects.
3. React.js is more stable than Vue.js and Angular, making it easier to maintain and update web applications.
4. React.js is more popular than Vue.js and Angular, making it easier to find developers with experience in React.
5. React.js is more performant than Vue.js and Angular, making it faster and more efficient for web applications.

Why Node.js?

Node.js is a powerful JavaScript framework that allows for fast and efficient development of web applications.
Node.js is better suited for real-time web applications, as it is event-driven and non-blocking.
Node.js and Express.js are both lightweight and can be scaled easily.
Node.js is lightweight and is better suited for microservices architectures.
Node.js is faster than others as it is built on Chrome’s V8 JavaScript engine.
Node.js and Express.js provide a wide range of tools and libraries for completing complex web development tasks.
Node.js and Express.js are both open-source and have an active community of developers providing support and resources.

Why Express.js?

1. Express.js is fast and lightweight, making it ideal for developing web applications with minimal overhead.
2. Express.js is highly extensible, allowing developers to easily add custom features and functionality to their web applications.
3. Express.js is open source and free to use, making it a cost-effective solution for web development.
4. Express.js provides a robust routing system that makes it easy to define and handle routes for web applications.
5. Express.js provides a powerful templating system that makes it easy to create dynamic HTML pages.
6. Express.js supports middleware, which allows developers to easily add custom functionality to their applications.
7. Express.js supports the MVC (Model-View-Controller) pattern, making it easy to develop structured web applications.
8. Express.js is well-documented, making it easy for developers to quickly learn and start building with Express.
9. Express.js is built on top of Node.js, allowing developers to take advantage of the features of Node.js in their web applications.
10. Express.js has a large and active community of developers, making it easy to find help and support for web development projects.
11. Express.js is a popular web application framework that is used for building dynamic websites and web applications.

Why MongoDB?

1. MongoDB is highly scalable, allowing for the rapid development of large-scale web applications.
2. MongoDB is highly reliable, providing a robust and secure database system for web applications.
3. MongoDB is easy to use, making it a great choice for developers of all skill levels.
4. MongoDB is open source and free to use, making it a cost-effective solution for web development.
5. MongoDB supports a wide range of data types, making it easy to store and query data.
6. MongoDB provides a powerful query language, making it easy to query and manipulate data.
7. MongoDB supports indexing, allowing for faster query performance.
8. MongoDB supports sharding, allowing for the horizontal scaling of databases.
9. MongoDB is well-documented, making it easy for developers to quickly learn and start building with MongoDB.
10. MongoDB has a large and active community of developers, making it easy to find help and support for web development projects.
When compared to other NoSQL databases, MongoDB stands out for its scalability, reliability, ease of use, and cost-effectiveness. MongoDB also provides powerful query language, indexing, sharding, and a large and active community of developers. These features make MongoDB an ideal choice for web development projects.
Why AWS?

1. Scalability: AWS provides a highly scalable cloud platform that can easily scale up or down to meet the needs of the project.

2. Reliability: AWS is a reliable cloud platform that provides high availability and uptime.

3. Security: AWS provides a secure cloud platform with advanced security features such as encryption, identity and access management, and more.

4. Cost-effectiveness: AWS is a cost-effective cloud platform that offers competitive pricing and discounts.

5. Flexibility: AWS provides a flexible cloud platform that can be used to develop and deploy applications of any size.

6. Global Reach: AWS has a global presence with data centers located in multiple regions around the world.

7. Support: AWS provides a comprehensive support system with a wide range of resources and tools.

8. Integration: AWS provides a wide range of integration options with other cloud platforms and services.

9. Automation: AWS provides a range of automation tools that can be used to automate tasks such as deployment, scaling, and more.

10. Innovation: AWS is constantly innovating and introducing new features and services to its cloud platform. 
PROJECT MANAGEMENT METODOLOGY: AGILE

I would recommend using the Agile project management methodology.
1. Agile allows for changes to the project plan as needed. Since the scope of the project is expected to change throughout the development process due to the new establishment of the company, Agile is the ideal choice since it allows for ongoing adjustments and changes to the project plan.

2. Agile encourages collaboration. The Agile methodology emphasizes collaboration between the development team and the customer, which is necessary for the successful completion of the www.flexchange.com project.

3. Agile encourages frequent feedback and adjustments. Agile emphasizes the importance of frequent feedback and adjustments throughout the development process, which will be beneficial for the www.flexchange.com project since it will allow the team to quickly identify any issues and make any necessary changes.

4. Agile allows for quick development and implementation of new features. Agile allows for the development team to quickly develop and implement new features, which is beneficial for the www.flexchange.com project as it will allow the team to quickly add the new features that are desired.

5. Agile is a proven and successful methodology. Agile is a proven and successful methodology that has been used for many successful projects over the years. This makes it a great choice for the www.flexchange.com project, as it has a track record of success.
6. Agile allows for testing early and often. Agile encourages frequent testing throughout the development process, which will be beneficial for the www.flexchange.com project as it will allow the team to quickly identify any issues and make any necessary changes.

7. Agile allows for rapid delivery. Agile encourages rapid delivery of features and functionality, which is beneficial for the www.flexchange.com project as it will allow the team to quickly deliver the desired features and functionality.

8. Agile encourages continuous improvement. Agile emphasizes continuous improvement throughout the development process, which is beneficial for the www.flexchange.com project as it will allow the team to quickly identify any issues and make any necessary changes.

9. Agile encourages transparency. Agile encourages transparency between the development team and the customer, which is necessary for the successful completion of the www.flexchange.com project.

10. Agile is cost-effective. Agile is a cost-effective project management methodology, which is beneficial for the www.flexchange.com project as it will allow the team to complete the project within the budget.
 
STORY POINTS

1. User Login Screen: 2 story points, 1 day
2. Forgot Password Flow: 3 story points, 2 days
3. Language Option: 2 story points, 1 day
4. Home Screen (Dashboard): 5 story points, 2 days
5. Exchange Rate Display: 3 story points, 2 days
6. Campaigns: 4 story points, 2 days
7. My Settings (Password Update, Information Update): 5 story points, 3 days
8. Money Transfer: 5 story points, 3 days
9. Domestic Transfer: 3 story points, 2 days
10. International Transfer (Name-to-Account): 5 story points, 2 days
11. Cash Check: 3 story points, 2 days
12. Request Money by Message: 3 story points, 2 days
13. Where is My Money?: 3 story points, 2 days
14. Bill Payments: 4 story points, 2 days
15. QR Payment: 3 story points, 2 days

Total: 45 story points, 22 days

1. User Login Screen: 2 story points. 
1.1. Story Point:  This story point involves the development of a login button on the main page of the website, where the customer can enter their cell phone or e-mail address and password. 
1.2. Story Point: This story point involves the development of options for the user to reset their password, including Get Password/Forgot Password options for mobile phone and E-mail login, 'Remember Me' for Unremembered User login, and 'Forget Me' for Remembered User login.

2. Forgot Password Flow: 3 story points. 
2.1. Story Point: This story point involves the development of the Forgot Password screen, which the customer can access by selecting the Forgot Password option from the user login screen. 
2.2. Story Point: This story point involves the development of the customer entering their TR ID and mobile phone number, and a verification code being sent to their phone. 
2.3. Story Point: This story point involves the customer entering the new password and new password repetition, and being shown a confirmation screen that the password has been successfully changed.

3. Language Option: 2 story points. 
3.1. Story Point: This story point involves the development of providing 3 language options to the customer on the website login screens.
3.2. Story Point: This story point involves the development of the login screen being updated in the language chosen by the customer.

4. Home Screen (Dashboard): 5 story points. 
4.1. Story Point: This story point involves the development of a menu structure on the homepage screen, where the customer can access all functions. 
4.2. Story Point: This story point involves the development of an area on the homepage screen, where the customer can view all accounts and account balances. 
4.3. Story Point: This story point involves the development of an area on the homepage screen, where the customer can view exchange rates. 
4.4. Story Point: This story point involves the development of an area on the homepage screen, where the customer can view campaigns. 
4.5. Story Point: This story point involves the development of a search field, logout button, last successful and failed login fields on the homepage screen. 

5. Exchange Rate Display: 3 story points. 
5.1. Story Point: This story point involves the development of providing exchange rate information to users on the home page. 
5.2. Story Point: This story point involves the development of the customer being able to access EUR/TRY, USD/TRY, GBP/TRY and EUR/USD information via the Currency field. 
5.3. Story Point: This story point involves the development of the last update and date/time being available. 

6. Campaigns: 4 story points. 
6.1. Story Point: This story point involves the development of the customer being able to view all campaigns with a visual and description. 
6.2. Story Point: This story point involves the development of a page specially prepared for campaigns. 
6.3. Story Point: This story point involves the development of customer-specific campaigns and general campaigns being shown in separate sections. 
6.4. Story Point: This story point involves the development of a “All Campaigns” button at the bottom of the page. 

7. My Settings (Password Update, Information Update): 5 story points. 
7.1. Story Point: This story point involves the development of the customer being presented with Notification Settings, Information Update and Password Update options when they click on the My Settings step on the home page. 
7.2. Story Point: This story point involves the development of the customer being able to update their password by entering their Current Password, New Password and New Password (Again). 
7.3. Story Point: This story point involves the development of the customer being able to update their Personal Information, Contact Information and Address Information on the website. 
7.4. Story Point: This story point involves the development of the customer being able to add a new address from the Add Address option. 
7.5. Story Point: This story point involves the development of the customer being shown a confirmation screen when their information is successfully updated. 

8. Money Transfer: 5 story points. 
8.1. Story Point: This story point involves the development of the customer being able to transfer money between themselves 24/7, free of charge in TRY, USD and EUR currencies. 
8.2. Story Point: This story point involves the development of the customer being able to send money by entering the Mobile Phone or Account Number. 
8.3. Story Point: This story point involves the development of the customer being shown a Transaction Success screen when the transaction is successful. 
8.4. Story Point: This story point involves the development of a structure where saved transactions can be viewed and deleted. 
8.5. Story Point: This story point involves the development of the customer being able to select the currency for money transfer. 

9. Domestic Transfer: 3 story points. 
9.1. Story Point: This story point involves the development of the customer being able to make TL EFT to accounts and cards. 
9.2. Story Point: This story point involves the development of the customer being able to make 24/7 FX Money Transfer to USD and EUR accounts at contracted domestic banks. 
9.3. Story Point: This story point involves the development of the customer being able to select the currency for domestic money transfer. 

10. International Transfer (Name-to-Account): 5 story points. 
10.1. Story Point: This story point involves the development of the customer being able to select a country to send money to. 
10.2. Story Point: This story point involves the development of the customer being able to select one of the Send to Account and Send to Name options. 
10.3. Story Point: This story point involves the development of the customer being able to enter the Recipient's Name, Mobile Phone, and Description if the “Send to Name” option is selected. 
10.4. Story Point: This story point involves the development of the customer being able to enter the Recipient Account Number, Recipient Cell Phone and Description if the “Send to Account” option is selected. 
10.5. Story Point: This story point involves the development of the customer being shown a confirmation screen with the Recipient Name and Surname, Description, Transaction Amount, Expense, Applied Exchange Rate, Total Amount to be taken from the Account, and Amount to be paid to the Recipient. 

11. Cash Check: 3 story points. 
11.1. Story Point: This story point involves the development of the customer being able to create a unique reference number. 
11.2. Story Point: This story point involves the development of the customer being able to withdraw money from authorized branches in Turkey and abroad. 
11.3. Story Point: This story point involves the development of the customer being able to select the currency for Cash Check. 

12. Request Money by Message: 3 story points. 
12.1. Story Point: This story point involves the development of the customer being able to enter the amount they will request on the website. 
12.2. Story Point: This story point involves the development of the customer being able to enter the membership account number and phone number of the person they will request money from. 
12.3. Story Point: This story point involves the development of a notification being sent to the person from whom money is requested when the transaction is confirmed. 

13. Where is My Money?: 3 story points. 
13.1. Story Point: This story point involves the development of the customer being able to query the status of their transaction by entering a reference number. 
13.2. Story Point: This story point involves the development of the customer being able to view the details of the transaction. 
13.3. Story Point: This story point involves the development of the customer being able to select the currency for the Where is My Money feature. 

14. Bill Payments: 4 story points. 
14.1. Story Point: This story point involves the development of the customer being able to pay the invoices of contracted institutions instantly by using their membership accounts. 
14.2. Story Point: This story point involves the development of the customer being able to save their invoice payments. 
14.3. Story Point: This story point involves the development of the customer being able to make instant payments from their saved payments. 
14.4. Story Point: This story point involves the development of the customer being able to select the currency for Bill Payments. 

15. QR Payment: 3 story points. 
15.1. Story Point: This story point involves the development of the customer being able to scan a QR generated on the screen or select from the Gallery and scan the QR. 
15.2. Story Point: This story point involves the development of the customer being able to determine from which account they will make the payment. 
15.3. Story Point: This story point involves the development of the customer being able to write a transaction description if they wish.
 
SPRINTS

I would recommend having 3 sprints of 8 days each. The first sprint would include tasks 1-5 (15 story points), the second sprint would include tasks 6-10 (20 story points), and the third sprint would include tasks 11-15 (10 story points). This would allow for the project to be completed in a timely manner while still allowing for adequate time to complete each task.
I calculated the length and number of sprints for the www.flexchange.com website project by first determining the total number of story points (45) and the total number of days (22). I then divided the total number of story points by the total number of days to get an average of 2 story points per day. I then used this average to determine the length of each sprint. I determined that 8 days would be the optimal length for each sprint, as it would allow for enough time to complete each task while still allowing for the project to be completed in a timely manner. I then divided the total number of story points by 8 to get the number of sprints (3). This would allow for the project to be completed in 3 sprints of 8 days each.
 
BONUS: USER STORIES

1. As a user, I want to be able to log in to the website with my cell phone or email address and password.
2. As a user, I want to be able to reset my password using my mobile phone number and verification code.
3. As a user, I want to be able to select different language options on the website login screens.
4. As a user, I want to be able to access all functions, view accounts and balances, exchange rates, campaigns, notifications and log out from the homepage.
5. As a user, I want to be able to access EUR/TRY, USD/TRY, GBP/TRY and EUR/USD information from the currency field.
6. As a user, I want to be able to view all campaigns with a visual and description.
7. As a user, I want to be able to update my personal information, contact information and address information on the website.
8. As a user, I want to be able to transfer money between myself 24/7, free of charge in TRY, USD and EUR currencies.
9. As a user, I want to be able to make TL EFT to accounts and cards, and 24/7 FX Money Transfer to USD and EUR accounts at contracted domestic banks.
10. As a user, I want to be able to send money to accounts or names in different countries.
11. As a user, I want to be able to create a unique reference number and withdraw money from authorized branches in Turkey and abroad.
12. As a user, I want to be able to request money from another user by message.
13. As a user, I want to be able to query the status of my transaction by entering a reference number.
14. As a user, I want to be able to pay invoices of contracted institutions instantly by using my membership accounts.
15. As a user, I want to be able to make payments to another user by scanning their QR code.
