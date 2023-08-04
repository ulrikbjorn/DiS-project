# DiS Project
##### Ulrik Bjørn Meelby, rgt545

## BlueChip Stock Trader
I have implemented a stock portfolio DBMS using Flask for the web layer and PostgreSQL for the database layer. The web-app allows an investor to manage (view and trade) a portfolio of stocks using simulated price data.
 
## How to compile
Assuming that the required dependencies are installed (Besides PostgreSQL, Flask the necessary Python packages can be found in requirements.txt) and the existence of a database scheme corresponding to the ER-diagram (Investor, Portfolio, Market) we have collection of .sql files. First we need to create the database by running 'createdb stockpofolio' in the terminal and subsequently run the schemes using 'psql < filename.sql'. 

The settings of the database can be modified in __init__.py.

## How to run
To run the web-app execute 'python3 run.py' in ther terminal provided the current working directory is the project directory.

## Difficulties encountered
The main reason for my failure to create a working DBMS was that I initially was overly ambitious choosing a too complex system to implement. As the project deadline grew closer I pivoted to a simpler system, but then I encountered a lot of configuration problems which came down to wrong port configurations and depreciated python dependencies. I hope that I have demonstrated a sufficient understanding of RA/SQL queries and relational databases in the mandatory assignments, as this project has not been a success. 

I urge you to consider the fact that I have been working without a group, and furthermore that I am learning in real-time how to study with ADHD. Thank you for reading my submission. 


















