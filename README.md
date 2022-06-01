IMPORTANT POINTS TO RUN THE dyte_main.py script

--> give the commmand as input to the dyte_main.py script

--> make sure that the input file is in the same directory as that of the dyte_main.py file

--> if update is not mentioned then the output file is "first.csv"

--> if update is mentioned then upgrade.csv is the output file containing the pr_request link also

--> The link added into the pr_link list is the link of the pull request made by self

--> All the github actions is done using the Github API, secret access token is also mentioned to verify the same

--> All the code is written in python, and the style of coding is procedural

--> To fetch the version number from the package.json file from github, I have created 2 functions both of which are capable of doing the same work, but when run in a      loop, the first function breaks after the first iteration due to extra data error which is caused due to the json.loads() function on which i am working to            rectify

***** -->  Currently, to fetch the data from github repo, run the substitute to fetch the verion from github repo manually by giving the repo url as input

ADDITIONAL FEATURES

--> A commented function is there in the script by the name "get_all_version()". which can returen the all the individual dependencies of the package.json file

--> A commented function by the name of "scrape_data()" is there, which can match the obtained dependencies from the official node-npm-package website using web scraping

--> It also has the feature of adding a issue to the repo, and using the issue id it can create a new pull request


LINK FOR GOOGLE COLLAB NOTEBOOKS

-->  https://colab.research.google.com/drive/19Z-T84cnt_Vg7_3FCSl2Hc2j_I3O9W-3?usp=sharing

-->  https://colab.research.google.com/drive/1L4gtho5Pd5SUs_zgpj5R6IO-vZs14jm5?usp=sharing

