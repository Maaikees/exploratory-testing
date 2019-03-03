>“In the fields of observation, chance favours only those minds which are prepared.” - Louis Pasteur

Exploratory Testing is a wonderful addition to automated testing because it manages to uncover a different type of information. Instead of testing with a 100% black and white 'expected result', the testing is structured around a Charter / Test Idea. Exploratory Testing is not structureless or without any indication of purpose or risk. In this article I will tell you more about different styles that you can use for an exploratory test session.

## Characteristics of different styles
Not every style has the same goal. Sometimes an exploratory test is mainly aimed at generating questions in order to get more clarity. Sometimes it is a method to look for issues. Whichever style you choose, realize that it includes a goal and purpose. Does a style focus on:

* Method or ask questions, or use of the product?

* Methodology or describing and analyzing the product?

* The details of the product?

* The patterns of use in the product?

* The environments through which the product passes (UI, API, Database)



### Example Workflow
You want to explore.

Step 1: think of the goal, why are you going to explore? Write a charter for this, or at least make sure you have a clear vision. This creates structure.

Step 2: think with which style (see for styles below in this article) you can best reach your goal.

Step 3: alone or together? Are you going to do it on your own or is it better to test together with someone?

Step 4: do your test session (for which you do not necessarily have to use the product, modeling an application for testing is also testing).

Step 5: After you have finished (timebox), reflect on what you have found and discuss any important outcomes with the relevant people.



## Styles
### Survey Test
A form of testing with the primary goal of learning more and learning about the design, purpose, testability and possibilities of the product. Survey testing is pretty informal and playful. You only have a separate mission. During a survey test you can get several ideas for deeper test sessions.

When do you use this option? For example, when a user story is roughly built and ready for a first test. The sooner you can do a survey test, the better, because very superficial problems quickly come to light.

### Hunches
emotion: you have a feeling that something is wrong somewhere and you want to look into it further. You build up questions and search for answers. You have heard a gossip in the corridor about a part of the application and will investigate that.

Testing is not boolean, emotions also have a place. The software is finally made by people and bias is possible.

### Model-based

Examples:

* architecture diagrams  
* data relationships  
* procedural relationships  
* requirements (requirements are always a model !! Never a representation of reality that is 100% complete)  
* functional relationship  
* failure models  


### Risk based  
You have defined a risk in advance and devote a test session specifically to that risk.

For example: in a fictional mobile app we still support reasonably old devices such as the iphone 4s and the iphone 5. We might consider it a risk that the app does not perform well on such old devices and always test a user story at least on such a device. Another example: for a web app, you can consider that not everyone has a super-fast computer at home and since javascript can do more and more beautiful tricks that are done client-side, how does the web app perform on a slow computer? Or on a not so great smartphone?

### Heuristic based
Grab one of the many heuristics and explore it. For ideas check out the Test Heuristics Cheat Sheet.

### Testing Tours  

Go through the product or a predefined part of the product by means of personas.
* couch potato (the lazy user who wants to go through something as quickly as possible with as few clicks as possible)
* the old lady (the average old customer who does not understand much of technology)
* fast and furious, the most impatient user!
* complexity tour (looking for the most complex features of the product)
* variability tour (applying as much variety in your tests as possible, in every dimension)
* clubbing tour: check the performance (for example with tools such as Postman or Gatling)
* follow the data: follow the data through the system. Check, for example, whether data correctly goes through all systems and everywhere in a correct manner.


## Support Tools
API: Postman  
Browser: Inspector, Postman, Bug Magnet, color picker, empty cache/cookies, Spectrum  
Logging/Proxy: Charles, Fiddler, SOAP  
Security: OWASP ZAP, Burp Suite  
Performance/load: Gatling, Jmeter  
Mobile: Genymotion, Android Studio, xcode  


### Resources
[Big List of Naughty Strings](https://github.com/minimaxir/big-list-of-naughty-strings)  
[Test Heuristics Cheat Sheet](http://testobsessed.com/wp-content/uploads/2011/04/testheuristicscheatsheetv1.pdf)  
[Exploratory Testing Styles](http://www.testingeducation.org/course_notes/amland_stale/cm_200212_exploratorytesting/exploratorytesting_4_styles.pdf)

