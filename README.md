# Sixty-Second-Server

There is a way to set up an incredibly simple backend server running on your localhost. It will be a Node project.
All it needs is a JSON file

# Steps:

1. Make a directory and give it a name

2. cd into that directory

3. npm init

4. Follow the setup by providing basic info for your Node project

5. npm install json-server -g

6. Make a db.json file => touch db.json

7. In package.json write a start script as => json-server -p 9000 -w db.json

8. Use dummy JSON data, or make your own and put it in db.json

9. npm start

10. There you have it!
