# PFC200_Docker_Scalability

When discussing software solutions in industrial automation, or in general for that matter, there’s always been an ever-looming presence that rears its ugly head on occasion. Much like how I’ve dealt with the monster under my bed as a child, I’ve greeted this aforementioned being in the same way…running out the room with my arms flailing while I make horrifically loud noises until it goes away.

Sadly, in a professional setting, this trump card of mine has not served me as well as it had in the past, so I’m forced to face this terrifying visage head on. The terror in question, of course, being scalable software deployment.

Picture this. You have heard my elevator pitch regarding Wago PLCs and our leveraging of open-source software. I’ve explained in great detail how Docker is free from the shackles of versioning and hardware dependencies while having an extensive library of software to choose from. You, naturally, are so enamored by my explanation that you immediately begin investigating these solutions and attempt to use them in your application.

And so, it begins. You connect your Wago PFC200 to the internet, install the docker ipk, pull your docker images, create your volumes, run your containers, and finally host a program on those containers. Now with your Midas-like touch, you have deployed your application and I get to walk back into my bog house like Yoda in Empire Strikes Back…until you stop me in my tracks and ask THE QUESTION (dun dun duuuuun).

The question goes something like this: “Joe, I like how the application works and everything about it, but I don’t want to go through all of these steps with each new controller. How can I deploy my application in a faster and easier way?”

Well after I’ve let out my shrieks of terror and risen from the fetal position, I figured this series would attempt to solve that very same issue. Each new addition will, hopefully, increase the scalability and ease.
