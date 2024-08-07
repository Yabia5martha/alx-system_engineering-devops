# 0x11. What happens when you type google.com in your browser and press Enter

In this project, I was asked to write an article to explain all about the web 2.0 infrastructure. Understanding this concept is very important for me as a Fullstack Software Engineer. Reviewing and encapsulating networking knowledge and skills I had been learning
and practicing over the last month, in this project, I wrote a blog post
answering the classic interview question - "What happens when you type a URL into a browser and hit `Enter`?"

## Task Responses :page_with_curl:

* **0. What happens when...**
  * [0-blog_post](./0-blog_post): Text file containing the link to my blog post.

* **1. Everything's better with a pretty diagram**
  * [1-what_happen_when_diagram](./1-what_happen_when_diagram): Text file
  containing the link to a diagram put together to visualize the networking
  process described in my blog.

## Project Questions and Requirements :☑️

### Task 0

This question is a classic and still widely used interview question for many types of software engineering position. It is used to assess a candidate’s general knowledge of how the web stack works on top of the internet. One important guideline to begin answering this question is that you should ask your interviewer whether they would like you to focus in on one specific area of the workflow. For a front-end position they may want you to talk at length about how the DOM is rendering. For an SRE position they may want you to go into the load balancing mechanism.\
This question is a good test of whether you understand DNS. Many software engineering candidates struggle with this concept, so if you do well on this question, you are already way ahead of the curve. If you take this project seriously and write an excellent article, it may be something that will grab the attention of future employers.\
Write a blog post explaining what happens when you type https://www.google.com in your browser and press Enter.

Requirements, your post must cover:
- DNS request
- TCP/IP
- Firewall
- HTTPS/SSL
- Load-balancer
- Web server
- Application server
- Database

Click [here](https://medium.com/@siiyabiamartha/what-happens-when-you-type-google-com-in-your-browser-and-press-enter-434f97df6576) to read my article.

### Task 1
Add a schema to your blog post illustrating the flow of the request created when you type https://www.google.com in your browser and press Enter.\
The diagram should show:
- DNS resolution
- that the request hitting server IP on the appropriate port
- that the traffic is encrypted
- that the traffic goes through a firewall
- that the request is distributed via a load balancer
- that the web server answers the request by serving a web page
- that the application server generates the web page
- that the application server request data from the database

I hosted the diagram image [here](https://imgbox.com/19dkbksY)