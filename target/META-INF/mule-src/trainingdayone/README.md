# Mule-Training-Collateral-Day-One

Day 1
•	Create an AWS trial account (https://aws.amazon.com/free/start-your-free-trial/)
•	Load a provided sample contact JSON data file into s3 
•	Use a polling scope,  download the JSON file, in batch mode read each entry, perform validation (remove any contacts that are 3 months old.  Check that they are more than 18 years old) , write output file as xml. Record how many passed the filter.
•	Add a scheduler to execute the same job