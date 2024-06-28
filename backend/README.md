### Web Server
Our project's web server is built using Python and the Flask Web Framework. The primary responsibilities of the web server include:

- **API Endpoint Routing:** Handling of API endpoints for various functionalities such as user authentication, data retrieval, and interaction with the front end.
- **Authentication System:** Implementation of authentication system to secure user access.
- **Database Interaction:** Facilitation of data retrieval and storage operations with the project's MongoDB database.

### Web Scraper
Python-based web scraper responsible for gathering data from multiple publicly available Manning CICS webpages. The scraper extracts information related to faculty, labs, research areas, and ongoing research projects. [Scraper ReadME](https://github.com/ckausika/CS320-Team-U/blob/main/scraper/README.md)

### Database
MongoDB Atlas Database | Multi-Cloud Database Service: Key aspects of our database setup include:

- **Database Structure:** Utilizing a single MongoDB database with five collections to store various types of information, including user data, professor profiles, lab details, research areas, and ongoing research projects.
- **Data Management:** Implementing efficient data management strategies to organize, retrieve, and update information stored in the database.
- **Scalability:** Leveraging MongoDB Atlas's scalability features to accommodate future growth and increasing data volumes as the application usage expands.
