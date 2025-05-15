### Hi there 👋
Welcome to my GitHub Repository!

🌱 I am currently seeking an opportunity to apply the solid foundations acquired through the CFG Full Stack Web Development and Data Science boot camps in a professional work environment.
Here are just a few of the projects I have worked on during the boot camps and independently afterwards. 

## 😄 About Me 

I am a resourceful web developer and budding data scientist with a strong interest in building innovative and impactful solutions. I love exploring new technologies and solving complex problems. My areas of expertise include:

### Skills:
- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Backend:** Python, Node.js, Express, Flask  
- **Database management:** MySQL, SQlite, SQL Alchemy ORM
- **Machine Learning:** numPy, Pandas, Seaborn, SKLearn, spaCy
- **NLP:** spaCY
- **Data Analysis:** data cleaning and preprocessing- handling missing values and inconsistent data entry, scaling and normalisation, parsing dates
- **Data Visualization:** Matplotlib, PowerBI
- **Tools:** Machine Learning, DBMS


## 🌱 I'm currently learning

I'm constantly expanding my knowledge and exploring new domains. Currently, I'm focusing on SigRec, a web application for the management of signalling records drawing on over two decades of experience in a design office.

**Key Concepts:**
- Application factory pattern (create_app)
- Modular Flask blueprint architecture
- Form multi-row processing
- SQLAlchemy ORM for database modeling
- Record deduplication and error handling
- Basic user feedback with flask.flash
- Render deployment with environment variables
   
**Languages:**
- Python (Backend)
- HTML, CSS (Frontend templating)
- Jinja2 (Templating engine)
  
**Frameworks and libraries:**
- Flask
- SQLAlchemy
- Bootstrap (via CDN)
  
**Cloud Platforms:**
 - Render — hosting & deployment
 - GitHub — version control
 - SQLite (via Flask SQLAlchemy) — file-based database (non-persistent across deploys)


## 🔭 Projects

## SigRec webb app in Flask with SQlite 

### Project history

### Phase 1: MySQL Database Creation and Recovery  
I initially developed mysigrecdb during the CFG Data & SQL course as my capstone project.
My first objective was to design core tables and relationships for a database managing signalling records used in a design office. However, upon revisiting the project, I discovered that my original files had been corrupted during a computer transfer, leaving only partial data intact. To recover my work, I leveraged a clean `db.mwb` to forward-engineer the database, re-generating tables and relationships.
Using the `mysql.connector` and `pandas` libraries alongside the `os` module, I automated the process of reading `.csv` files containing table data into DataFrames. Since my database schema and `.csv` files originated from different development stages, I turned this recovery process into an opportunity to identify and resolve missing data, errors, and inconsistencies.

### Phase 2: Transition to Flask and Web App Development  
During my time in the CFG Full Stack Bootcamp, I learned about Python and the Flask web framework, which inspired me to transform my standalone database project into a fully functional web application. I dedicated myself to learning Flask in depth, along with key supporting technologies such as Jinja2 for templating, SQLAlchemy for ORM-based database management, and Bootstrap for responsive UI design. This phase also included understanding web forms, routing, error handling, and deployment processes — all of which were essential to building and deploying a scalable and modular Flask application.

### Phase 3: Deployment and Ongoing Enhancements
After completing development of the core features, I focused on deploying the application to a live environment using Render, a modern cloud platform. I configured the project for production with an app factory structure, used Gunicorn as the production-ready WSGI server, and securely managed sensitive data like secret keys through environment variables.
For deployment, I switched from MySQL to SQLite to simplify the setup, but I'm planning a future migration to PostgreSQL for greater reliability and persistence across deployments.

Planned improvements include:

- Adding a secure user login system with role-based access for different teams (Design, Record Control, Management).
- Full implementation of the Design and Management modules to complement the fully functional Record Control system.
- Migrating from SQLite to PostgreSQL to ensure long-term data persistence and scalability.

This phase marks the shift from a local prototype to a maintainable, production-ready web application.





### Natural Language Processing - Creating a 'Netflix Recommendation System' in Python with spaCy: watch_next.py

The objective of this project is to develop a Netflix recommendation system using natural language processing techniques in Python. The system compares the similarity between a given movie description and a collection of other movie descriptions to generate personalised recommendations.

### Python Variables and Control Structures project: finance_calculators.py

This task required creating a program that allows the user to access two financial calculators: an investment calculator (where there is a choice of simple or compound interest) and a home loan repayment calculator based on information provided (interest rate, number of years invested/ needed for the repayment, simple or compound interest). 

### Hangman Python game : hangman.py

Independent project to strengthen my understanding of OOP concepts learned during the CFG boot camp by creating a class-based Hangman game.





