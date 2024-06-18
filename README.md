
# CICS Undergraduate Research Finder - CS320

This web application allows undergraduate students and professors at UMass Amherst to connect over research opportunities. Students can search for professors and labs that are offering research projects. They can view professors' research interests, affiliated labs, and past and ongoing projects. Students can easily contact professors through the application by sharing their research profile, experience, resume, etc. Professors can post information about ongoing research projects and recruit students through the application by viewing their respective research profiles.

## Back End
### Web Server
Our project's web server is built with Python and the Flask Web Framework. The web server handles API endpoint routing as well as the site's authentication system and any data retrieval from the project's database.

### Web Scraper
Our python program scrapes results from several publically available Manning CICS webpages for information about faculty, labs, research areas and ongoing research projects.  

### Database
MongoDB Atlas Database | Multi-Cloud Database Service: currently one database with 5 collections.


## Project Installation

### Backend Virtual Environment Setup

#### Windows
```
  py -m venv .venv                       # Create venv
  py -m pip install -r requirements.tx   # Install python packages
```

#### Mac OS / Linux
```
  cd backend
  python -m venv .venv              # Create venv
  pip install -r requirements.txt   # Install python packages
```

### Running Flask Server

#### Windows

```
  cd backend
  .venv\Scripts\activate            # Enter venv
  flask --app app run               # Run Flask App
```

#### Mac OS / Linux

```
  cd backend
  source .venv/bin/activate         # Enter venv
  flask --app app run               # Run Flask App
```

### Frontend Quickstart

```
  cd frontend/project
  npm install
  npm install -g @angular/cli
  ng serve --open
```
