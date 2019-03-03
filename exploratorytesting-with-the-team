
# Exploratory Testing with the Team 

## What is Exploratory Testing
Tested = checked + explored

> "With a test script, you miss the same things every time"

[Wikipedia](http://en.wikipedia.org/wiki/Exploratory_testing) actually has a nice little paragraph explaining the essential message:

> Exploratory testing is an approach to software testing that is concisely described as simultaneous learning, test design and test execution. Cem Kaner, who coined the term in 1993, now defines exploratory testing as "a style of software testing that emphasizes the personal freedom and responsibility of the individual tester to continually optimize the quality of his/her work by treating test-related learning, test design, test execution, and test result interpretation as mutually supportive activities that run in parallel throughout the project."

> While the software is being tested, the tester learns things that together with experience and creativity generates new good tests to run. Exploratory testing is often thought of as a black box testing technique. Instead, those who have studied it consider it a test approach that can be applied to any test technique, at any stage in the development process. The key is not the test technique nor the item being tested or reviewed; the key is the cognitive engagement of the tester, and the tester's responsibility for managing his or her time.

In essence exploratory testing is about designing, executing and analyzing your tests as you go. It requires deep thinking skills, focus and alertness. In agile testing, exploratory testing has an important role. Ideally it is used in addition to your automated core tests, in which you check that the basics of your application are working.  

### How do you do Exploratory Testing 
#### Tasklist for an ET session
* explain to newcomers what Exploratory Testing is (10 min) 
* decide on test goal for the session
* create charters (5 - 10 min) 
* do the testing session (30 min) 
* debrief phase: discuss the defects and decide with PO which ones need to be solved 
* optional: do another testing and debrief session

### Explaining to newcomers what ET is
*Focus*  
A pitfall for beginning Exploratory testers is the lack of focus. The idea is that you stick to your charter in one testing session. But you cannot help but notice unrelated things. Try not to get distracted by that. A tip is to document something you notice that isn't related to your charter as inspiration for your next testing session! When you've done that, bring your focus back to the charter at hand. 

Extra tip for developers who are beginners in exploratory testing: don't start debugging when you've found a defect in the testing session. Stick to the charter, write down ideas on why or where the defect is manifesting itself but KEEP GOING. Stay focussed. It's only 30 minutes maximum.

To sum it up: By concentrating you are able to observe the details. You will be alert of subtle clues about the system or application under test. Concentration is a limited source, so use it wisely.

*Together or alone?*  
* Pair testing is really effective; two pairs of eyes spot more than one. Be careful not to get out of focus though. Go sit in a different room away from your team to keep focussed.
* Doing a session alone is also good. Documenting well is really important! No extra pair of eyes to check your work.
* Making charters works wonders with a group of people.
* Debriefing is most effective when the ppl who need to fix the defect are there. And maybe the Product Owner if they are interested in the outcome.
* It's also a good idea to get people out of their comfort zone. Get back-end devs to test the front-end and vice versa

*Timeboxing*  
Timeboxing is of paramount importance. When you do an ET session, set a timebox for 30 minutes maximum. You probably cannot hold deep focus for longer than that. Spend 5 minutes creating some charters, then test for 30 minutes and debrief. Of course after you've completed one testing cycle, nobody stops you from doing another! As long as you are aware of the limits of your concentration all is well. 

*What can you test with ET*  
Anything. It isn't limited to the front-end. You can test databases, API's, the back-end, anything really.

### Create charters
It is recommended that you use Charters for your ET session. Charters help you by giving you focus. A typical ET charter has this format:

Explore **target** (e.g.: a feature, a requirement, a quality attribute)   
With **resources** (e.g: a tool, a data set, a technique, a configuration)    
To discover **information** (e.g: what are you hoping to find out)  


An example charter would be:

Explore using the mobile app  
with a bad connection  
to discover if the app still works as expected

 
As you can see, this charter focusses on finding issues when a user has a limited internet connection. It is aimed to find incorrect error messages or odd behaviour that might need to be fixed. 

Making a good charter has a couple of typical pitfalls. Avoid making the charter too broad, or too narrow. You can make charters when you are attending refinements, planning sessions or when you hear a discussion that makes you go like 'oh, there might be issues in this part of the application, let's explore that!'. The charters are there to help you avoid turning ET into Monkey Testing (where you just wander around an application without a sense of direction; your only hope is to randomly stumble upon bugs).

### Do the testing session
#### Document what you're doing
At the end of the session, there is a short debrief. You can discuss the defects you've found with the team and decide which ones need to be solved. Defects should be reproducible, but since you don't script your scenario's you should document what you're doing during the session. You should be able to show others how you've produced a defect, else it can't be reproduced nor solved. The documentation is for yourself, the only reportable outcome of the ET session are defects and steps to reproduce them. So feel free to write down anything that is important for you, the way you like it. There are no rules as to how, as long as you do it.

So please note: THIS IS REALLY IMPORTANT. Unless you are an experienced exploratory tester you're going to forget what you've done. Give yourself time to learn how Explorarory Testing works and help yourself and your team by DOCUMENTING.  

### Debrief
A debrief is a short discussion between the Product Owner and the team about the session. Jonathan Bach uses the aconymn PROOF to help structure the debriefing. PROOF stands for:-

Past. What happened during the session?
Results. What was achieved during the session?
Obstacles. What got in the way of good testing?
Outlook. What still needs to be done?
Feelings. How does the tester feel about all this?
Don't forget to do a debrief, it is really important. Here you can decide with the team and PO which bugs are worth solving, for instance.

### Want to know more?
Read the book ['Explore It!' by Elisabeth Hendrickson](https://www.amazon.com/Explore-It-Increase-Confidence-Exploratory/dp/1937785025)  
Use this [Test Heuristics Cheat Sheet](http://testobsessed.com/wp-content/uploads/2011/04/testheuristicscheatsheetv1.pdf) during your test sessions  
Read James' Bach [blog](http://www.satisfice.com/articles/what_is_et.shtml) about the subject  
Look at [this presentation](http://www.kaner.com/pdfs/QAIExploring.pdf) that explains the difference between scripted testing and ET  
Excellent [blog post](http://www.satisfice.com/blog/archives/1509) "Exploratory Testing 3.0" about the evolution of Exploratory Testing and Scripted Testing
 

### Quotes
> When I was a kid, I would use a hammer to set my tent stakes or to pound nails into two-by-fours to build tree forts. I thought I could use the hammer for anything. If I hit a board hard enough, it would break, and I wouldn’t need to use the saw. If I hit the plywood just right, I could punch a hole through the board without using the drill.

> Obviously, using one tool to do it all may get quick results, but it won’t look pretty. Many in the testing industry use a similar single-tool approach, attempting to solve every problem using automated testing. No time? Slap some automation on your software and ship it out the door. No money? Cut down on testers and have an automation engineer do it all.

>While I’m a proponent of automation in its proper context, you still need the interactive tester to dig deep using exploratory testing and find bugs. Let’s look into what exploratory testing is and a method to find great exploratory testers.

>source: http://tech.lds.org/forum/viewtopic.php?t=4590
