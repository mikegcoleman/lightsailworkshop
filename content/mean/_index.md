+++
title = "Deploy and Scale a MEAN App"
weight = 70
+++

This section of the workshop workshop consists of two hands-on labs. In the first lab you will deploy a simple two-tier MEAN application in a single Lightsail instance. This single instance will house both the web front-end (written in Node.js with Express) as well as a MongoDB database. You'll deploy this instance from Lightsail's preconfigured MEAN blueprint. 

In the second lab you'll deploy the web front-end and the MongoDB database into their own instances. This will allow you to scale the front-end independently of the database. You'll accomplish this by creating a snapshot of the front-end instance, and then deploying two additional instances based off that snapshot. From there you'll put all three of the web front end instances behind a Lightsail load balancer in order to provide some fault tolerance as well as horizontal scalabilty