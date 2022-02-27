1. CREATE VIRTUAL ENVIRONMENT WITH py -m venv env
2. Activate virtual environment with env\scripts\activate
3. Install dependencies with pip install -r requirements.txt
4. Supply database connection credential in database.ini
5. Note : This will only work for a postgres database
6. You can add more queries in the db_queries.json file
7. Group queries you want to get reports for in the same .json file and change the queries file name on line  8 of reports.py
8. Provide a name for which to save your files on line 9 of reports.py
9. Run reports.py
10. A folder named report_files will be created and will store your reports"# Database-Reports" 
