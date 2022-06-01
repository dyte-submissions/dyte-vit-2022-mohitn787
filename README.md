RUN THE dyte_main.py script<br?
--> give the commmand as input to the dyte_main.py script<br>
--> make sure that the input file is in the same directory as that of the dyte_main.py file
--> if update is not mentioned then the output file is "first.csv"
--> if update is mentioned then second.csv is the output file containing the pr_request link also

Additional features
--> A commented function is there in the script by the name "get_all_version()". which can returen the all the individual dependencies of the package.json file
--> A commented function by the name of "scrape_data()" is there, which can match the obtained dependencies from the official node-npm-package website using web scraping
--> It also has the feature of adding a issue to the repo, and using the issue id it can create a new pull request
