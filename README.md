# Ben Merlotti

## About Me  
Hi, I'm Ben! I'm a multidisciplinary creator with a passion for crafting engaging digital experiences. My journey spans video editing, motion graphics, and graphic design, and I've recently ventured into web development with a focus on full-stack projects. I'm always eager to learn, create, and solve challenges in innovative ways.

## Professional  
- **LinkedIn**: [Connect with me](https://www.linkedin.com/in/benmerlotti/)  
- **Portfolio**: Coming soon!  

## Projects

### [Automated Job Scraper & Notifier](https://github.com/benMerlotti/job_board_web_scraper)
An autonomous Python application designed to streamline the job search process by automatically scraping new job listings from a target website and delivering consolidated email notifications. This project showcases a complete data pipeline, from web data extraction and persistent storage to automated notification, demonstrating key skills in backend development, data handling, and system automation.
- **Tech Stack**: Python, BeautifulSoup, Requests, SQLite, smtplib
- **Key Features**
  - Robust Web Scraping: Utilizes the BeautifulSoup library to parse and navigate the HTML structure of a job board, reliably extracting key details from listings, including title, company, location, experience level, and posting date. The scraper is designed to be resilient to minor HTML changes by targeting structural elements over brittle text content.
  - Persistent Data Storage: Scraped job data is stored in a local SQLite database, creating a persistent record of all findings. This allows the system to track which jobs have been seen and processed over time.
  - Duplicate Prevention: Leverages SQL's UNIQUE constraint on job links to automatically prevent duplicate entries, ensuring the integrity of the collected data. A stateful INSERT OR IGNORE strategy is used for efficient data insertion.
  - Stateful Notification System: The application intelligently queries the database to identify only new, un-notified job listings (where is_notified = 0). After a notification is sent, the database is updated to mark those jobs as notified, ensuring users only receive alerts for fresh opportunities.
  - Automated Email Alerts: Integrates with Python's built-in smtplib to automatically format the new job listings into a clean HTML email and send it to a designated recipient. Secure authentication is handled using App Passwords for services like Gmail.
- **Learning Focus**: Data acquisition from unstructured web sources (web scraping), HTML parsing and navigation (BeautifulSoup), database design and management (SQLite), writing clean and efficient SQL queries in Python, building stateful applications, system automation logic, and interacting with external services (SMTP for email).

### [Druid Video Sales Portal](https://github.com/benMerlotti/Druid_ClipMarketplace)
A secure, client-facing web application built to allow a video production company (Druid) to showcase and sell event footage directly to their clients. This project demonstrates a full-stack development workflow, integrating a modern frontend with a Python backend and leveraging core AWS cloud services for scalable and secure file storage and delivery.
- **Tech Stack**: Python, Flask, React.js, AWS (S3, IAM), Boto3, JavaScript (ES6+), HTML/CSS
- **Key Features**
  - Dynamic S3 Integration: The Flask backend communicates directly with AWS S3 to dynamically list video objects based on a client-specific folder structure (e.g., ClientName/EventName/).
  - Secure, On-the-Fly Access: Implements a secure delivery mechanism by generating time-limited S3 Pre-signed URLs. This allows clients to view private videos without exposing the source files or requiring public bucket access.
  - RESTful API Backend: A Flask-based API serves video metadata to the frontend, acting as a secure intermediary between the client's browser and AWS services.
  - Interactive Frontend: A client-side application built with React that fetches and displays a list of available videos, providing a user-friendly interface for browsing content.
  - Cloud-Native Foundation: Utilizes AWS IAM for creating dedicated service users and fine-grained permission policies, adhering to the principle of least privilege for enhanced security.
- **Learning Focus**: Full-stack application architecture, REST API design and development (Flask), frontend state management (React Hooks), integration with major cloud services (AWS S3), cloud security best practices (IAM roles/users, pre-signed URLs), and managing a multi-service development environment (backend server, frontend dev server, cloud services).

### [Movie Tv Recommender](https://github.com/benMerlotti/Movie-Tv-Recommender)
A content-based movie and TV show recommendation system built in Python. This project demonstrates an end-to-end data pipeline, from data collection via the TMDB API, through data cleaning and preparation, to implementing a recommendation engine using TF-IDF vectorization and cosine similarity.
- **Tech Stack**: Python, scikit-learn, requests, JSON
- **Key Features**:
  - Fetches movie data (overview, genres, keywords, cast, director) from The Movie Database (TMDB) API.
  - Cleans and preprocesses textual data to create a "content soup" for each movie.
  - Utilizes TF-IDF to convert movie content into numerical vectors.
  - Calculates cosine similarity between movies to find similar content.
  - Provides movie recommendations based on a user-supplied movie title via a command-line interface (CLI).
- **Learning Focus**: Data pipeline development, API integration, data cleaning, feature engineering (text processing), content-based filtering, and basic machine learning concepts.

### [Tequio Business Ops Manager](https://github.com/benMerlotti/TequioDemoTrack_Capstone)  
A web application designed to manage customer, employee, product, and purchase data while providing actionable insights and streamlined operations.
- **Tech Stack**: React, .NET, SQL Server
- **Key Features**:  
  - Create and manage customer and employee profiles  
  - Track product inventory and purchase records  
  - Generate and download CSV reports  
  - Responsive design optimized for both mobile and desktop use  


### [FlexTrack](https://github.com/benMerlotti/FlexTrack_Capstone)  
A workout tracker web application designed to help users create and manage routines, track progress, and stay consistent with their fitness goals.  
- **Tech Stack**: React, JSON Server
- **Key Features**:  
  - Create custom workout routines  
  - Track sets, reps, and weights  
  - Responsive design for mobile and desktop  

More projects coming soon!  

## Contact  
📧 **Email**: [benmerlotti@gmail.com](mailto:benmerlotti@gmail.com)  




