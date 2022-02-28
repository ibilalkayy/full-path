In any typical organization, the development team creates products, and the operation team manages and maintains these products. However, the DevOps concept is a collaboration between development and operation teams, which enables continuous delivery of applications and services to end-users. 

This means that when the development team is ready with the product, it goes to the maintenance and management phases immediately and is released to the end-users with minimum delay.

# What is DevOps?

You can google the definitions and wade through all that buzzword extravaganza but know that most are embarrassingly long word salads stuffed into giant run-on sentences. (See what I did here?)

So, I’ll save you the clicks and distill it down:

    DevOps is a way to deliver software with shared pain and responsibility.

That’s it.

OK, but what does that mean?

It means that traditionally, the developers (people who create software) had incentives that were vastly different from operations (people who run software.)

For example, as a developer, I want to create as many new features as fast as possible. After all, this is my job and that’s what customers demand!

However, if I’m an ops person, then I want as few new features as possible because every new feature is a change and change is risky.
As a result of this misalignment of incentives, DevOps was born.

DevOps attempts to fuse development and operations (DevOps, get it?) into one group. The idea is that one group will now share both the pain and the responsibility (and presumably, the rewards) of creating, deploying, and generating revenue from customer-facing software.

Now, purists will tell you know that there is no such thing as a “DevOps Engineer”. “DevOps is a culture, not a role,” they will tell you.
Yeah, yeah. They are technically correct (the worst kind of correct!) but as it so often happens, the term has morphed beyond its original meaning.

Now, being a DevOps Engineer is something like “Systems Engineer 2.0.”

In other words, somebody who understands the Software Development Lifecycle and brings software engineering tools and processes to solve classic operations challenges.

    DevOps ultimately means building digital pipelines that take code from a developer’s laptop all the way to revenue generating prod awesomeness!

That’s what it’s all about!

Also note that as a career choice, the whole DevOps space is highly compensated, with almost every company either “doing DevOps” or claiming to do so.

Regardless of where the companies are, the overall DevOps job opportunities are plentiful, offering fun, meaningful employment for years to come.

**NOTE:** Be wary of companies hiring for a “DevOps team” or a “DevOps department.” Strictly speaking, such things should not exist because ultimately, DevOps is all about the culture and a way of delivering sofware, not a new team or department to be staffed up.

## Enough Talk, Where Do I Start?

Master the following and you can safely and honestly call yourself a DevOps Engineer! Or a Cloud Engineer if you detest the “DevOps” title.

The map below represents mine (and probably the majority of folks working in this space) idea of what a competent DevOps Engineer should know. That said, it is only an opinion and there will certainly be dissenting voices. That is OK! We are not after perfection here, we are after a solid foundation upon which to build.

NOTE: You are meant to traverse this breadth-first, layer by layer. Start (and continue!) with the foundation first. Learn the technologies in blue first (Linux|Python|AWS), then if time permits or job market demands, go after the purple stuff (Golang|Google Cloud).

Again, go after the first layer in every pillar. Then, time permitting, go after the second layer to add depth to your expertise.

Honestly, the foundational layer above is something you can never really stop learning. Linux is complex and takes years to master. Python requires on-going practice to stay current. AWS evolves so rapidly that things you know today are but a fraction of the overall portfolio a year from now.

But once you have the Foundation layer reasonably figured out, move onto the real-world set of skills. Notice there are 6 blue columns total, one per month.

NOTE: What’s notably missing from the pipeline above is Test. That’s intentional — writing unit, integration, and acceptance tests is not easy and traditionally falls on the shoulders of developers. The “Test” phase omission is intentional, since the goal of this roadmap is rapid intake of new skills and tools. Lack of testing expertise is judged by the author to be an insignificant barrier to a proper DevOps employment.

Also, please remember, we are not after learning a whole bunch of unrelated techno-babble here. We are after a solid understanding of tools that taken together, tell a single, coherent story.

That story is **end-to-end process automation — a digital pipeline that moves bits around in an assembly line-like fashion.**

Moreover, you don’t want to learn a bunch of tools and stop. Tools change rapidly, concepts much less so. Therefore, what you want to do is use the tools as learning proxies for the higher level concepts.

OK, let’s dig in a little deeper!

## What Does a DevOps Engineer Do?

While DevOps is a term that may encompass many roles there are some common tasks across these different roles:

- Spinning up and automating infrastructure
- Writing CI/CD Pipelines
- Creating and configuring container orchestrators
- Working closely with developers to write well designed microservices architectures
- Design DevOps strategies (Roadmap of infrastructure and deployments)
- Designing observability platforms and recommendations for various teams.
- Providing platform and infrastructure recommendations and advice to development teams.
- Ensuring that all workloads and infrastructure is secure.

## Core Technical Skills

There are six technical skills that will be common to every DevOps role. Once you have mastered these fundamentals, you are ready to start applying for entry level roles or internships as you move on the learning ladder towards DevOps technical skills:

- Linux (OS fundamentals)
- Basic Programming skills
- Bash
- Git
- Networking Fundamentals
- Cloud Platform Fundamentals

### **Linux (OS Fundamentals)**

Linux is an open source operating system (OS) that is based on Unix. The vast majority of DevOps roles will make use of Linux in one form or another, and while you could focus on Windows if you want to follow a Microsoft path in your DevOps journey, Linux and all the open source resources available for it make learning operating systems and how they work easier.

### **Resources**

- [Beginners Guide to Linux](https://www.tecmint.com/free-online-linux-learning-guide-for-beginners/)
- [37 Important Linux Commands](https://www.howtogeek.com/412055/37-important-linux-commands-you-should-know/)

## Basic Programming Skills

Don’t fret, you don’t need to be Dennis Ritchie to be a DevOps engineer. In fact, you don’t even need to call yourself a programmer at all to get started on many DevOps roles.

However, you need to at least know basic programming concepts, such as loops, variables, arrays, lists, etc. These will not only be handy when you need to read or modify some code, but will also be essential when scripting and automating your workloads.

I recommend you learn the basics and start with Golang as it is easy, then do lots of challenges in a website like Edabit and work your way up to intermediate. If you get to that level, you shouldn’t have a huge issue scripting and doing most automation jobs that come your way.

Also at some point in your learning journey it is worth becoming familiar with common design patterns and algorithms. These are not necessary to get started in DevOps but they will come in handy down the line.

### **Resources**

- [Edabit](https://edabit.com/challenges/python3) - This is a programming challenges website, once you have the basics down start with very easy and work your way up.
- [Hackerrank](https://www.hackerrank.com) - Another challenges website
- [Common Algorithms]​(https://u.osu.edu/cstutorials/2016/11/21/7-algorithms-and-data-structures-every-programmer-must-know/)
- [Design Patterns](https://refactoring.guru/design-patterns/catalog)

## Bash

Bash is the most essential scripting language to automate tasks in the Unix environment (Powershell would be the Windows equivalent). Even if you prefer scripting in Golang or any other language, bash is the most widely available, and it will be very hard for you to do this job without knowing how to use it.

You don’t need to be a programming prodigy in order to achieve most tasks that you will encounter on a daily basis, but some programming knowledge definitely helps.

### **Resources**

- [Beginner Bash Guide​](https://www.tldp.org/LDP/Bash-Beginners-Guide/html/)
- [Advance Scripting Guide​](https://tldp.org/LDP/abs/html/)
- [Bash interactive tutorial​](https://www.learnshell.org/)
- [Bash Interactive Challenges​](https://cmdchallenge.com/)
- [The Bash Guide​](https://guide.bash.academy/)
- [Bash Katacoda​](https://www.katacoda.com/courses/linux)
- [Bash Cookbook](http://index-of.es/Programming/Bash/O%27Reilly%20bash%20CookBook.pdf)

## Networking Fundamentals

You don’t need to be a network engineer to start your career in DevOps but it helps a lot if you have a basic grasp of networking, such as:

- What’s an ip?
- What’s a subnet and subnet mask?
- What’s a route?
- What’s a router and a switch?
- What’s a VPC?

Learning the above and a bit more is essential for troubleshooting and later designing VPC strategies in your cloud infrastructure.

### **Resources**

[The Bits and Bytes of Computer Networking](https://www.coursera.org/learn/computer-networking)

## Git

Git is a distributed version control system for tracking your code changes that is widely used by all software engineering and operations teams. I strongly recommend you spend some time familiarising yourself with it and the concept of branches, rebase, merging, etc.

### **Resources**


## Cloud Platform Fundamentals

There are many cloud platforms for you to choose from to begin your journey. The three biggest ones are AWS, GCP and Azure.

Most people would recommend you start with AWS as it is the most widely used and most demanded in job adverts. However, it is also where the market is most saturated.

I’d personally recommend starting out  with GCP as it is intuitive and easy to use. You get 300 dollars free credit as well and their certifications have a syllabus that is cloud agnostic, which means that it will prepare you for when you learn AWS or other cloud platforms. Azure is also a good choice if you prefer a Microsoft environment to work on and that’s where you want your career to go.

### **Resources**

- [Google Cloud Free Offering​](https://cloud.google.com/free)
- [Quicklabs​](https://google.qwiklabs.com/)
- [Azure](https://azure.microsoft.com/en-us/)
- [AWS Free Tier](https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc)​
- [Google Cloud Free Courses](https://www.coursera.org/googlecloud)​
- [AWS and other Cloud Computing Agnostic Free Courses​](https://www.coursera.org/courses?query=aws)

## DevOps Technical Skills

Once you’ve gotten your core technical skills down, then you can proceed to become more familiar with the tools and practices specifically used in DevOps roles. This is by no means an exhaustive list, but they are the most common skills and topics you are most likely to encounter in most DevOps roles.

### **Containers**

Containers are a way to package and isolate your running applications. This is not only more secure, but it also makes your running environment more deterministic because a container will always run in exactly the same way, no matter what server or computer it is running on.

Containers are often used a lot in CI/CD pipelines, as well as in production workloads and microservice architectures, so understanding containers is a must. Container orchestrators are also used a lot these days which we will explore later.

### **Tools**

- **[Docker](https://docs.docker.com/get-started/)** - Most popular runtime environment for containers, learn this.
- **[Docker-compose](https://docs.docker.com/compose/)** - This tool allows you to configure and orchestrate multiple containers in your computer, especially useful if your application has multiple containers or if you need to bring up the same container over and over.
- **[Docker Deep Dive](https://www.pluralsight.com/courses/docker-deep-dive-update)** - A fantastic and thorough course from the 5-star training instructor.

### **Resources**

- [Play with Docker​](https://training.play-with-docker.com/)
- [Docker-compose mini tutorial​](https://www.tutorialspoint.com/docker/docker_compose.htm)
- [Docker cheatsheet​](https://www.docker.com/sites/default/files/d8/2019-09/docker-cheat-sheet.pdf)
- [Docker-compose cheatsheet](https://devhints.io/docker-compose)

### Continuous Integration (CI),Continuous Delivery (CD) and Continuous Deployment

A CI/CD pipeline is the production line in a company that does software engineering. A CI pipeline builds and tests the code to ensure it is ready to be integrated in your main branch, and a CD pipeline is an extension of that to ensure it can be deployed.

Understanding CI/CD well requires understanding git, git branching models, trunk based development, automation, and different testing methods. Jenkins is the most widely used and powerful CI tool and you would do well learning it.

However It’s not the most user friendly, and the language used to write pipelines (Groovy) is not exactly intuitive. Gitlab CI is much more simple to use and it may be a more approachable tool to learn pipelines first. There are many other tools you can use to take care of your CI/CD pipelines, but the most important thing is that you are familiar with the concept.

### **Tools**

- Jenkins​
- Gitlab CI​

### **Resources**

- [Branching Models​](https://medium.com/contino-engineering/branching-models-in-a-nutshell-bf24ea1d888a)
- [Git tutorial for TBD​](https://medium.com/contino-engineering/git-to-know-this-before-you-do-trunk-based-development-tbd-476bc8a7c22f)
- [Continuous Delivery Playlist by Dave - Farley​](https://youtube.com/playlist?list=PLwLLcwQlnXBxy8H8JEizOcfDh_Vyy6qyv)
- [Continuous Delivery Book​](https://www.amazon.co.uk/Continuous-Delivery-Deployment-Automation-Addison-Wesley/dp/0321601912)
- [What is continuous delivery?​](https://www.redhat.com/en/topics/devops/what-is-continuous-delivery)
- [Learning TBD​](https://cloud.google.com/architecture/devops/devops-tech-trunk-based-development)
- [Continuous Integration​](https://cloud.google.com/architecture/devops/devops-tech-continuous-integration)
- [Deployment Automation​](https://cloud.google.com/architecture/devops/devops-tech-deployment-automation)
- [Continuous Testing​](https://cloud.google.com/architecture/devops/devops-tech-test-automation)
- [Continuous Delivery​](https://cloud.google.com/architecture/devops/devops-tech-continuous-delivery)
- [Trunk Based Development (TBD)​](https://trunkbaseddevelopment.com/)
- [Test Driven Development](https://en.wikipedia.org/wiki/Test-driven_development) - While not strictly necessary, this approach is often recommended as a way to make sure that your code is always fully tested before it goes into the server.
- [Continuous Delivery, it’s great but it won’t work here](https://youtu.be/IvWr29afDF8) - Talk by Jez Humble
- [Adopting Continuous Delivery](https://youtu.be/6DeWOrmvhRM) - Talk by Jez Humble

## Infrastructure as Code (IaC)

Infrastructure as code is a practice by which you create, configure and update your infrastructure by writing code and applying it.

This is different from creating infrastructure manually or by clicking on the console because you keep a replicable record of everything that’s deployed, which allows you to better audit and recreate it.

IaC can be either one of these:

- **Declarative:** You describe the outcome and the tool makes it happen. For example if you say, “I want two servers”, multiple applications of this code will always yield two servers, no more, no less. This is also called idempotent, meaning that no matter how many times you run the code, the result is always the same. This is the preferred way of writing IaC and most tools such as ansible or terraform aim to work in this way.

- **Imperative:** Whatever you request gets created every time; if you say, “I want two servers” and you hit apply three times, you will get six servers. A bash script is, generally speaking, an imperative way to do IaC.

Additionally, when writing infrastructure as code you will be doing either one of these or two type of operations:

- **Configuration Management (CM):** This is automation code that configures running infrastructure. For example running scripts to install updates on one or multiple servers at once. Tools like Ansible, Puppet, Saltstack and Chef allow you to do this mostly in a declarative way.

- **Orchestration:** Like the name implies orchestration creates resources and their metadata, but it generally doesn’t configure what’s inside of them. For example, you can say you want five servers created, and those servers are created to your specifications with whatever image and metadata you want, but orchestration does not define what configuration goes inside those servers for the most part. Tools like Terraform and CloudFormation are used for orchestration—Terraform being the most platform agnostic and popular of them all.

While understanding CM is essential and you will use it from time to time, it is best to design your architecture in such a way that you can avoid it as much as possible. This is because no matter how well you do CM, there will always be a configuration drift after a period of time.

Instead of doing CM, cloud providers allow you to provide user metadata scripts that can run when you create a server.

In addition, you can use tools like packer to create images for your servers that contain all the upgrades and software needed. In this way, you can just destroy the server and recreate it whenever a change is pushed to the application or updates are needed.

In other words, provided that you can design your architecture you should opt for minimising the amount of CM you do, however in legacy environments where pure orchestration is not possible, then CM becomes more relevant.

### **Tools**

- Terraform (Orchestration)
- CloudFormation (Orchestration for AWS only)
- Ansible (CM) - There are other CM tools like puppet, chef, and Saltstack, but Ansible is currently the most widespread and easiest to use.
- Packer - To create server images.
- Cloud Deployment Manager (Orchestration for GCP only)

### **Resources**

- [Learn IaC with Terraform​](https://learn.hashicorp.com/tutorials/terraform/infrastructure-as-code)
- [IaC tutorial​](https://www.invensislearning.com/blog/infrastructure-as-a-code-tutorial/)
- [IaC Explained​](https://www.digitalocean.com/community/conceptual_articles/infrastructure-as-code-explained)
- [How Ansible works](https://www.ansible.com/overview/how-ansible-works)

## Microservice Architecture

Traditionally, applications were designed as a monolith, meaning that all the components were integrated tightly together within the same server.

Monoliths are simpler to get started with and  operate and you don’t need to deal with issues such as latency or connectivity nearly as much because everything is likely to reside in one place.  However this simplicity also makes them tightly coupled, less scalable and harder to upgrade without downtime.

Microservice architectures on the other hand have multiple advantages over monoliths:

- Easier to distribute responsibilities, various teams working in different components.
- Easier to independently scale
Fault isolation, if one service breaks, not everything breaks.
- Isolation of data (such as for use cases like GDPR, etc)
- Easier to upgrade independent components without causing overall downtime to the application.

Microservices are not an integral part of every DevOps role, however because using them allows one to update an architecture in a piecemeal manner and more regularly, they are much in vogue these days.

That being said, microservices are not a panacea; they allow more flexibility and scalability but they are also far more complex, meaning you will have to deal with designing an application that’s truly decoupled and also deal with latencies, connectivity, retries, etc. In essence you are trading code complexity for infrastructure complexity with the aim to improve delivery velocity, scalability and decoupling.

Because Microservices are small and meant to scale, container orchestrators are often the preferred method to run them. These will detect when an application is strained and automatically scale them for you or restart them if there is an issue.

It is important you understand at least what an application needs to be like in order to qualify for a microservice. Simply dragging a monolithic application from a server and dumping it on a container will not make it a microservice. Instead, each component needs to be split and redesigned to account for extra latency, connectivity, and also segregate data and config layers from the running application.

Also doing microservices requires a shift in how infrastructure is traditionally run. Rather than treating servers as pets, they are treated as cattle. Microservices are deployed as images and servers are scrapped and recreated when an upgrade is required.

### **Resources**

- [The Problem with Microservices​](https://youtu.be/zzMLg3Ys5vI)
- [12 Factor Application](https://12factor.net/) - Applications that are designed with the 12 factor model in mind are essential in microservice environments.
- [When to use Microservices and when not to.](https://youtu.be/GBTdnfD6s5Q)
- [Software Architecture Monday](https://youtube.com/playlist?list=PLdsOZAx8I5umhnn5LLTNJbFgwA3xbycar) - This is a great playlist of videos teaching a lot of different concepts about microservices and other architectures in general
- [Essential Microservice Testing​](https://nandovillalba.medium.com/essential-microservice-testing-a838c34a86e3)
- [Advance Distributed System Design​](https://learn.particular.net/courses/distributed-systems-design-fundamentals-online)
- [Mastering Chaos, a Netflix Guide to Microservices.](https://youtu.be/CZ3wIuvmHeM)​
- [Microservice Pattern](https://microservices.io/patterns/microservices.html)

## Container orchestrators

Container orchestrators allow you to run containers across one or multiple servers and scale your workloads horizontally. This makes them ideal platforms to run microservices.

*For example*, instead of having one or multiple containers running in one server, the orchestrator would take care of creating more replicas of servers and containers to serve more traffic on demand.

Sounds simple enough but orchestrators make certain assumptions about how your application is designed. For example, they assume that configuration is passed as environment variables and that your data is not saved within the actual container. So sometimes migrating an application to an orchestrator to make it scalable requires re-engineering it to make it a microservice. The **12 Factor app** is a method of designing applications that makes them ideal to work with orchestrators.

Whilst there are many orchestrators like Swarm, ECS and Nomad, by far the most popular container orchestrator is Kubernetes and hence I recommend you focus your efforts on that one.

When learning kubernetes, I recommend a top down approach. Start with understanding the architecture and components loosely and then play with an already existing cluster, rather than creating your own from scratch. This will make your learning process a lot less overwhelming and will also make it easier to see why all the components are needed.

If you use a Mac, a kubernetes cluster comes bundled with Docker so you could use it just like that. Otherwise you could use something like kind to generate your own.

In terms of using kubernetes in the cloud, GCP’s implementation is by far the easiest to use, but both Azure and AWS have their own.

### **Tools**

- [Docker Kubernetes​](https://www.docker.com/products/kubernetes)
- [Kind​](https://kind.sigs.k8s.io/docs/user/quick-start/)
- [GKE​](https://cloud.google.com/kubernetes-engine)
- [EKS​](https://aws.amazon.com/eks/?whats-new-cards.sort-by=item.additionalFields.postDateTime&whats-new-cards.sort-order=desc&eks-blogs.sort-by=item.additionalFields.createdDate&eks-blogs.sort-order=desc)
- [AKS​](https://azure.microsoft.com/en-gb/services/kubernetes-service/)
- [K9s​](https://github.com/derailed/k9s)
- [k0s​](https://k0sproject.io/)

### **Resources**

- [Kubernetes Tutorial for beginners​](https://youtu.be/X48VuDVv0do)
- [Kubernetes Components​](https://kubernetes.io/docs/concepts/overview/components/)
- [CKAD Practice Questions​](https://medium.com/bb-tutorials-and-thoughts/practice-enough-with-these-questions-for-the-ckad-exam-2f42d1228552)
- [CKA learning resources​](https://github.com/walidshaari/Kubernetes-Certified-Administrator)
- [Learning Kubernetes the Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way)


## Monitoring and Observability

We monitor systems to tell us when something is an issue or is about to be an issue, and we observe to ensure trends in performance and traffic that helps us make our systems better in the future.  Monitoring is about understanding known knowns and known unknowns, with monitoring you test hypotheses about the behaviour of the system. Observability on the other hand is about unknown unknowns; about discovering new issues with richer data and creating hypotheses that can be monitored.

Monitoring and observability can be boiled down to:

- **Logging:** The process of outputting system events that may or may not be errors.

- **Metrics:** These are time series that indicate the number of events in a time period. They can be based on logs or system status like ram, etc.

- **Distributed Tracing:** With distributed tracing you assign an individual ID to each request that comes into a system so you can monitor its path through it and how it affected the various microservices.

- **Service Level Indicators (SLIs):** These reflect the current state of your system. SLIs are generally based on metrics that you define.

- **Service Level Objectives (SLOs):** You define a SLO and ensure that your system runs below that metric. For example if you have an SLO that 95% of requests should be under 200ms and suddenly you start seeing too many requests taking 1 second, then you are breaching your SLOs. When this happens you will need to design for scale or fix whatever issue is causing this upticks in performance so you don’t lose customers.

- **Service Level Agreements (SLAs):** Service level agreements are contracts you have with your customers that outline what compensation will be given if they are breached. For example you could say to your customers that if your service is down for more than 95% of the year you will pay them x amount of money in credits. SLAs should be set far higher than SLOs, this way you can tackle the issue before your levels get critical.

### **Resources**

- [SLIs vs SLOs vs SLAs​](https://www.atlassian.com/incident-management/kpis/sla-vs-slo-vs-sli)
- [Monitoring and observability​](https://cloud.google.com/architecture/devops/devops-measurement-monitoring-and-observability)
- [Monitoring​](https://sre.google/workbook/monitoring/)
- [Practical Alerting​](https://sre.google/sre-book/practical-alerting/)
- [Service Level Objectives​](https://sre.google/sre-book/service-level-objectives/)
- [Implementing SLOs​](https://sre.google/workbook/implementing-slos/)
- [Alerting on SLOs​](https://sre.google/workbook/alerting-on-slos/)
- [Logging Best Practices​](https://www.scalyr.com/blog/the-10-commandments-of-logging/)
- [Microservice Observability​](https://dzone.com/articles/microservice-observability-part-1-disambiguating-o)
- [Distributed Tracing](https://microservices.io/patterns/observability/distributed-tracing.html)

## Software Reliability Engineering (SRE)

SRE is a subset of DevOps where you apply software engineering principles to implement and improve the operations of your distributed systems.

The term was popularised by Google and they have multiple books on the topic as well as Coursera courses available for free. It is worth studying them even if your title is not formally that of an SRE as there is a wealth of knowledge that you will certainly be able to apply to any DevOps role. I especially like and recommend their chapters on SLIs and SLOs.

### **Resources**

- [SRE Books​](https://sre.google/books/)
- [SRE Coursera](https://www.coursera.org/learn/site-reliability-engineering-slos)

## Security

I purposely didn’t mention security until the end because I want you to think of it as essential as air and keep it in mind for absolutely everything that you do. Always design with security in mind and not as an afterthought.

You don’t have to be a certified hacker to design secure systems, but it certainly does help a lot to know about security and understand the type of attack involved in a system you are designing.

## **Resources**

- [Try Hack me](https://tryhackme.com/)​
- [Hack the Box​](https://www.hackthebox.eu/)
- [Vulnhub​](https://www.vulnhub.com/)
- [Practical Ethical Hacking Course​](https://academy.tcm-sec.com/p/practical-ethical-hacking-the-complete-course)
- [Building Secure and Reliable Systems](https://static.googleusercontent.com/media/sre.google/en//static/pdf/building_secure_and_reliable_systems.pdf)

## Agile

Agile is a set of principles for engineers that enables them to do continuous and short release cycles in a more efficient, faster and nimble way by embracing changing requirements on the fly and improving dialogue with the customer and the business. Agile generally speaking is an integral part of DevOps.

The principles of Agile were codified in a manifesto and later implemented in various forms such as scrum, XP, kanban, etc. Scrum is possibly the most popular implementation of Agile, followed by Kanban, but just because they are popular doesn’t mean that they would be the best for your team, which is why it is good to become familiar with the various implementations to see which one suits best.

## **Resources**

- [The Agile Manifesto​](https://agilemanifesto.org/principles.html)
- [What is Agile?​](https://www.tutorialspoint.com/sdlc/sdlc_agile_model.htm)
- [Extreme Programming (XP)​](https://ronjeffries.com/xprog/what-is-extreme-programming/)
- [Kanban​](https://www.atlassian.com/agile/kanban)
- [Scrum​](https://www.scrum.org/resources/what-is-scrum)
- [Kanban vs Scrum​](https://www.atlassian.com/agile/kanban/kanban-vs-scrum)
- [Clean Agile, back to basics](https://youtu.be/4JihsBOBbdI) - A talk by Bob C Martin, one of the founders of the agile manifesto
- [Explaining Agile](https://youtu.be/GE6lbPLEAzc) - A talk by Martin Fowler, another founder of the Agile Manifesto.