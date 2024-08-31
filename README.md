# Voyage Vista
-------------
### Usage :
- Clone the repository to your local machine using the following command: ```git clone git@github.com:Git-Cat-21/Voyage-Vista.git``` 
- Change into the project directory:  ```cd Voyage-Vista```
- Ensure that you have Node.js and MongoDB installed. If not, you can follow the installation tutorials:
- [Node.js installation guide](https://www.youtube.com/watch?v=06X51c6WHsQ)
- [MongoDB installation guide](https://www.youtube.com/watch?v=gB6WLkSrtJk)
- If you're using Visual Studio Code, make sure to install the Live Server extension.
- Open the index.html file, right-click, and select "Open with Live Server."
- Open your preferred browser and navigate to localhost:5500 to start using Voyage Vista

-------

### Signup-page/Login-page/Booking-page:
- Open your terminal and execute the following command:  ```node server_signup.js```/ ```node server_login.js```/ ```node server_book.js```
- After running the command, navigate back to the webpage and complete the signup form/ login form/ booking page.
-------

### Database Access:
- All data is stored in MongoDB under the mydatabase database within the users collection. 
- You can view the data using MongoDB Compass or via the terminal with the following commands:
1. Run ```mongosh``` in your terminal.
2. Switch to the database with ```use mydatabase```
3. View the user data with ```db.users.find().pretty()```
4. Good luck exploring your data!
