# Reliable, Scalable and Maintainable Applications

> Building Tech, with a massive scale having an enormous impact ( good ) is my life's mission.

## CPU Intensive Vs Data Intensive Applications

- Applications as we see today have huge amounts of data passing through them, and computing that data is rarely a problem, because, thanks to Moore's law, we have computing chips that are increasing in their power day by day. 
- Instead the bigger problem that we face today is having applications that are data intensive. Applications should be written in a way to leverage the technologies, and provide a kick-ass user experience 
- Efficient technologies like Kafka, Docker, AWS ( include all ), React, Flutter exist, Intelligent users, the ones who are well adapted to use applications built using these exist, only that the people who know how to creatively leverage these tech, to build apps, are rare. 
- As a developer/engineer you shouldn't have any favorites, instead you should know when to use what, to get the job EFFICIENTLY done. Oh yeah, you should talk/walk/eat/love/lust/crave EFFICIENCY!!!
- The way applications are built right now, is to have independent processes running which are in-control of critical tasks, for example, there's a caching server (Redis), there's a messaging bus (MQ), there's a text-search server ( Index based ElasticSearch ), there's an API Gateway ( Express). That means your entire application is kinda bunch of inter-dependent ( great if independent ) systems running all together 
- And as a Developer/Engineer, is it your duty to handle all these systems together, such that they form a **RELIABLE SYSTEM**, which means that for a given input, you can *rely* on your system to give a correct/expected output. Which is also the reason why CS education usually begins with solving I/O based problems, thinking of it from a bird's eye prespective, everything can be simplified to an I/O problem 
- Once, you believe your system is reliable, you make it available for the people to use. As more and more people start to use your system, the traffic that your system should handle naturally increases. Therefore, you must always build systems that can handle and react accordingly to increase in *scale* of traffic, which would then mean that your system is **SCALABLE** 
- Since, you're not Tony Stark, in order to make your system you'd need to have multiple people in your team, that would mean that your system must be designed in a way so that, people can easily contribute towards it, in other words, easily *maintain* it. Which would then make your system **MAINTAINABLE** 


 
