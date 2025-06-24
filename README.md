# Exoplanets web app

![image](https://github.com/user-attachments/assets/0fc859d3-5dc8-4c22-835c-6e1ddf38eda1)

### Languages

database: PostgreSQL (used Python for csv format preprocess)

backend: PHP 8 Apache

HTML, JavaScript, XML, XSD 

styling: Tailwind, Vanilla CSS

Run in Docker 4 containers.: web_exoplanets (PHP 8 Apache), Tailwind, postgres_db_exoplanets, admirer_exoplanets

### Database
Database is from Official NASA Exoplanets Archive web (https://exoplanetarchive.ipac.caltech.edu/) downloaded as csv and preprocessed in Python Pandas to format compatible with PostgreSQL. And another csv table from adityamishraml on kaggle.com, which is also from NASA Exoplanets Archive, but with more decribing columns which are usefull. I connect these two tables in PostgreSQL into one table exoplanets and created dimensional tables to exoplanets table.
