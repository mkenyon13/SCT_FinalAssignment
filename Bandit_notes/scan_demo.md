## Running bandit on isd_project

### scan the entire folder
- bandit -r/ ../Final_Project

### scan a single file
- bandit my_file.py

### Generate the report
- bandit -f html -o report.html ../Final_Project