# Creating DevHub Content

This the master repository for the DevHub repo. Content is written using reStructured Text but uses a number of proprietary extensions and the site as a whole is built using the Snooty tool chain. As a result the input files are expected to have a **.txt** extension. Files with a different extension will not be processed. 

## Quick Start
- fork this repo: https://github.com/mongodb/devhub-content
- in the settings you need to setup a webhook to trigger the build for each new branch you push in your repo. 
- You need to ask the devhub team to add your github user in the list & they will add you in the Slack alerts system (you get notificiations when your build is running & done).
- When you are happy with your branch, you can PR to the master branch of the upstream repo (the one above)
- make sure your rebase your branch on the latest version of upstream/master before your PR to ease the merge process and avoid conflict as much as possible.
- Run [`sanity-check.py`](https://github.com/mongodb/devhub-content/tree/master/sanity-check), watch the results and act on them
