rackerchallenges
================

```

# Challenge1 creates three webhead machines, waits for them to 
# build and displays the information to the user.  No input 
# required

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

example: ./challenge5




# Challenge6 creates a container called challenge6, enables cdn and
# prints the results.  No input required.

example: ./challenge6





# Challenge7 creates 2 webhead nodes and sets up a load balancer on port 80 for
# both.

example: ./challenge7




# Challenge8 creates a cdn enabled container and uploads an index.html object
# to it.  It also sets the metadata for an index file and creates a cname
# in dns for it.  The challenge doesn't give a domain name to use, so we need
# user input for it.
#
# ./challenge8 -h
# usage: challenge8 [-h] --fqdn FQDN
#
# Create a pre-defined index.html file in a public cdn and cname a 
# user provided fqdn to it.
# 
# optional arguments:
#   -h, --help   show this help message and exit
#   --fqdn FQDN  fully qualified domain name

example: ./challenge8 --fqdn challenge8.linuxrackers.com



# Challenge 9 creates a server with a dns entry based on a given fqdn, image id
# or name and flavor id or name.  
#
# ./challenge9 -h
#
# usage: challenge9 [-h] --fqdn FQDN --image IMAGE --flavor FLAVOR
#
# Create a server based on fqdn, flavor id or name and image id or name.
#
# optional arguments:
#   -h, --help       show this help message and exit
#   --fqdn FQDN      fully qualified domain name
#   --image IMAGE    image id or name
#   --flavor FLAVOR  flavor id or name

example:  ./challenge9 --fqdn test.linuxrackers.com --flavor 2 --image 03318d19-b6e6-4092-9b5c-4758ee0ada60

or 

example: ./challenge9 --fqdn test.linuxrackers.com --flavor "512MB Standard Instance" --image "CentOS 5.6"


```

