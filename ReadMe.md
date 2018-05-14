Our social lives revolve around friends and family we trust, isn't it? Is it fair to say, "Trust" is like an oxygen to our social media lives. Twitter CEO holds this view. This project came into being when the Twitter Team published an RFP to measure how trustworthy their "social media platform" is to users at any given point in time? Are there goblins that need to be extinguished and the good guys that need to be encouraged? 

This project started as a technology proposal with a few measely ideas on developing a few convenient trust measures, which we will call as trust-intel TIN model for short.

FIGURING OUT WHAT TO MEASURE

What does this system that we are going to measure look like here? 

We are aware of the never ending streaming nature of twitter platform. It is fascinating to think what prompts these humans to keep on typing their thoughts. 

Ideally, we want to establish a few high-level health indicators that give us a sense of the traffic flowing through this platform. Keep it simple Sam principle applies here. 

I propose that our system estimates and publishes two singular numbers, one idenitfying the "unhelathy red traffic" and "healthy blue traffic". Red Estimate and Blue estimate. Simple enough. 

At any given time, our analytics engine can tell you the nature of the system. When you have overwhelming blue traffic flowing through the system, the system breathes easily as more oxygen (trusty conversations) are flowing through the system. You made the connection, I realize.

COLLECT ME SOME DATA

**Data collection** can be a lonely and boring job. Well. We will write a program and let it handle that, then. Before that, we are making some observations on the nature of data we will be gathering from the twitter platform. 

1. Tweet is the smallest unit of data on twitter platform. You agree? 
2. Tweets can multiply (get retweeted, liked and responded to). This is good. This is why the platform exists isn't it? 

3. *Find me some Rabbits:* 

My observation is that some of the Tweets have a tendency to keep multiplying like rabbits. These tweets can develop a *velocity* and find their ways to more twitter users! These quick spikes called as *amplifications* are of great interest to the twitter team.  The tendency to quickly multiciply, in a sense resembles that of rabbits. Let us name them RABBITS. We need to make sure, we net some rabbits in our data gathering. Are you ready. 

OK. What percentage of twitter traffic is filled with rabbits? We simply don't know up front! 

4. *Find me some Hobbits*:

*"Hobbits really are amazing creatures, as I have said before. You can learn all that there is to know about their ways in a month, and yet after a hundred years they can still surprise you at a pinch."
—Gandalf, in The Fellowship of the Ring*

My other observation is that there are Tweets that are kind of special, but are rare species that are not very visible to a lot of people on the platform and are in some sense like the Hobbits. It does not make them less important. After all who saved 
earth? The hobbits! 

So, yes, we want a sample of them as well.

DATA COLLECTION SYSTEM

OK. Well. At any rate, we don't want to deal with an infinite number of tweets to begin with our systme analysis journey. So, our first *strategy* is to patiently wait for a small amount of time and take a snap shot of all the tweets that show up in that period of time on the twitter platform. The length of the time is entirely our decision and simply depends on what we plan to do with these tweets.

That should give us a data file. I am christening this file as *"tweet-stream-day-hour-min-timezone.txt"*.

*Repeat:* We will repeat this data gathering procedure atleast 8 different times in a hour period, dividing the 24-hour period into 8 Zones. 

Although, eventually, this procedure needs to be repeated for each region of the world, this is an excersise that can come later. Here, our goal is to create a minimum viable strategy that works and can be back tested and extended to other regions, hopefully!




