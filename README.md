In this article, we’ll be using Docker compose, the cleaner and more systematic method. Here’s how:

1.Check Docker Compose Installation:

**docker-compose --version**

2.Create a new directory for WordPress:

**mkdir ~/wordpress/**

**cd ~/wordpress/**

3.Create a new docker-compose.yml in the new directory and paste the content below. Don’t forget to change the credentials.
Copy the or download docker-compose.yml inthis repo.

4.Run this command in the directory to create the containers:

**docker-compose up -d**

Your browser will enter localhost:8000 and display the WordPress setup screen.

![image](https://user-images.githubusercontent.com/38104778/138898568-540b6129-1a9e-4cc0-b835-18454ef33e9f.png)
