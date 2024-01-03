# nosql-challenge
GitHub repo for NoSQL homework. 

## Instructions:

Ensure that before running any commands, you have started your local MongoDB environment with the command ```mongod```.

To be able to use this repo for grading purposes, you will need to clone the repo to your local machine. Navigate to the "Resources" folder and run the following command ```mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json```, to upload the json file into your local MongoDB database. 

If you need to re-run any commands for any reason, it is best to go back to the CLI and rerun the import command, as any changes you make going through the notebook will be permanently amended to the databse and will affect the output of earlier commands.

Some assistance from classmates Tia Scott and Davin Frankosky was used in the completion of this homework.
