## Create a MySQL Database with RDS(AWS)

Got to your AWS Console & Search for RDS then Open it.
<p align="center"><img src="Images/1.jpg" style="border-radius:50%"/></p>
Now click on Create a Database

Now select the Engine we are using MySQL with version 8.0.30

Templates Should be Free Tier, so it will not charge anything
<p align="center"><img src="Images/2.jpg" style="border-radius:50%"/></p>
Give your Database Name & Password (should be 8 characters)

Choose Instance as db.t2.micro 
<kbd><img src="Images/3.jpg"/></kbd>
</br>
Storage Allocated as 20 GiB
<p align="center"><img src="Images/4.jpg"/></p>
Enable Storage Autoscaling, we are using 22 Gib as Maximum threshold 
<p align="center"><img src="Images/5.jpg"/></p>
We are also Activating the Backups with 7 Days of Retention 
<p align="center"><img src="Images/6.jpg"/></p>
Let the remaining Settings as it is & Click on Create a Database.

It will Take Some Time to Create a Database, MySQL Database Successfully Created with RDS AWS Service
<p align="center"><img src="Images/7.jpg"/></p>

Follow For More Devops: -

https://www.linkedin.com/in/devops-learning
