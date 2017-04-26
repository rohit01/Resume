# Rohit Gupta

  * hello [AT] rohit.io
  * Blog: <http://www.rohit.io>
  * Github: <https://github.com/rohit01>
  * LinkedIn: <http://www.linkedin.com/in/rohit01>
  * Docker Hub: <https://hub.docker.com/r/rohit01>

## Experience Summary:

 1. **Company: ANI Technologies (aka OlaCabs) - <https://www.olacabs.com> (January 2016 - present)**  
    Ola is the most popular cab booking service in India. It has a presence in over 100 cities and caters to million+ bookings per day.

    **Production Engineer II (January 2016 - present):**  
    Working as an individual contributor towards building a highly scalable and reliable microservices-based infrastructure platform. Some of the projects I own include the centralized logging platform (Graylog), metrics platform (Prometheus, OpenTSDB) and cluster management (Mesos/Marathon).

 2. **Company: Knowlarity - <http://www.knowlarity.com> (1 year, 6 months)**  
    Knowlarity is India’s largest cloud telephony company backed by investors like Sequoia Capital and Mayfield.

    **Technical Lead - DevOps (June 2014 – November 2015):**  
    Lead a team of nine developers to write infrastructure as a code. Kick-started many automation projects, replaced legacy monitoring systems, helped improved processes, application architecture and built the team.

 3. **Company: Plivo - <https://www.plivo.com> (1 year, 11 months)**  
    Plivo is a silicon valley (US) based telephony startup backed by Y-Combinator (YC) and investors like Andressssen Horowitz, Battery ventures and Qualcomm.

    **Devops Lead (January 2014 – March 2014):**  
    Lead the Indian devops team of 8 members. Closely worked with customers, product team, Infrastructure team, founders and sales team. Gave trainings on the engineering and customer support aspects which helped improve quality of support, team bonding and productivity.

    **Product Engineer (September 2013 – January 2014):**  
    Worked on Plivo cloud APIs and core media/telephony technologies. It involved working with most of the technologies used by Plivo, viz.: Python Django framework, Python Flask, FreeSWITCH, SIP, REST APIs, redis, etc.

    **Lead Infrastructure Engineer (May 2012 – September 2013):**  
    Kick-started project 'Tank', a solution over AWS to manage Plivo infrastructure. The solution was the first engineering step taken by Plivo to ensure high availability and scalability of cloud and dedicated server infrastructure. The role also involved setting up automated server monitoring and API service monitoring for status board.

 4. **Company: Tata Consultancy Services (TCS) - <http://www.tcs.com> (10 Months)**  
    Tata Consultancy Services Limited (TCSL) is a multinational information technology (IT) service, consulting and business solutions company headquartered in India.

    **Assistant Systems Engineer - Trainee (July 2011 – April 2012):**  
    Started my career with Initial Learning Program (ILP) Training at TCS. Lead a batch of 41 people as a CR and a group of 3 members as a project group lead. Was awarded 'Star of the Learners Group' and 'Certificate of Appreciation' in TCS Gems for finding a place in LIREL Honor Rolls.

## Technical Skills:

  * Programming Languages:
      * Present proficiency: golang, Python, Ruby, Shell scripting (bash)
      * Past proficiency: C, Java, Lua
  * Operating Systems: OS X (Mac), Linux (Debian, Ubuntu, CentOS)
  * Configuration management: Ansible, Chef
  * Cloud computing: Amazon Web Services (EC2, ECS, S3, Route53, SES, RDS, Cloudfront, etc), Rackspace
  * Monitoring: Prometheus, OpenTSDB, Shinken, Nagios, NRPE plugins
  * Administration: Linux Systems, Docker, Mesos Marathon Clusters
  * Tools: Kafka, Elasticsearch, Graylog, Heka, Filebeat, fluentd, cadvisor, sentry
  * Web framework: Python Flask


## Projects:

  * **Graylog - Centralized logging platform (April 2016 – present):**  
    With a vision to support micro-services at scale, dozens of transparent releases a day, we built a centralized logging platform using open-source tools like Fluentd, Heka, Kafka, Graylog and Elasticsearch. It is a truly scalable system which handles 500k+ messages per sec, billion+ messages per hour and 100TB+ queriable log at any given point of time.  
    FOSS Asia 2017 Talk: <https://youtu.be/ZkRPj34UWfs>

  * **Centralized monitoring - Prometheus & OpenTSDB (February 2016 – present):**  
    Did setup, automation and designed a custom alert routing logic for monitoring critical systems and applications. Prometheus supports both static and dynamic (service discovery based) targets for pulling metrics. Push mode for metrics is supported by OpenTSDB. Documentation is auto-generated in confluence which serves as runbook for OnCall.

  * **Mesos/Marathon/Chronos cluster (February 2016 – November 2016):**  
    Involved in setup, automation and design of the Mesos/Marathon/Chronos cluster for production-grade container orchestration. This serves as the backbone for powering most micro-services at Ola.

  * **Dr. Octopus - Event driven infra failovers (September 2016 - present):**  
    This project is written from scratch using golang and zookeeper. It detects internal infra failures at high-speed and reliably using multiple servers at different physical locations. Once a failure is detected, it reacts to the event by performing automatic failovers. The application is configurable using REST APIs. It emits OpenTSDB metrics for Grafana dashboard and alerting.

  * **Bloody Mary (November 2016 - March 2017):**  
    This project is written from scratch using golang. It takes monitoring to a new level by generating metrics from HAProxy logs in real-time. The metrics are used to generate Grafana dashboards per application domain (DNS / vhost). The metrics are also used for custom alerts per application using Bosun.

  * **Konfilarity (July 2014 – November 2015):**  
    Started konfilarity as an internal project of knowlarity for configuration management. It helped improve release processes, server deployments, security, DNS management and is still an evolving project.

  * **Shinken (July 2014 – November 2015):**  
    Replaced legacy monitoring system - Nagios with Shinken. Introduced new paradigms like Multi DC deployment, unified agent configuration, end to end automation, frequent and easy releases, ease of adding new features plus hosts.

  * **SethJi (December 2014 – January 2015):**  
    A python flask application to generate AWS billing reports based on tags.  
    Project Link: <https://github.com/rohit01/sethji>

  * **Docker Shinken (December 2014):**  
    Automated build repository for 'shinken', 'shinken\_thruk' and 'shinken\_thruk\_graphite' docker registry images.  
    Project Link: <https://github.com/rohit01/docker_shinken>  
    Related blog post: <http://www.rohit.io/blog/rip-nagios-hello-docker-shinken.html>

  * **Zero Users (August 2014 – September 2014):**  
    Zero hassle native linux user management. Built with ♥ and Ansible.  
    Project Link: <https://github.com/rohit01/zero-users>

  * **Dikhao (February 2014 – July 2014):**  
    Dikhao is an opensource project to cache every EC2, Route53 resource, find relations between them, and provide really fast lookups. It can be installed as a python command line utility (pip install dikhao), deployed in heroku and has a ready to use hubot plugin.  
    Project Link: <https://github.com/rohit01/dikhao>

  * **PlivoCloud (September 2013 – January 2014):**  
    PlivoCloud is an internal project of Plivo which powers all HTTP APIs. It is built using Python Django Web Framework, Flask Microframework and makes extensive use of python libraries.

  * **PlivoCommercial (September 2013 – January 2014):**  
    PlivoCommercial is an internal project of Plivo which handles the core telephony in media servers. Built on top of the opensource softswitch: FreeSWITCH, it provides easy to use internal telephony APIs.

  * **Tank (May 2012 – September 2013):**  
    Project Tank is Plivo's high availability solution over AWS. It also includes automated server monitoring using an opensource nagios like tool - Shinken. The project extensively uses many python libraries and custom NRPE plugins.

  * **Plivo Statusboard (May 2012 – September 2013):**  
    Worked on the backend of the Plivo statusboard. The project involved implementing a 24X7 automated monitoring of Plivo HTTP APIs like calls, Conference, SMS and account related APIs.

  * **Android Sudoku Solver (January 2012 – April 2012):**  
    An Android application to solve sudoku puzzles of all difficulty levels (including diabolical). The algorithm used to solve the same was developed personally.  
    Project Link: <https://github.com/rohit01/AndroidSudokuSolver>

  * **TCS BαNCS Service Integrator (October 2011 – April 2012):**  
    Service Integrator (SI) is a simple and flexible solution that integrates systems with minimal changes for existing applications, supports technologies – old and new and financial messaging standards. The application makes use of Java, ANT, Unix shell scripts, XML, DB (SQL), Hudson framework

  * **National Self Employment Program - NSEP (July 2011 – September 2011):**  
    Developed the NSEP Account Management module of NSEP project. NSEP was a prototype project for the Government of India to encourage entrepreneurship among young graduates.

  * **StegoSoft (July 2010 – June 2011):**  
    Developed a steganography application using enhanced least significant bit (LSB) algorithm. It can be used to hide information in an audio medium without any apparent change in the size or quality of the audio file.  
    Project Link: <https://github.com/rohit01/stegosoft>

## Achievements:

  * Speaker at Conferences: FOSS Asia 2017, The Fifth Elephant 2016, PyCon India 2015, PyCon Singapore 2013, PyCon India 2012
  * Received the award for 'Star of the Learners Group' at TCS Trivandrum on 23/09/2011
  * Received 'ILP Top Performer (13-Oct-2011)' award for outstanding performance in Initial Learning Program (ILP) of TCS at Trivandrum
  * Received 'Certificate of Appreciation' in TCS Gems for finding a place in LIREL Honor Rolls – a recognition program for excellent professional conduct and work ethics
  * Won the 1st prize in the 'Konfigure' event (Shell Programming competition) of 'MUKTI 11.2', a National level Technical Symposium on GNU/Linux and Free Software held from February 4 to 6, 2011, at NIT Durgapur
  * Founded ‘GNU/Linux User Group of KGEC', which provided a platform for discussions amongst Linux users and creating awareness / interest for the same

## Initiatives:

  * Promoted learning and sharing culture through tech sessions, meetups and conferences
  * Have lead teams and technical projects many times, right from the start of my professional career
  * Promoted FOSS, conducted tech events, maintained Linux servers at the university

## Educational Qualification:

  * B. Tech in Information Technology (2007-2011)  
    Institution: Kalyani Government Engineering College  

  * CBSE - XII (2006-2007)  
    Institution: Guru Teg Bahadur Public School  

  * ICSE - X (2004-2005)  
    Institution: Assembly of God Church School  

## Recommendations:

  * **Michael Ricordeau - Co-Founder, Plivo (YC S2012):**  
    Rohit is passionate by his work. He has a very good knowledge of cloud technology and can solve all sort of hard problems (failover, scalability, monitoring, load balancing) for any Saas/Paas infrastructure.  

  * **Vimal Gupta - Senior Director, Knowlarity Communications:**  
    Rohit, A highly motivated DevOps professional who has excellent technical skills and a can do attitude. He love to solve the Critical DevOps problems and always ready to learn. He understand the business needs as well and this enables him to align his tasks with business goals. He is also a very good mentor, a very good team player as well as a lead. I wish him a very bright career ahead.  

*last update: April, 2017*
