# DiS Project
##### Ulrik Bjørn Meelby, rgt545

## BlueChip Stock Trader
I have implemented a stock portfolio DBMS using Flask for the web layer and PostgreSQL for the database layer. The web-app allows an investor to manage (view and trade) a portfolio of stocks using simulated price data.
 
## How to compile
Besides PostgreSQL and Flask, the necessary Python packages can be found in requirements.txt. After the required dependencies have been installed the database can be created by executing 'createdb bluechip' in the terminal. Load the database schemes by executing 'psql bluechip < filename.sql'. The settings of the database can be modified in __init__.py.

## How to run
To run the web-app execute 'python3 run.py' in the terminal, which will host the web-app from http://127.0.0.1:5000. 














