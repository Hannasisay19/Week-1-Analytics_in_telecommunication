# Week-1-Analytics_in_telecommunication
# steps to run the project 
clone the project 
```
git clone git@github.com:Hannasisay19/Week-1-Analytics_in_telecommunication
```
then create a virtual environment
```virtualenv venv
source venv/bin/activate
```
then run the requirements

```
pip install -r requirements.txt
```
add the data to your database

```
psql -U postgres -d telecom -h localhost -p 5432 -f telecom.sql
postgres = user_name
telecom = database_name
telecom.sql = path of sql file
```
