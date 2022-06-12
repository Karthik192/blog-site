# blog-site
### This is a test blog-site v1.

It consists some default blog posts and you can add more info by going to the **`/compose`** route

It is not hosted on a Web server though.

So, you need to host the website locally on **`port 3000`**.

# Blog Website Readme file

 This is a blog website which is an online journal where an individual, group, or corporation presents a record of activities, thoughts, or beliefs.

## How to run the server
Here, we need to setup two local servers. One for the database and one for the website backend.
#### Steps to setup database:
1. Install MongoDB by visiting the official website (https://www.mongodb.com/try/download/community) and downloading the latest community installer. You need to sign up first to be able to download.
2. After installing MongoDB, you need to create a directory **/data/db** exactly with the same name (case sensitive) so that the database will be stored inside that directory.
3. Create a .bash_profile folder in the root directory and edit it using vim editor and insert **alias mongod="/c/Program\ Files/MongoDB/Server/5.0/bin/mongod.exe"** and **alias mongo="/c/Program\ Files/MongoDB/Server/5.0/bin/mongo.exe"**
4. Run the command **mongod** which then starts the server on **localhost:27017**
5. Now run command **mongo** to open the MongoDB shell.

#### Steps to setup local server:
1. Download and install NodeJS in the official website (https://nodejs.org/en/download/).
2. Run the command **npm init** which initializes the web directory structure and adds the node modules.
3. Now delete all the folders except **node modules** and paste all the codes using the same directory structure as provided.
4. Install the library files required by using command **npm i express ejs lodash mongoose**
5. Now you can run the server by using command **node app.js** which in turn runs the website on **localhost:3000**
