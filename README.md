# PostgreSQL Extension for Chess Game

## Authors
- Antonio Baldari
- Michele Leggieri
- Michael Kahla
- Hongdu Wei

## Overview
This project provides a PostgreSQL extension to analyze chess games using SQL. The extension supports various core functions, btree indexing, and optimization.

## Installation and Testing
Follow these steps to install and run tests:

1. Open a terminal.
2. Navigate to the project folder:
    ```sh
    cd path/to/project/folder
    ```
3. Run the following commands:
    ```sh
    make clean
    make
    sudo make install
    sudo -i -u postgres
    createdb chess
    psql chess
    ```
4. Open the `test.sql` file and copy all the queries.
5. Paste the queries into the terminal to view results about core functions, btree index job, and btree optimization.

## Files in the Repository
- `chess.c`: Main C file for the extension.
- `chess.control`: Control file for PostgreSQL extension.
- `chess--1.0.sql`: SQL file to create functions in the database.
- `Makefile`: Makefile to build and install the extension.
- `test.sql`: SQL queries for testing the extension.
- `report.pdf`: Detailed report on the project.
- `test_database/`: Contains test databases and related files.
