## Set up FINN preprocessor without using docker

in case you want to set up finn propcessor on your system, this is the step to follow.

### 0. Prerequites

* postgresql is installed/running, on port 5432
* psql is installed (command line client)
* super user name is 'postgres', and no password is set

### 1. Setup database and user

Good reference is available from official postgis website https://postgis.net/documentation/getting_started/ 

1. Login to database as database administrator.  From bash (or other command line interface), use folloing command.
   ```bash
   psql -U postgres
   ```
   You should see a prompt from database like this:
   ```console
   psql (10.23)
   Type "help" for help.
    
   postgres=#
   ```
   
