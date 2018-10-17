# burger
The application allows a user to add a burger that will be initially displayed in the "Not Devoured" section. Then when one clicks on the "Devour" button, the entry shows up in the "Already Devoured"section! </br> 
Once the burger is 'devoured' the user can click the Delete button to delete/remove that entry. This will delete that burger </br>
from the underlying db as well.</br>

Even though I have not deployed to Heroku, I have used the JAWSDB_URL environment variable for db connection details. For locally hosted version, environment variable is "MYSQL_PWD" and stored in an .env file. The .env file type is in .gitignore file. When testing/executing this app locally you need to have your own .env file and provide the value for MYSQL_PWD variable in it.</br>

