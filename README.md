Submitted by -  MOHIT NAYAK
Reg.no - 19BCE1179
Vit Chennai CSE


IMPORTANT POINTS TO RUN THE dyte_main.py script

--> give the commmand as input to the dyte_main.py script

--> make sure that the input file is in the same directory as that of the dyte_main.py file

--> if update is not mentioned then the output file is "first.csv"

--> if update is mentioned then upgrade.csv is the output file containing the pr_request link also

--> The link added into the pr_link list is the link of the pull request made by self

--> All the github actions is done using the Github API, secret access token is also mentioned to verify the same

--> To fetch the version number from 'package.json', I have used github api to fetch the contents of the file

--> All the code is written in python, and the style of coding is procedural

-->  Above each snippets, brief description are mentioned as comments

ADDITIONAL FEATURES

--> A commented function is there in the script by the name "get_all_version()". which can returen the all the individual dependencies of the package.json file

--> A commented function by the name of "scrape_data()" is there, which can match the obtained dependencies from the official node-npm-package website using web scraping

--> It also has the feature of adding a issue to the repo, and using the issue id it can create a new pull request


LINK FOR GOOGLE COLLAB NOTEBOOKS

-->  https://colab.research.google.com/drive/1TRVHZ7C9eaN-tjwbpi0wYAxNLDCZnECm?usp=sharing


SAMPLE LINK FOR PULL REQUEST MADE (which gets stored in the upgrade.csv file)

-->  https://github.com/dyte-in/javascript-sample-app/pull/341

