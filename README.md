# Mule-Training-Collateral-Day-One


## Authors:
Minton, Tom <tom.minton@capgemini.com>   
Suchindrum, Anand <anand.suchindrum@capgemini.com> 

## Overview

- Create an AWS trial account (https://aws.amazon.com/free/start-your-free-trial/)
-	Load a provided sample contact JSON data file into s3 
-	Use a polling scope,  download the JSON file, in batch mode read each entry, perform validation (remove any contacts that are 3 months old.  Check that they are more than 18 years old) , write output file as xml. Record how many passed the filter.
-	Add a scheduler to execute the same job

## Training Steps
### Download a copy and import to Anypoint Studio

SSH | HTTP

`git clone git@github.com:loganmancuso-capgemini/Mule-Training-Collateral-Day-One.git`

`git clone https://github.com/loganmancuso-capgemini/Mule-Training-Collateral-Day-One.git`

- launch AnypointStudio, right click on file explorer and click import
- Anypoint Studio > Anypoint Studio project from file system > paste directory for new cloned project

### Run project
after the project is imported the Anypoint Studio should begin loading in dependencies and packages. Then click the green run button in the top toolbar and click run as Mule Application.