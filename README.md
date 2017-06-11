# Rethinkdb 2.3.5 with Python Drivers
This is a docker I created to run on my Unraid server. Other images that I had tried did not have python intstalled which was making it difficult to export/import data. The goal was to be able to use the rethinkdb dump command etc. 

This docker is tested and working with the latest version of Unraid. If you would like to see some changes, please feel free to open a pull request.

## How to install on Unraid
Go to: `Settings > General Settings > Enable additional search results from dockerHub? Change to Yes`
Search: unraid-rethink-python

## Gain access to bash to run the dump and import commands
`docker exec -it unraid-rethink-python bash`
Then run the commands that you need. 

