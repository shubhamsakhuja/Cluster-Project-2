# Cluster-Project-2

@Shubham - Created the python file to create connection with couchdb server and extracted data from UNIMLEB Research Cloud in the file twitter.json. 
Location: Cluster-Project-2/Inputs/Unimelb Cloud Extract Code

@Shubham - Created the Instance using Ansible folder that has all the Ansible and Shell scripts
To run these - go to /etc/ansible and type ./run-nectar.sh
Provide OpenRC file password and sudo password to run all the scripts in 1 go.
Location: Cluster-Project-2/Instances using Ansible/

@Shubham - Extracted Aurin Data in .json and .CSV format, filtered out to proceed analysis on Melbourne Region only.
Location: Cluster-Project-2/Aurin Data/

@Shubham - Layout of Actual Front end + Final Report Generation(Parts).

@Vinshon - Created CouchDB Cluster and connected nodes to SHUBHAM-VM2 and SHUBHAM-VM3 (Manually, not via Ansible), currently working on MapReduce.

@Sindhusha - Removed Duplicate Tweets from twitter.json (provided initially) that has data as of perth, we processed the just to check if it's working(functionality) and helping with Front end development with Haritha.

@Harita - Extracted the data from Twitter using Twitter API and stored in CouchDB, Creating the front end using Flask - HTML/CSS/Python

@Pan - Filtered the data to remove duplicate tweets on the basis of Twitter ID's and analysis of the tweets with regards to offence using Python. He will be adding the twitter.json file data(extracted from Melbourne Research Cloud) and Aurin data that was extracted to couchDB as well. 

Pending ?? ==> Analysis/Indivisual-Report/Video of the Project/Slides.
