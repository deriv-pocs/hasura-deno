Let me tell you about Hasura and Deno. I recently used them for app development and I wanted to spread the method. Let us start by exploring what these tools and products are and how they can be useful for app development.

Let us start with Hasura. 

![image](https://user-images.githubusercontent.com/11357486/186637730-5c80a8eb-cdbd-4d62-8f34-462d70d50372.png)

Hasura calls themselves a GraphQ engine that make your data instantly accessible through real-time GraphQL API, so you can create applications, connect to your database, have rest, and GraphQL, endpoints to provide a unified connected real-time secured GraphQL API for your data. 

For front-end developers it can be back-end for front-ends.

We can see an UI that consists of API, data, actions, remote schemas, events and monitoring. From the beginning, the important part would be how to connect to our database to start using other features.

![image](https://user-images.githubusercontent.com/11357486/186637816-936a07cf-82f9-4f95-9736-2b40ffc6cd73.png)


If we click on "Data" tab, we can observe which databases are already connected to the server.

![image](https://user-images.githubusercontent.com/11357486/186637849-d55e8d35-9d45-462b-8251-7889fe50823f.png)


We can see the default database and we also can connect to another database, or create a new one aut
Heroku has cloud offerings with free developer-friendly tears for hobby projects that you can use or  simply move to another cloud provider when the hobby project would move into production stage.

![image](https://user-images.githubusercontent.com/11357486/186637921-512b91c1-b168-4848-b5b3-8ca4ef0780d8.png)


If we click on free Heroku database button we can create a new PostgreSQL Database in Heroku


![image](https://user-images.githubusercontent.com/11357486/186637975-437978a4-0e44-42a0-bd30-516399138b7d.png)

When this is done, we can observe that in the data section of Hasura UI we see our new database is present and new database.

When we open it and connect to it, you can create new tables and columns.


![image](https://user-images.githubusercontent.com/11357486/186638023-2ec6f071-549b-425d-b196-3ee3c6527826.png)
<img width="1353" alt="image" src="https://user-images.githubusercontent.com/11357486/186638144-36babab9-218f-4af3-adcd-c8c769bacfeb.png">

Hasura provides a very comfortable UI to Create Database columns that are very common in front-end development such as unique random ID of the row.

It's a very simple interface to generate very common things like timestamp columns.

That can be just added to that particular table.

And now, if you are satisfied with the table, you can stop here. But let us say we want to have some kind of column for data. We create a new column that will expect data in a particular format such as Text.

Hasura will notify us that we have successfully created a table.

![image](https://user-images.githubusercontent.com/11357486/186638262-a30f9f4c-bf33-4a50-8690-06493b12df62.png)
<img width="433" alt="image" src="https://user-images.githubusercontent.com/11357486/186638387-10fd6a5e-d756-4086-8008-cbd667692275.png">

After successfully creating the table, we see modify section of this particular table, in case we see any errors or adjustments we  would like to make to this table

App Development consists of accessing the data from the databases through query languages, one of them is SQL. Another is GraphQL which is the main selling point of Hasura as it connects with Postgres database to generate GraphQL schema and endpoint for such database.


![image](https://user-images.githubusercontent.com/11357486/186638512-132efa19-473a-4d4d-945f-9f271f029270.png)

You can explore the generated GraphQL endpoint through the GraphicQL tool that lets you create GraphQL queries on the fly and see responses as JSON.


![image](https://user-images.githubusercontent.com/11357486/186638620-413e2467-0c15-4538-addb-59263562c757.png)


After this brief introduction to Hasura, I would like to move on to the second tool that we can use in our creation. Basically, I am running time for our application because we have a back-end and a database, but now we want to have a way to interact with that application. And with that database, and the back-end of it. Through some kind of front-end, whether it's a CLI application, a front-end in a browser application, a mobile application, or some other kind of front-layer for applications where JavaScript and our skills as front-end developers can be used and leveraged.

![image](https://user-images.githubusercontent.com/11357486/186638744-4d3b2db7-c56a-47d5-8878-fe3a6bc30eec.png)


Lets focus on the deployed aspect of that runtime, which in official ways can be done through their cloud provider service called Deno deploy.

Which provides instant deployments in 34 regions for a while with zero configuration zero maintenance on the development side and support for typescript web assembly modules and ECMAScript modules.

We can just fine this for this project to see already existing projects to create new projects. That would be the next step for us to interact with the data.

Whenever we are ready, we can create a new project.


Hello world. This is just a server. What would we want? As well as an example of a playground with JSX.



So you can observe how to develop locally and deploy globally.


In this case, that would be the "Hello World" and "Hello Team".

![image](https://user-images.githubusercontent.com/11357486/186638837-63063785-3a87-404e-8f04-e8019de8047c.png)


When we open a new browser, we can see the "Hello World" immediately in the web browser.


We can now try watch the soundtracks that we implemented before as data in Hasura with some soundtracks URL

And we can see what they are. Answers from our database immediately.

![image](https://user-images.githubusercontent.com/11357486/186638953-26deda59-98c7-4a1f-8dfe-693be92157cc.png)


