# DiS Project
##### Ulrik Bjørn Meelby, rgt545

## Stock Portfolio
I set out to develop a stock portfolio DBMS using Flask for the web layer and PostgreSQL for the database layer. The web-app would allow an investor to manage (view and trade) a portfolio of stocks using the publicly available Yahoo Finance API. 
Unfortunately, the endevaour proved to complicated given the time and resources at my disposal (1-person group) thus leaving me without a functioning application. 

In the sincere hope that I might be able to pass the project anyway, I have written about the project to demonstrate some knowledge of the course material.  

## How to compile
Assuming that our dependencies are installed (PostgreSQL and Flask) and the existence of a database scheme corresponding to the ER-diagram (Investor, Portfolio, Market) we have collection of .sql files. First we need to create the database by running 'createdb stockpofolio' in the terminal and subsequently run the schemes using 'psql < filename.sql'. 

The settings of the database can be modified in __init__.py.

## How to run
To run the web-app execute 'python3 run.py' in ther terminal provided the current working directory is the project directory.

## How to run


















