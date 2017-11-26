# Practical Computer Networking 🏁

Recently [someone](https://hackernoon.com/2018s-software-engineering-talent-shortage-its-quality-not-just-quantity-6bdfa366b899) posted that:

> **The software engineering shortage is not a lack of individuals calling themselves “engineers”, the shortage is one of quality — a lack of well-studied, experienced engineers with a formal and deep understanding of software engineering.**

This is generalised as the **Software Engineering Body of Knowledge** or **SEBK** and currently the latest published version of SWEBOK V3 has the following 15 knowledge areas.

* [Software requirements](https://en.wikipedia.org/wiki/Software_requirements)
* [Software design](https://en.wikipedia.org/wiki/Software_design)
* [Software construction](https://en.wikipedia.org/wiki/Software_construction)
* [Software testing](https://en.wikipedia.org/wiki/Software_testing)
* [Software maintenance](https://en.wikipedia.org/wiki/Software_maintenance)
* [Software configuration management](https://en.wikipedia.org/wiki/Software_configuration_management)
* [Software engineering management](https://en.wikipedia.org/wiki/Software_engineering_management)
* [Software engineering process](https://en.wikipedia.org/wiki/Software_engineering_process)
* [Software engineering](https://en.wikipedia.org/wiki/Software_engineering) models and methods
* [Software quality](https://en.wikipedia.org/wiki/Software_quality)
* [Software engineering professional practice](https://en.wikipedia.org/wiki/Software_engineering_professional_practice)
* [Software engineering economics](https://en.wikipedia.org/wiki/Software_engineering_economics)
* Computing foundations
* Mathematical foundations
* Engineering foundations

Each of those areas is a tip of a huge Iceberg, as each one of them are comprised of are big areas of development effort, best practices, tools, techniques, experience; Coincidentally those areas are only touched in a traditional 4-year formal computer science education, giving only foundation skills. **The most important stuff is learned on the act of problem-solving and that is a skill that is learned by experience and mentorship.**

There are numerous challenges in today's market. The most often are:

1. **Lack of experience**: Professionals need to have demonstrated experience with real-world examples. Experience in the form of diverse of Skills is measured in Gold in this Business and the more you’ve got the more valuable it becomes.
2. **Lack of hard job skills/technical skills: **Professionals need experience with tools, processes, Programming languages, Frameworks, design and problem solving skills.
3. **Salary demands too high: **Developing highly critical software that can scale to handle millions of users is not a simple task. Thus the more responsibilities are involved the more competitive packages the recruiters need to offer in order to persuade people to switch jobs.
4. **Lack of soft skills/workplace competencies: **Being a computer programmer does not mean working alone. You need to have a collaborating spirit and communicate effectively, glue with the team and be pleasant to hierarchy. Some people find it very difficult to abide by that.
5. **Lack of formal engineering education: **That includes classic Computer Science topics that are mainly covered by the 
   **SEBK.**

**Traditional Bootcamps mainly focus on Technical skills.** How to answer well in technical interviews, how to build web applications, how to solve nontrivial problems that require some sort of algorithm design and in many ways they teach you how to code in order to start your career as a Junior Dev. That’s OK, but it touches only one out of the five challenges.

Someone in pursuit of higher goals might need to expand his or her horizon of options. If you notice, most of those challenges have a correlation factor related to **experience in forms of achievements.**

**Thus the more achievements one can have related to Technical skills, formal engineering education, soft skills with creating thinking, explaining complex things in a simple manner, time management, decision making, creating problem-solving and others, the more valuable and competitive he is.**

So the next question is how does someone manage to acquire those achievements?

![](https://cdn-images-1.medium.com/max/1600/1*IPn3zZyt5WD9hbDmuLbLiQ.jpeg)

Enter this series!

### What is this Series all about?

This series is a modest attempt to worn your hands with practical skills both soft and hard. It's an attempt to provide some formal engineering foundation knowledge. Computer networks together with some other topics such as Computer Architectures, Operating Systems, Database Systems, Algorithms, and Data Structures, Distributed Systems, Data Science and Software Engineering form a big part of the **SEBK.**

Understanding each one of them is a big task, but its important to invest your time and effort as they are what differentiates the good from the best.

If you follow along you will gain tons of experience, you will create your own networking stack, you will sniff, create or manipulate packets and you will build network topologies.  This is the only proven way to understand how that thing really works. If you ever wondered how the TCP congestion control works, then guess what, you will have to implement your own TCP stack! And that my friend is a great Achievement.

### Why Computer Networking?🤔

* Because networking is everywhere. It's the glue that binds everything that we use to communicate. Internet, HTTP, FTP, TCP/IP, WiFi, LANs, MANs, Routers, Bridges and tons of other protocols are in-place to make computers talk to each other without breaking apart.
* Because its a skill that everyone wants to know, yet few can master it. Networking is difficult to understand in depth, but its very valuable skill for the modern Software Engineer as he or she is challenged to understand how computers communicate in the long run and how he can design Systems that scale.

Hopefully, by the end of this series, you will be able to manipulate packets like they are a second nature to you.

### What can I learn?

> Tell me and I forget. Teach me and I remember. Involve me and I learn.  
> Benjamin Franklin

I’ve divided the important stuff into sections. For each section, there will be some articles explaining a particular topic. Each article will have some theory in a narrative and explanatory way. At the end of each article, there will be challenges in various forms that are designed to test your understanding of the theory. **The challenges themselves will not be trivial. So it's important to tackle them with a clear mind.**

The main topics covered are:

* **Network Topologies**
* **Network Types**
* **Network Communication Protocols**
* **Network Security and Encryption**
* **Network Management**
* **Cloud Networking**

There will be links to further study and resources after each part. Those will be hand-picked in order to provide quality extra study material.

### How can I study?🎓

![](https://cdn-images-1.medium.com/max/1600/1*H2S-4j9aUpeZY8KDLe16sQ.jpeg)

The recommended approach to work on the quizzes and the Lab Exercises is to grab a friend or two \(who is interested\) and run the exercises together. You can do it solo but remember you need to practice your soft skills too, how to prioritize, how to communicate, how to explain complex things in a simple way and most importantly how to collaborate on a complex problem. Those skills can become invaluable in your next career hunt.

**Note there will be NO SOLUTIONS to the assignments. Everything is open-ended, so you are encouraged to search and find answers on your own or with a party.**

That way you can really value your time and work on the assignments. In the end, you will have a greater sense of achievement if you practice without knowing the answers before-hand.

### What tools do I need?🔨

During the series, the following tools are needed in order to fully understand the concepts:

* [**Wireshark**](https://www.wireshark.org/): For packet capture, analysis and monitoring. 
* [**TCPDump**](https://linux.die.net/man/8/tcpdump): For packet capture, analysis and monitoring. 
* [**Mininet**](http://mininet.org/): For setting up complex Networks.
* [**Docker-Machine**](https://docs.docker.com/machine/) + [**Docker-Compose**](https://docs.docker.com/compose/): For setting up quickly hosts with a different configuration, and practicing on your lab assignments. 
* **Ping, Netcat, Tracert, IfConfig, Digm, Curl **and other Protocol tools.
* **Go and a little bit of C or Python: **For coding the networking stacks.

I suggest you go, download the tools and familiarize yourself with them as you will be using them a lot.

### Conclusion

Computer networking is not only for Network Engineers, It's for every professional working in the field of Computers. The world does not need more coders. It needs more problem solvers, more security aware and information technology professionals. Follow this series and you learn everything you need to know to be like that. \(I hope I've managed to convince you by now.🙏\)

### LICENSE

Licensed [BY-NC-SA Creative Commons](http://creativecommons.org/licenses/by-nc-sa/4.0/).

