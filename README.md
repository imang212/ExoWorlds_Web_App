# Exoplanets web app

![image](https://github.com/user-attachments/assets/0fc859d3-5dc8-4c22-835c-6e1ddf38eda1)

ExoWorlds is a web-based application designed for the exploration and management of exoplanet data. The project leverages structured data formats and server-side processing to provide a seamless interface for interacting with celestial datasets.

### Tech stack
- **database**: PostgreSQL (used Python for csv format preprocess)
- **Backend**: PHP(AJAX)
- **Data Formats**: XML, XSD
- **Frontend**: JavaScript, HTML5, CSS3 (Vanilla CSS), Tailwind (styles)

Run in Docker environment with 4 containers.: web_exoplanets (PHP 8 Apache), Tailwind, postgres_db_exoplanets, admirer_exoplanets

### Database
Database is from Official NASA Exoplanets Archive web (https://exoplanetarchive.ipac.caltech.edu/) downloaded as csv and preprocessed in Python Pandas to format compatible with PostgreSQL. And another csv table from adityamishraml on kaggle.com, which is also from NASA Exoplanets Archive, but with more decribing columns which are usefull. I connect these two tables in PostgreSQL into one table exoplanets and created dimensional tables to exoplanets table.
