# Reliability

- Simply speaking, anything that you can rely upon is called Reliable
- In this case:

  - You can rely upon your system that no one can make any unauthorized access
  - You can rely upon your system that it shall handle user errors
  - You can reply upon your system that it performs efficiently for the given data volume and internet connectivity
    If all the above points are true, then you have a reliable system for yourself.

- A "resilient" system is the one that can handle faults, or is fault tolerant

- One good way to build a fault tolerant system, is to deliberately cut off services/ shut down services and see how the system reacts to it, Netflix's "Chaos Monkey" is one such example for a fault tolerant system.

## Hardware Reliability 

- Having Hard disks being setup in a RAID configuration, where RAID stands for Random Array of Independent disks
- RAID 5 has 3 drives, in which one drive is called parity drive, which in case of any failure starts building up the lost data. 
- Single server systems have planned downtime, the messages that you receive that "We shall remain unavailable during these hours, inconvenience is regretted" is because the underlying system is single server and in order to upgrade it, they have to stop the traffic. 


## Software Reliability 

- Identify the guarantee points that a system can provide, and write scripts so that the system checks itself, and notifies you whenever there is a case of discrepancy. 
- > Humans are unreliable, Systems can be made reliable. Hence trust Systems not Humans. 
- Use strictly typed languages like TS, which minimizes the scope of errors 
- Have through testing all over the system, pre-commit and post-commit hooks which would make sure that unreliable/untested code hasn't entered the code base
- Provide a sandbox environment for the development to take place, the sandbox environment should be using the real data, but shouldn't affect the original data
- Have a huge testing process in the pipeline, that would then prevent any non-optimal code from reaching the production
- Have systems in place that can help in rollback under your command, if in case there's a chance of failure 
- Include telemetry, system that continuously monitors the performance, and can forecast a failure so that you can be ready to rollback your system. Infact, I'd say your system should automatically rollback if the telemetry indicates a severe problem in performance.

## Importance of Reliability 

- Whenever a User signs up on your application, they expect that their data would be safe with you, designing a reliable/fault-tolerant system is the least amount of thing you can do to uphold their trust and withold your integrity 

