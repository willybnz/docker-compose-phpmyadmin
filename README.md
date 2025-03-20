# docker-compose-phpmyadmin
Deploying phpMyAdmin with Docker Compose for easy MySQL/MariaDB management.

# how to test 

You need to type the following command: <br>    
-    docker compose up -d  <br>

Then once this is done you can access the web interface by typing:<br>
-    http://localhost:8080

Once you have access to the graphical interface you can select your database in our case it is mydatabase and then create the tables directly.

![graphical_interfaces](images/Capture%20d'écran%202025-03-20%20153042.png)

Similarly we can check access to mysql from our container by typing: <br>
-    docker exec -it mysql_db mysql -u root -p <br>

In my case I tried to create a table directly from my container where I have access to my database.

![container_access](images/Capture%20d'écran%202025-03-20%20154432.png)

