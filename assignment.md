# Assignment: Exploring Real-World Code Examples
## Introduction
In our everyday lives, we interact with a myriad of software applications, often without realizing the complex code that powers them. From the moment we silence our morning alarm, to checking the weather forecast, or even making an online purchase, software is an integral part of our daily routine. As we embark on our journey to learn coding, it's essential to understand how these applications are built and function. This assignment, designed for beginners, leverages our newly acquired skills in using GitHub and other online repositories. It's an opportunity to explore and connect with the real-world applications of code.

## Objective
Your task is to delve into the world of coding by finding real-life examples of code that power the software applications you use daily. This exercise will help you understand how theoretical coding concepts are applied in practical, real-world scenarios.

## Assignment Details
Research and Exploration: Using online repositories like GitHub, search for code examples that align with the everyday software applications described in the provided prose blurbs.

Link and Line Numbers: For each example, provide the link to the code repository and specify the exact line numbers where the relevant code is located. This will help you practice navigating through code repositories and understanding code structure.

Documentation: Along with each link, write a brief description of what the code does and how it relates to the functionality of the application in the real world.

## Prose Blurbs for Exploration
- Code that specifies when an alarm clock should start making audible sounds.  
- Code for a rocket targeting system.
- File compression utility algorithm.
- Weather forecasting algorithm.
- E-commerce checkout system process.
- Social media post scheduler.
- Fitness app calorie counter.
- Online voting system mechanics.
- Automated email response system.

Alarm Clock Code:
https://github.com/tjtrebat/alarm/blob/a1045898fdb001fc31a7cf805eeb46a4f8f205e1/alarm.py#L9 & lines 37-51
  Lines 37-46 dictates when the alarm will sound by using a tick method. From youtube videos, I have gathered that the tick method is constantly checking the time until the time inserted into the code (or put into the alarm system) matches the time set on the alarm. Lines 37-42 set up the tick method in this code while lines 43-46 dictates when the alarm will sound depending on the input. If True, alarm does not sound but if False, alarm will sound. Futhermore lines 48-51 show what sound will be emited by defining the create_sound function in the previous code.
  This app is crucial for many people as they need an alarm to wake for jobs, school, or any other imporant events. If the code wasn't timed to be perfectly on the dot, many people would be late to their events, affecting how others viewed them and opportunities. Everyone who has access to an alarm uses it at one point in their life. Its needed as humans have evolved to sleep more peacefully and less aware of their surroundings. 

Rocket Targeting System:
https://github.com/123nadeem/Smart-Rocket-System/blob/main/main.py & lines 196-206
  This function calculated the distance between the rocket and the target which then in return gives a value. Lines 196-200 find this distance by using two different functions that calculate map range and distance. Lines 202-203 states that if the function is True and is completed then it will be multiplied by 10 and lines 205-206 state that if the function crashes then the value is True and will be divided by 10. 
  This code is crucial for deliveries of these rockets to be precise because if it isn't, it can hurt the surrounding or people it wasn't intended for. Whilst these machineries are often used for combat, it is also for defense which can be needed in cases.

File Compression Utility Algorithm:
https://github.com/SamirPaulb/FileCompressor/blob/main/main.py & lines 22-29
  Lines 22-23 retrieves the file that is being uploaded and line 25 saves it. Then line 27 creates the path where the compressed file will be stored. Line 28 compresses said file and guides it to the path mentioned before. Finally, line 29 removes the original file. 
    Compressed files are used by those working in offices, schools. everyday life. It is useful because you can save storage, its easier to download and upload, etc. But this code does it in a quick manner which deletes the original file, saving time for the user. 

Weather Forecasting Algorithm:
https://github.com/SalaniLeo/Forecast/blob/master/Forecast/data.py & lines 128-130, 141, & 291
  Lines 128-130 creates a request to get information from a weather app based on the latitude and longitude. Line 141 reloads the app to display said weather information in the city chosen. Line 291 shows the cities weather depending on the city chosen. 
  The weather app is crucial to know when users are planning events or traveling to different cities. This weather forecasting algorithm finds the longitude and latitude of the user location allowing the weather forecasting to be more accurate in their location. 

E-commerce Checkout System Process:
https://github.com/imyds/Ecommerce-Cart/blob/main/Ecommerce-Cart.py & lines 42-85
Lines 42-47 create the function that allows the person to view what is in their cart. Line 49-56 creates two outcomes where if there are no items in the cart then it does not for checkout to proceed & returns but if there are items in the cart then you can proceed to checkout. Lines 58-64 displays the available objects in the cart where the user can add or delete said products. From there, the user can proceed if there are products in the cart and theres none, it does not allow for checkout. Lines 66-82 is what is displayed to the customer which is entering product IDs and quantity. If user inputs invalid ID, the function displays said message and if user accidently puts quantity to 0, the function displays a message that the quantity must be greater than 0. Lines 84-85 allow for a message to be displayed for checkout and a function checks out the customer. 
  This code is very user friendly as it allows the user to constantly edit their cart through out the check out process. This is needed as online shopping has become more common, easy check out encourages more people to use said website. 

Social Media Post Scheduler:
https://github.com/Visualistic-Studios/Media-Manager/blob/release/resources/accounts.py & Lines 422-504
  Lines 422-424 finds location to post and begins the function. Lines 426-429 ensures that the post was made. Lines 447-458 locates users that were mentioned in the post. Line 474 uploads the post. Lines 489-500 creates two outcomes; if the post was sucessful then the published post ID is shown but if not then it states that were was an error.
  This code is useful to allow the user to upload without worrying about the timing of when to post and doing it individualy. While not everyone is a social media influencer, it can benefit those who simply want to post while away from technology.

Fitness App Calorie Counter:
https://github.com/Otryy/Base_fitness_tracker/blob/main/main.py & Lines 68-132
  Lines 63-83 calculate the number of calories burnt by running by using weight of the user, duration of run, mean speed of kilometers ran by hour. Lines 86-105 calculates the number of calories burnt by sportswalking through the same methods. Lines 108-132 calculates the number of calories burnt by swimming through the mean speed (average swimming speed) by taking account of the length of the pool, duration of user, kilometers swam in an hour, and weight of the user.
  Understanding and seeing the numbers of calories burnt motivates the user to keep their workout. The calculations being behind the screen allows for an easy to understand interface for the user. This code can be used by professional athletes or anyone who shows an interest in working out. 

Online Voting System Mechanics:
https://github.com/shah-deep/Online-Voting-System/blob/main/VotingPage.py & Lines 6-54
  Lines 6-21 functions' handels whether the selected vote in the server was successful or a failure which is displayed to the user. Lines 25-34 function allows for the option of the canidates to be displayed. Line 36-54 gives the different canidates options with an image.
  An online voting system is helpful for those who aren't comfortable voting in person or for easy access. This can increase the amount of people voting. The image that is displayed along with the canidate's name makes the options more clear. 

Automated Email Response System:
https://github.com/thekamik/email-automation-with-gpt-ai-and-python/blob/main/email_bot.py & Lines 23-57, 74-98, 100-121
  Lines 23-57 create a function that retrieves unread emails and generates a response using the ai_responder function. Lines 74-98 sends the message after the response is generated by the ai_responder function. Lines 100-121 defines the ai_responder function and messages are generated by asking ai and displaying it for said user. 
  This allows for quick questions or statements to be made without long wait times which in return gives the user a quicker answer and saves companies time from responding to these emails. 

Verification of Username/password:
https://github.com/Sommmie/User_Verification_System/blob/master/user_verification_system.py & Lines 9-13, 18-27
  Lines 9-13 registers the user for the first time and if the confirmation password and password match, an account is created. If it does not, it prints "Enter a corresponding password". Lines 18-27 logins the user if they have an already existing account. If password is entered in wrong then it prints to enter a valid password or if the user miswrites their username then it prints to enter the correct username. 
  There are millions of websites everyone uses and signing in whether for personal, work, or school use is a necessity for security. Therefore, everyone is bound to sign in or up for a website.

Calender Reminders:
https://github.com/kamaljohnson/calender.py/blob/master/calender.py & Lines 37, 51-55
  Lines 37 displayes notes created for the specific date, month, or year that can be reminders, holidays, or other events. Line 51-55 allows the user to add a note/reminder or view all the reminders/events.
  I use reminders on my calender daily to remind myself to get to certain classes, assignment due dates, or personal events. It gives the user the ability to make room for information that is relevant now and not for the future and ensures that they will remember future events.

Period Cycle Tracking:
https://github.com/cilab-ufersa/period_cycle_prediction/blob/main/period_cycle_prediction/utils/utils.py & Lines 8-45, 84-105, 108-132, 181-196
  Lines 8-45 creates a function that generates basic cucle data for the duration in between each period. Lines 84-105 creates a function that determins the lengths of each period and cycle. Lines 108-132 creates a function that allows for prediction of cycles and periods. Lines 181-196 creates a memory for the algorhythm which can adjust itself (this assumption comes from line 183 where it states LSTM which when googled is short term memory)
  When around half the population are women and most women have cycles, I find this code to be important as knowing why you feel a certain way due to horomones can be validating. Addtionally, the predictions can help women plan events better but most of all understand their bodies. 


Document Title: "Exploring Code in Daily Life"
Content Structure: For each of the nine blurbs, include a heading with the blurb title, followed by your findings (link and line numbers) and a brief description. Also, do the same for 3 kinds of tools you use every day (for example: how the email app knows there are new messages, how my calendar adds new items, how my video game authenticates my user/password)
Length: No more than two paragraphs per blurb.
Evaluation Criteria
Accuracy: Correctly identifying relevant sections of code.
Clarity: Clear and concise descriptions of how the code functions.
Research Skills: Ability to effectively use online resources like GitHub.
