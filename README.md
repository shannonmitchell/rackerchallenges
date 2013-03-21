rackerchallenges
================

# Challenge1 creates three webhead machines, waits for them to build and displays the information to the user.  No input required

example: ./challenge1


# Challenge2 does the following
#  - creates a server called challenge2_orig
#  - waits for it to build
#  - saves an image of it called challenge2_image
#  - waits for the image to save
#  - creates a clone called challenge2_clone from the image
#  - waits for the build then prints host information for all servers
# No input required.

example: ./challenge2




# Challenge3 accepts a directory and container argument and copies 
# the directory contents to cloud files
#
# ./challenge3 -h
# usage: challenge3 [-h] --directory DIRECTORY --container CONTAINER
#
# Work with cloud files and directories
#
# optional arguments:
#   -h, --help            show this help message and exit
#  --directory DIRECTORY
#                         directory to read from
#   --container CONTAINER
#                        cloud files container name

example: ./challenge3 --directory /etc --container test_container




# Challenge4 just takes a fqdn and ip address and creates the record 
#
# ./challenge4 -h
# usage: challenge3 [-h] --fqdn FQDN --ip IP
#
# Work with cloud files and directories
#
# optional arguments:
#   -h, --help   show this help message and exit
#   --fqdn FQDN  fully qualified domain name
#   --ip IP      ip address

example: ./challenge4 --fqdn test.linuxrackers.com --ip 10.10.10.33






# Challenge5 creates a dbinstance, db and db user from variable 
# information in some global variables.  No input required.

exampe: ./challenge5



