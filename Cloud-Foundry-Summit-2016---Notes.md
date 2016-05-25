---
title: Cloud Foundry Summit 2016 - Notes
layout: post
author: rbuehl
permalink: /cloud-foundry-summit-2016---notes/
source-id: 14tXxgtWLKYH37ie47civTOCWpwMcIjNrqAYrYqJEjmU
published: true
---
# Cloud Foundry Summit 2016 - Notes 

## Day 1:

### Keynotes

#### Sam Ramji

* non zero book

* Self = project 

* Platform = positive sum game 

* Best sales person sold first phone ever, example for network effects

* Platform revolution book: the more the greeted the network effects 

* Certification 2016

    * Time stamped for referencing hardware cf versions (2016, 2017, …)

    * ATOS CF released

* Every company uses 4.6 clouds 

* Packages services

    * Service brokers

* Packages Apps

    * Effective marketplace and simple packaging format for mobile

    * Create same for cf apps

* 2100+ contributors, 2300+ patches, 130+ core committers, 25 releases (on pair with openstack or Linux

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_0.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_1.jpg)![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_2.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_3.jpg)

#### Martin Ford (the rise of robots)

* Productivity vs compensation is in line until 1973 due to transition in technology

    * Before tools to become productive

    * Replacing workers as tools become autonomous 

* Long term: guaranteed income with incentives, especially for education 

* Machines to not consume, so what's the economic impact in the long run?

#### Angel Diaz (VP of cloud architecture & technology)

* Dojo for speed up open source committer status

* Cloud foundry is platform of innovation

* Customers have choice with consistency 

* Abacus project?

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_4.jpg)

#### Sam Gambarin (Director of cloud services)

* no longer selling insurances to brokers but to customers 

* A lot of SoR around; utilize them!

* Bluemix as there is Watson capabilities available

* Requirements took time as they needed to be standardized, but implemented in three weeks. 

* Bluemix in 2016 only for workforce not for customers

#### Greg Otto (Executive Director Cloud Services, Comcast)

* 16million Xbox customers

* Late 2015 go live with business critical application with cloud foundry

* Pivotal supported

* 2 days workshop 

    * Day 1: build platform 

    * Day 2: deploy existing applications done by core developers

* Work closely with the dev teams to learn together 

* Most time spent on people

    * Channel passion to realize great things

    * Better together story

* 2-3 days for new features instead of weeks

* Product scaling in minutes instead of months 

* Nick for heavy lifting stories 

#### Justin Smith (director pivotal, security)

* Cloud native Security: rotate, repave, repair

* Security is like painting the golden gate bridge every day

    * They protect a national treasure

    * Act of love

    * The bridge is always changing 

* Make cf the secure runtime 

    * Cyber attacks is number one threat in {document}

    * Shape of threat: lpt, worm, malware 

    * Breach reports 

* Top drivers of breaches 

    * Vulnerable software / not patched

    * Time

    * Leaked credentials 

* Amount of firewall rules in big companies 

* How often do you change TLS keys

* Pay to get someone to monitor security

* deal with all the modifications?

* Software and culture resist change (grumpy people / security that do not want to change)

* It's about perspective:

    * repair the whole stack > vulnerable software

    * Pivotal & the fast patch: 30 releases in 2016

    * Repave: destroy & rebuild often

        * What's the minimum amount of liven time?

        * How about reboot each machine every two hours?

        * Cron job to "bosh recreate"

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_5.jpg)

#### Phil Glebow (director pricing architecture)

* localised promotional pricing

* Initial results required objective 90 c4.4xlarge for gurobi instant cloud product to solve 6000 instances of the problem

* Timing constraints are critical 

* Why cloud: elastic pricing for customers (time/cost)

* Changes to the algorithm can now be published quickly - with unit tests and automate cf pushes

* Spring boot shop now 

* Spring actuator for some of the endpoints

* Spring cloud config 

* Mongo (existing on VMs)

* RabbitMQ (exiting on VMs) - both as PCF on premise did not yet have then required services 

* Organisational issues

    * Java is not the preferred language for data science / optimisation

    * Agile vs waterfall context is a challenge for data scientists (they have a favor for over verification / planning 

### Lightning talks

#### Renat Khasanshyn (CEO altoros)

* Overview of Platforms (blue mix, predix, app exchange, ...)

* Disruptive force = tech + millions of developers 

* Digitalizing revenue streams

* Cf-training.altoros.com

#### Ed Anuff (svp, product strategy, apigee)

* we need to get into the clouds not into the cloud

* Cloud Foundry Route Services

    * Hook into the route

    * Rate limiting

    * do software right by integrating your api infrastructure ensures that teams to api writes -> consistent

#### Roman Swoszowski (VP of Cloud Foundry at GrapeUp): Cloud foundry resisted : ADP, VoIP and beyond

* Web Applications: 12-factor

* non-http-applications 

* extensible LB-interface to support 

* Logging and metrics: [http://santaclara2015.cfsummit.com/sites/cfs2015/files/pages/files/cfsummit15_king.pdf](http://santaclara2015.cfsummit.com/sites/cfs2015/files/pages/files/cfsummit15_king.pdf)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_6.jpg)![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_7.jpg)![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_8.jpg)

## Day 2

#### Doug Safford (VP AllState Technology Innovation,[ https://www.linkedin.com/in/doug-safford-4369144/de](https://www.linkedin.com/in/doug-safford-4369144/de))

* 70% of business is auto insurance

* metaphor: car manually build -> assembly line (for situation of insurance industry right now)

* CompoZed Labs (Accelerated Delivery), internal brand Mat Curry (starting with a small band of believers)

* Start with technology to prove the business…

* Starting with product that has no dependencies 

* Jan '15 with no integration to 17 product by Nov’15

* Sent best engineers 20-30 to pivotal labs

* methodical and strategic plan from tipping around edges to change core systems

* 4 Month training programs: building products after 2 months

* same look and feel of team working areas (compozed labs)

* 30% of VI is now PCF

* Push complete cloud foundry instance from one DC to another in 3h, fully automated. 

    * validation of all application

    * 4 engineers to manage power impacts

    * zero impact on customers 

    * build a lot of tools to manage infrastructure 

* Resistance is strong

    * HR, procurement, real estate all have a lot of role (85 years of tradition)

    * CEO banned scooters (no scooters allowed) 

    * director / manager compensated for giving and taking orders

    * 6-8 person teams make the decision now

* Metrics are scarce

    * benefits

    * waterfall -> don't look for metrics

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_9.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_10.jpg)![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_11.jpg)![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_12.jpg)![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_13.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_14.png)

#### Bill Hilf (SVP & GM, HP Cloud)

* Customer experience / review

* Jason Armstrong (Travelport, travel commerce platform) 

* New Dojo in Seattle 

#### Simon Johansson (Platform Engineer), Daniel Otte (Head of Platform Engineering,[ https://nl.linkedin.com/in/danielotte/de](https://nl.linkedin.com/in/danielotte/de), Springer Nature) - From Weeks to Minutes: 

* Bringing in springerlink which was hosted by a third party

* Ops-side was drowning as transformation was not yet in-place

* Interactive story about ordering vms, DNS, NFS, FCC, pubilc endpoints, configuration management, …

* Go-live: speed up because it's freaking slow. 

* single isolated solutions: puppet, chef - ansible overriding both

* New Team: "Platform Engineering" -> speed-up development processes 

* Brought development back insight. 

* Faster horses: don't wait for weeks for vms

* spring app file anatomy, clone a repo in any language of choice 

    * must expose an endpoint

    * generating dashboards

    * creating build pipelines 

    * monitoring for free 

* Small footprint

    * few boxes in 2 data centers

* CF from scratch using the community software, supported by own people and community 

* Idea-2-production

    * code

    * cf push

    * bind app to domain to get it onto the internet

#### Marc-Thomas Schmidt (Chief Platform Architect,[ https://www.linkedin.com/in/marc-thomas-schmidt-35488710/de](https://www.linkedin.com/in/marc-thomas-schmidt-35488710/de), GE Digital)

* Predict is an IoT platform 

* Systems of Assets (SoA), SoE, SoR

#### Michael Villiger - Technolgy Evangelist, Dynatrace,[ https://www.linkedin.com/in/mvilliger:](https://www.linkedin.com/in/mvilliger:) performace driven ci/cd in a nutshell

* software is eating the world…

* APIs and monitoring into them

#### Shannon Coen (Product Manager, Pivotal Software, Inc.) & Carlos Eberhardt, Apigee: Recent enhancement with route services

* App auto sleep

* ssl certificate provisioning

* weighted routing

* CE: caching demo

* tcp routing: http vs. tcp routing based on different domains

#### Jeff Barrows (Cloud Platform Service Architect, GE Research,[ https://www.linkedin.com/in/jbarrows](https://www.linkedin.com/in/jbarrows)): Monitoring Cloud Foundry Graphite 

* Bosh release of sensu client

* Every node belongs to al group 

* Now capturing all base Linux stats for all nodes 

* Infos to decide if we need to scale out the platform 

* Naming convention very important

* stuff to be put on github as soon as clearance by legal is available 

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_15.jpg)![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_16.jpg)![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_17.jpg)

#### Running Cloud Foundry in a Compliance and Security Focused Environment - Diego Lapiduz and Bret A. Mogilefsky, 18F (Internal Agile Org in Fed, [https://18f.gsa.gov/](https://18f.gsa.gov/))

* Documentation is gov is of WHOLE stack (200-1000pp), requires 4006 knowledge of regulations (FIPS, etc.)

* 6-14 month Authority to Operator (ATO)

* Speed = security 

* no secure systems but only systems that haven't been broken yet

* Automation, automation, automation with concourse and bosh

* Source code on github: track change to the repos

* Hashes satisfy the controllers: "here's hashes for changes builds etc.."

* Forwarding Logs to CloudWatch (hopefully with alerting soon)

* Making nessus part of the bosh release

* User access: 

    * Standard uaa with upstream saml provider with MFA

    * Delegate user management

* Ephemeral jump boxes: Hijack concourse container as ephemeral jump boxes

* Compliance Masonry

    * Write docs as YAML data in github

    * Composable layers, configurable mapping

    * Automate publishing with concourse

* Use User provided services for SECRETS

* Blessed buildpacks: Have documentation and will get "quicker" security assessment

* Custom buildpacks: bring your own, no docs, will require longer lasting assessments

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_18.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_19.jpg)![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_20.jpg)![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_21.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_22.jpg)

#### [Building a Brand Around a Technology and Cultural Transformation - Matthew Curry, Transformation Leaser @ Allstate](https://cfsummit2016.sched.org/event/6aKz/building-a-brand-around-a-technology-and-cultural-transformation-matthew-curry-allstate?iframe=yes&w=i:0;&sidebar=yes&bg=no#?iframe=yes&w=i:100;&sidebar=yes&bg=no) ([https://www.linkedin.com/in/mattjcurry/de](https://www.linkedin.com/in/mattjcurry/de)) 

* History - The desire for control 

* Insurance industry is not the only industry that has problems with designs

* Netfix culture deck

* Small business are like speedboats: life is good

* A large vessel is needed as company matures: Early rules are tightly aligned to core values, but layers of rules make it difficult to navigate - work! 

* "This boat can go pretty fast until we need to change direction

* Why do I have to go to that meeting of no one has the power to make decisions 

* More venture capital is going into insurance industry than ever 

* The answer: decentralize - create empowered and collaborative teams > spread the crews on many speedboats 

* What was needed a "marketing name" for the thing -> CompoZed Labs

* Engineers love t-shirts -> drive a more casual atmosphere 

* Compozed comprises

    * Labs: where we work, casual dress, fun, collaboration, learning, riping down cubicle farms

    * Methodology: paring always, TDD, CD, automate everything, devops, tightening feedback loops…

        * "My service is too critical for you to mess around without it"

    *  Platform: 

        * CF is the center of the platform 

* Communicate, communicate, communicate: 

    * Website has not create metrics

    * Offline Face-2-face can't be replaced

    * Meetups with externals and inviting internals works out well

    * Start coordinating events

* Compozed Manifesto -> values != what are our rules (bad idea)

    * Respect your pair

    * Respect your team 

    * Always try to get better

    * User first

    * Learn always

* Having leaders wear a hoodie and t-shirt -> organization change

* "Changes in behaviour change culture not powerpoint slide"

* Quality of t-shirts is important: iterate, feedback, iterate

* Training course will have trained around 250 by end of the year

* Changing the recruiting processes  

* Boss put a meeting on calendar, subject "don't go to meetings"

* Transformation in all divisions (hr, real estate, …) 

    * Tech platforms

    * Application design 

    * Customer focus

    * Operational models 

* Lessons learned

    * Iterate quickly

    * Communicate always...storytelling is critical 

    * Constantly be inclusive

    * Understand incentives (e.g., for public talks - changing performance management -> does the person embody the values?)

    * Live the culture at all levels (nothing will kill your culture like hypocrisy)

* Why a training center and not learning on the job? 

    * People didn't pair ever

    * Get people back on coding (some haven't coded in a while)

* Trained people are in "awesome mode", old environment is “sad mode”. Awesome people should sad mode people to get in “mildly sad mode”

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_23.jpg)![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_24.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_25.jpg)![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_26.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_27.jpg)

Swagger and cf: Dr Max, 

* not just a pretty UI 

* Swagger is basis for open api foundation 

* Iterate and repeat

* swaggerhub

* Description of cf api eg for service broker 

* Demo: Create a broker from its description with swaggerhub

* Test compatibility kit for cf-swagger 

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_28.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_29.jpg)

Containers 

* Docker containers will not be patches with cf

* Cf-docker-bridge

* Using docker commands to push

* Use cf to scale, log, ssh, …

* RunC will become container runtime 

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_30.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_31.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_32.jpg)

#### Container Networking:

* Packet tracing back to the application to improve multi tenancy capabilities 

* container network interface (CNI)

* Extension of the cloud controller

* Current routing 

    * Cf components constantly advertise routes 

    * Routers use this advertisement to route traffic 

* Policies

    * Explicit vs implicit definition

    * Open discussion on which layers policies should apply

* Policy enforcement

    * Vxlan (VNI = tenant)

    * Sending Container puts bit for source 

    * Receiving container may check these bits

    * ![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_33.jpg)![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_34.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_35.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_36.jpg)![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_37.jpg)

Bosh 2.0 - provision resources on demand 

* managing and deploying stateful services is hard 

* Dynamic ip allocation 

* Global cloud config 

* ![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_38.jpg)

* ![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_39.jpg)

### Keynotes

Ken Owens, CTO of Cloud Infrastructures, Cisco

* Cloud Native Transformation

    * Great if it works

    * Very difficult to troubleshoot

* Lessons learned

    * ![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_40.jpg)

    * Shipped software development lifecycle tool 

* Mesos

    * Containerized cf deployment 

    * Mantl.io

Fireside chat: Barton George (Sr Technologist, office of the CTO, Dell) & Cody Taylor (Director Software Engineering, Dell):

* Deployment process, end to end delivery cycle

* Structural changes, collocation,...

* Environment parity 

* Blue green deployment 

* Formal dojo lasted 

* Deployed three different deployments 

* Working with pivotal on community edition 

* Opinionated platform vs opinionated apps

* ![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_41.jpg)

Security x CF

* Guido Westenberg, head of platform engineering team

    * look how integration looks like user provided service, service broker, bosh release (tile)

    * Take partnering request and work with ISV

    * Try to deliver an MVP

    * What are the partners we should be working two

* Mike Gardiner, Gardiner 

    * Hardware security models 

* Secrets

    * Vault, key whiz, HSM...but how to ignite 

    * User provided services 

    * Cf set-env

## Day 3

### Keynotes 

#### [Delivering Simpler, Clearer, Faster Government Services with Cloud Foundry - Lindsay Holmwood, Head of Development, Australian Government Digital Transformation Office - Lindsay Holmwood](https://cfsummit2016.sched.org/event/6ZjN/keynote-delivering-simpler-clearer-faster-government-services-with-cloud-foundry-lindsay-holmwood-head-of-development-australian-government-digital-transformation-office?iframe=yes&w=i:0;&sidebar=yes&bg=no)

* GHE

* Jenkins / CI 

* CF 

* Graylog

* [https://github.com/AusDTO](https://github.com/AusDTO)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_42.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_43.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_44.jpg)

#### [Enterprise DevOps: Balancing Innovation Velocity with Business Requirements - Brian Gallagher, President, Cloud Platform Team, EMC - Brian Gallagher](https://cfsummit2016.sched.org/event/6ZjO/keynote-enterprise-devops-balancing-innovation-velocity-with-business-requirements-brian-gallagher-president-cloud-management-division-emc?iframe=yes&w=i:0;&sidebar=yes&bg=no)

* DevOps 

    * accelerating enterprise innovation 

    * Build Measure Learn

    * Different value systems in dev and ops

    * Dev: cf push

    * Op: bosh deploy

* Clear path report

* EMC Cloud Foundry persistence

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_45.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_46.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_47.jpg)

[A Journey to the Center of the Cloud Foundry - Alex Ley & Ed King, Pivotal Grand Ed King • Alex Ley](https://cfsummit2016.sched.org/event/6ZjZ/a-journey-to-the-center-of-the-cloud-foundry-alex-ley-ed-king-pivotal?iframe=yes&w=i:0;&sidebar=yes&bg=no)

* Well made funny introduction to PCF like 

* Moved to parallel track, maybe link to recording...

* Funny thing: this session was packed! How many of the participants are really deep into CF?

[BoF: Securing a Cloud Foundry Deployment - Alan F. Moran, David Brock, and Luke Rabczak, Allstate: David Brock • Alan F. Moran • Luke Rabczak](https://cfsummit2016.sched.org/event/6aZ3/bof-securing-a-cloud-foundry-deployment-alan-f-moran-david-brock-and-luke-rabczak-allstate?iframe=yes&w=i:0;&sidebar=yes&bg=no)

* same people as yesterday evening in the security x cf session.

* Moved on to parallel track 

[Breaking the CF-Release Monolith - Alvaro Perez-Shirley & David Sabeti, Pivotal: Alvaro Perez-Shirley • David Sabeti](https://cfsummit2016.sched.org/event/6Zjx/breaking-the-cf-release-monolith-alvaro-perez-shirley-david-sabeti-pivotal?iframe=yes&w=i:0;&sidebar=yes&bg=no)

* cf release 

* Diego release 

* How do we scale the core development process / devise it into teams / releases that are still compatible? 

* Everybody is currently pushing to the same release

* Needs breaking the manifest as all components are described here

* Blessed versions come from release integration pipeline

* "How do we CI this"? (default question)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_48.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_49.jpg)

#### [Monitoring Cloud Foundry: Learning about the Firehose - Dustin Ruehle & Tom Collings, ECS Team, Tom Collings • Dustin Ruehle](https://cfsummit2016.sched.org/event/6Zk3/monitoring-cloud-foundry-learning-about-the-firehose-dustin-ruehle-tom-collings-ecs-team?iframe=yes&w=i:0;&sidebar=yes&bg=no)

* Firehose, big giant multiplexer 

* Doppler: cross nodes 

* Traffic controller: cross AZ 

* Rsyslog are not in firehose yet 

* Traffic controller uses web sockets 

* Bosh lite: 10mb/min on vagrant 

* Separate user for everything that consumer nozzler (e.g., firehose.doppler)

* Protocol buffers 

* Firehose-to-syslog resolves guid to app name for cf nozzle

* Memory-based auto scaling. 

* Stop apps of not used (feedback control), saves used app instances. 

* Firehose provides access to orgs and spaces

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_50.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_51.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_52.jpg)

[Diego Runtime Overview - Eric Malm, Pivotal - Eric Malm](https://cfsummit2016.sched.org/event/6Zk6/diego-runtime-overview-eric-malm-pivotal?iframe=yes&w=i:0;&sidebar=yes&bg=no):

* very good presentation, really cutting complexity down.

* future will have runc garden (open container initiative, [https://runc.io/](https://runc.io/))

* Apps: buildpack-app, docker app, Windows app

* Diego workloads 

    * Long running processes 

        * Continual

        * Scalable 

        * Available 

    * Task (App task)

        * Terminating 

        * Singleton (non scalable)

        * Consistent (eg, run exactly once)

* Consul manages all global locks of components 

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_53.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_54.jpg)

![image alt text]({{ site.url }}/public/MUT337qXWbCAc3V8MKowgA_img_55.jpg)

[Auto-Scaling, Watch My Instances Grow and Shrink - Michael Fraenkel and  Bo Yang, IB](https://cfsummit2016.sched.org/event/6Zk9/auto-scaling-watch-my-instances-grow-and-shrink-michael-fraenkel-bo-yang-ibm?iframe=yes&w=i:0;&sidebar=yes&bg=no)M

* Available as incubator 

* IBM, Fujitsu, SAP

* PCF comes with autoscaling, looks like open source can now do that too

* MVP: scaling based on mem

* How about scaling based on prices? -> custom metrics but where do you get the price from?

