Awesome Devops
==============

A curated list of resources for DevOps

What is DevOps?
---------------

DevOps (a clipped compound of "development" and "operations") is a culture, movement or practice that emphasizes the collaboration and communication of both software developers and other information-technology (IT) professionals while automating the process of software delivery and infrastructure changes. [Wikipedia](https://en.wikipedia.org/wiki/DevOps)

Index
-----

-	[Culture](#culture)
-	[Process](#process)
-	[Technology](#technology)
-	[Security](#security)
-	[Tools](#tools)
-	[Misc](#misc)

Culture
-------

-	[DevOps Culture](http://martinfowler.com/bliki/DevOpsCulture.html)
-	[Conway's Law](https://en.wikipedia.org/wiki/Conway%27s_law) - States that organisations will tend to produce systems that mirror their communication structures
-	[How to Hire](https://medium.com/swlh/how-to-hire-34f4ded5f176#.ilxplhbdh) - Some useful tips on hiring
-	[What security experts need to know about DevOps and continuous delivery](https://labs.signalsciences.com/what-security-experts-need-to-know-about-devops-and-continuous-delivery-f9e0d53dd09f#.7y0lxtsr9) - Info and benefits for Security and DevOps teams working together
-	DevOps and the Myth of Efficiency [Part 1](http://blog.christianposta.com/devops/devops-and-the-myth-of-efficiency-part-i/) & [Part 2](http://blog.christianposta.com/devops/devops-and-the-myth-of-efficiency-part-ii/) - Complex vs Complicated and Efficiency - DevOps for Enterprise
-   [Who drives culture in DevOps?](https://opensource.com/article/17/12/who-drives-culture-devops)

Process
-------

-	[The War of Independence for Enterprise Architecture](https://medium.com/compliance-at-velocity/the-war-of-independence-for-enterprise-architecture-1ed8eb34af3f#.kts5s5a12) - the role of Enterprise Architects in DevOps: 4 ‘R’s - Review, Renewal, Refactoring, Resilience
-	[Choosing Design over Architecture](https://18f.gsa.gov/2015/11/17/choose-design-over-architecture/) - Starting from user stories and user experience
-	[How to write a Postmortem](https://blog.serverdensity.com/how-to-write-a-postmortem/)

### Project Management

-	[Organizing GitHub issues](https://robinpowered.com/blog/best-practice-system-for-organizing-and-tagging-github-issues/) - One (of many) approaches to managing and tagging Github issues
-	[Release Ready Teams](https://www.atlassian.com/agile/release-ready-teams) - An infographic showing the how Atlassian's agile teams release early and often
-	[Using Kanban over Scrum](https://medium.com/cto-school/ditching-scrum-for-kanban-the-best-decision-we-ve-made-as-a-team-cd1167014a6f#.p8a1zicwm) - A useful post on the benefits of Kanban over Scrum (but not always relevant for every team)

### Mapping

-	[Wardley Mapping](http://blog.gardeviance.org/2015/02/an-introduction-to-wardley-value-chain.html) - An introduction to Value Chain Mapping to help understand the "Why" for organisations and Devops Teams.

### Automation

### Quality

### Open Source

-	[Making Your Open Source Project Newcomer-friendly](http://manishearth.github.io/blog/2016/01/03/making-your-open-source-project-newcomer-friendly/)

Technology
----------

-	[Basic Infrastructure Patterns](http://www.scriptcrafty.com/basic-infrastructure-patterns/) - Basic patterns seen while working on build/CI/deployment technology
-	[Infrastructure as Code](http://martinfowler.com/bliki/InfrastructureAsCode.html) - the approach to defining infrastructure through code that can then be treated just like any software

### Containers

-	[The Curious Case of Linux Containers](https://medium.com/@sumbry/the-curious-case-of-linux-containers-328e2adc12a2#.j1hbq72im) - A Blog Post discussing real issues of deploying containers across distributed systems.
-	[The Oncoming Train of Enterprise Container Deployments](http://www.juliandunn.net/2015/12/04/the-oncoming-train-of-enterprise-container-deployments/) - Blog summary of containers and a few antipatterns.
-	[DevOps, Containers & Microservices: Separating the hype from the reality](http://www.slideshare.net/dberkholz/devops-containers-microservices-separating-the-hype-from-the-reality) - A presentation outlining a future of how to build and deploy applications to generate business value.
-	[Tectonic Summit Videos](https://www.youtube.com/playlist?list=PLlh6TqkU8kg_Eydfk1Nyt6iK7wM8v9bRA) - A YouTube playlist of Container and DevOps presentationss from the Tectonic Summit in December 2015
- [A Practical Introduction to Docker Container Terminology](http://developerblog.redhat.com/2016/01/13/a-practical-introduction-to-docker-container-terminology/) - When discussing an architecture for containerization, it’s important to have a solid grasp on the related vocabulary.

### Operating Systems

-	[The Art of Command Line](https://github.com/jlevy/the-art-of-command-line) - A guide on the Command Line for beginners and the experienced

### Cloud

-	[Infrastructure as Database](http://www.scriptcrafty.com/infrastructure-as-a-database/) - Is infrastructure more like a DB than code?

### Microservices

### Security

-	[You Wouldn't Base64 a Password - Cryptography Decoded](https://paragonie.com/blog/2015/08/you-wouldnt-base64-a-password-cryptography-decoded) - A primer on Cryptography for Developers
-	[How to Protect Your Infrastructure Against the Basic Attacker](http://blog.mailgun.com/security-guide-basic-infrastructure-security/) - A good outline of important security configurations in Linux based systems

Tools
-----

### Containers

-	[Docker](https://www.docker.com/) - The tool that kickstarted the modern container movement
-	[rkt](https://coreos.com/rkt/docs/latest/) - An alternative container runtime and spec by the team at CoreOS

### Operating Systems

-	[CoreOS](https://coreos.com) - A small linux operating system that runs containers
-	[RancherOS](https://rancher.com) - Another small container OS where the entire OS is containerized.
-	[Project Atomic](http://www.projectatomic.io/) - RedHat's container OS and tools
-	[Snappy Ubuntu Core](https://developer.ubuntu.com/en/snappy/) - Canonical's container OS

### Cluster Managers

-	[Kubernetes](https://kubernetes.io)
-	[Nomad](https://www.nomadproject.io/)
-	[Mesos](https://mesos.apache.org/)
-	[Mesosphere](https://mesosphere.com/)
-	[Swarm](https://docs.docker.com/swarm/)

### Source Control

-	[Git](https://git-scm.com/) - The most popular distributed version control system.
-	[Mercurial](https://www.mercurial-scm.org/)
-	[Github](https://github.com/) - Git repo hosting as a Service
-	[Gitlab](https://about.gitlab.com/) - Self-hosted Git repos

### Configuration Management

-	[Ansible](http://www.ansible.com/)
-	[Chef](https://www.chef.io/)
-	[Puppet](https://puppetlabs.com/)
-	[SaltStack](https://saltstack.com/)

### Continuous Integration & Deployment

-	[Jenkins](https://jenkins-ci.org/)
-	[Buildkite](https://buildkite.com/)
-	[Drone](https://github.com/drone)
-	[Shippable](https://app.shippable.com/)
-	[Travis](https://travis-ci.org/)
-	[Gitlab CI](https://about.gitlab.com/)

### Incident Management

- [PagerTree](https://pagertree.com/)
- [OpsGenie](https://www.opsgenie.com/)
- [VictorOps](https://victorops.com/)
- [PagerDuty](https://www.pagerduty.com/)

Misc
----

-	[Awesome Lists](https://github.com/sindresorhus/awesome) - A list of Awesome lists (very meta!)
-	[DevOps Weekly](http://www.devopsweekly.com/) - A weekly mailing list with interesting DevOps related News and Tools
-	[DevOpsLinks](http://devopslinks.com/) - A newsletter & team chat with interesting DevOps related News and Tools
-	[Sysadvent](http://sysadvent.blogspot.co.uk) - One DevOps/Sysadmin related article for each day of December, ending on the 25th article.
-	[The Phoenix Project](http://www.amazon.com/Phoenix-Project-DevOps-Helping-Business/dp/0988262509/ref=sr_1_1?ie=UTF8&qid=1451900824&sr=8-1&keywords=project+phoenix) - A Novel about IT, DevOps, and Helping Your Business Win
-   [DevOps'ish](https://devopsish.com/) - A newsletter focused on People, Process, and Tools in the DevOps, Cloud Native, and Open Source spaces.
