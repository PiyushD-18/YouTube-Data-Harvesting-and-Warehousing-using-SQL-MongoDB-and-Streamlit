# YouTube-Data-Harvesting-and-Warehousing-using-SQL-MongoDB-and-Streamlit

Step 1: Set Up Your Environment
Make sure you have Python installed on your system.
Create a virtual environment for your project.
Install Streamlit, pymongo (for MongoDB), and any other necessary packages.

Step 2: Obtain API Keys
You will need API keys for the YouTube Data API, Google API, and the SQL database (e.g., SQLite, MySQL, or PostgreSQL). Obtain and secure these keys.

Step 3: Create the Streamlit Application
Create a Streamlit Python script (e.g., app.py) for your application.

Step 4: User Interface Design
Design the Streamlit app's user interface with input fields, buttons, and data display components to meet the specified features.

Step 5: Retrieve YouTube Channel Data
Implement the functionality to input a YouTube channel ID and use the YouTube Data API to retrieve the relevant channel data (channel name, subscribers, total video count, playlist ID, video ID, likes, dislikes, comments of each video).
Display the retrieved data in the Streamlit app.

Step 6: Store Data in MongoDB
Provide an option to store the retrieved data in a MongoDB database as a data lake. You'll need to set up a MongoDB connection and create a collection to store the data.

Step 7: Collect Data for Multiple Channels
Implement the ability to collect data for up to 10 different YouTube channels and store them in the data lake by clicking a button.
Allow users to input multiple channel IDs and loop through the data retrieval process for each channel.

Step 8: Migrate Data to SQL Database
Provide an option to select a channel name and migrate its data from the data lake (MongoDB) to a SQL database as tables (e.g., SQLite, MySQL, or PostgreSQL).
Establish a connection to the SQL database and create the necessary tables.

Step 9: Search and Retrieve Data from SQL Database
Implement the ability to search and retrieve data from the SQL database using different search options. Allow users to specify search criteria and perform queries on the SQL database.
Implement the ability to join tables to get channel details if required.

Step 10: Testing and Debugging
Thoroughly test your Streamlit application to ensure all features work as expected.
Debug any issues or errors that arise during testing.

Step 11: Deployment
Deploy your Streamlit application to a web server or platform of your choice. Ensure that it is accessible to users.
