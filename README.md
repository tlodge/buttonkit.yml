#getting started

this docker file will pull in all images needed to run buttonkit.  Note that it mounts volumes on the host directory (by default /opt, set in .env). 

 OSX restricts the directories that your are able to mount to, and will fail if you do not explicitly set a legal directory.  To do this do:

   export HOSTMOUNT=~/dockermnt

and then when up and running you should see volumes created there

To get started just run

   docker-compose up -d


