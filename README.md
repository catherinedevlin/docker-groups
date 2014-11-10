docker-groups
=============

Sets of single-service Dockerfiles designed to interoperate

Most practical uses of Docker require more than one service.  For example, a production
webservice may imply a WSGI servince, an nginx service, and a PostgreSQL service.  Orthodox
Docker calls for one service per container, which suggests three Docker containers interacting
with each other.

To shortcut the complexity involved in setting up such multi-container architectures, I'm 
creating sets of Dockerfiles and shell scripts that already "know" how to interact with
each other.

Disclaimer: I am the worst DevOps person ever.  Patches from the competent are welcomed.
