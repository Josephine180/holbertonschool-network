# Project: What happens when you type google.com in your browser and press Enter

Background Context
------------------

Being a Full-Stack Software Engineer means you’re comfortable interacting with any layer of the stack.

A way to easily assess this is to simply ask an engineer to explain how a software system works. They can have a general overview of the flow or can choose to dig deep in a certain area.

Let’s practice by exploring the infrastructure side (network, servers, security…) of the question.

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet.project.files/holbertonschool-sysadmin_devops/298/aJPw3mw.jpg)

Requirements
------------

### General

*   You can post your blog post on the platform of your choice, LinkedIn or Medium are good ones
*   A `README.md` file, at the root of the folder of the project, is mandatory

Tasks
-----

### 0\. What happens when...

mandatory

This question is a classic and still widely used interview question for many types of software engineering position. It is used to assess a candidate’s general knowledge of how the web stack works on top of the internet. One important guideline to begin answering this question is that you should ask your interviewer whether they would like you to focus in on one specific area of the workflow. For a front-end position they may want you to talk at length about how the DOM is rendering. For an SRE position they may want you to go into the load balancing mechanism.

This question is a good test of whether you understand DNS. Many software engineering candidates struggle with this concept, so if you do well on this question, you are already way ahead of the curve. If you take this project seriously and write an excellent article, it may be something that will grab the attention of future employers.

Write a blog post explaining what happens when you type `https://www.google.com` in your browser and press `Enter`.

Requirements, your post must cover:

*   DNS request
*   TCP/IP
*   Firewall
*   HTTPS/SSL
*   Load-balancer
*   Web server
*   Application server
*   Database

Publish your blog post on Medium or LinkedIn; share the URL of your blog post in your answer file and in the field below.

Please, remember that these blogs must be written in English to further your technical ability in a variety of settings.

**Repo:**

*   GitHub repository: `holbertonschool-network`
*   Directory: `what_happens_when_your_type_google_com_in_your_browser_and_press_enter`
*   File: `0-blog_post`


### 1\. Everything's better with a pretty diagram

mandatory

Add a schema to your blog post illustrating the flow of the request created when you type `https://www.google.com` in your browser and press `Enter`.

The diagram should show:

*   DNS resolution
*   that the request hitting server IP on the appropriate port
*   that the traffic is encrypted
*   that the traffic goes through a firewall
*   that the request is distributed via a load balancer
*   that the web server answers the request by serving a web page
*   that the application server generates the web page
*   that the application server request data from the database

[Gliffy](/rltoken/psFvxy-j0nALTn_sapK5tg "Gliffy") is free and what I personally use, but feel free to use what fits you best.

Some unrelated examples:

![](http://i.imgur.com/i9ivkdo.png)

![](http://i.imgur.com/R8R3sqC.png)

Share the URL of your diagram image in your answer file and il the field below.

Please, remember that these blogs must be written in English to further your technical ability in a variety of settings.

**Repo:**

*   GitHub repository: `holbertonschool-network`
*   Directory: `what_happens_when_your_type_google_com_in_your_browser_and_press_enter`
*   File: `1-what_happen_when_diagram`
