+++
title = 'Digital Ocean'
date = 2024-02-28T00:45:03-05:00
disableToc=true
+++
# Digital Ocean 
Digital Ocean is a cloud hosting service provider that we use to host all of the endpoints of 
our website and even the database. Here we will go over the in's and out's of the website.

https://www.digitalocean.com/


{{< figure src="img.png" title="title of image" width="400">}}

After logging into DO, this will be the landing page you will be greeted with. 

## Side Banner
Over on the side of the page is where you navigate to the different "projects" we have hosted

![img_1.png](img_1.png)

The first tab is the default project DO makes for you, we have our database hosted here

![img_2.png](img_2.png)

The circled database cluster is the database that website is pulling from. The cluster above that is a test database

![img_3.png](img_3.png)

The next three "projects" is the website itself split up into 3 parts.

Each are set up the same way so we will look at the Scheduled Message Manager as an example.

![img_4.png](img_4.png)

If you click into Schedule Message Manager you will see these three apps, that is the project. Each one has its own Github Repo that they are being pulled from. 

![img_5.png](img_5.png)
Unfortunatly we did not get a single application with all the plugins working so to access the website, you click this second field to take you to the URL. This is true for all Front-end apps. 

![img_6.png](img_6.png)
Clicking into settings allows you to view the most important aspects like which Repo the app is pulling from or the environmental variables.


