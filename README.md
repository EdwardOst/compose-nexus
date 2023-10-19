# compose-nexus
Docker Compose for Docker Hub nexus image.

[Official Docker Hub image for Nexus](https://hub.docker.com/r/sonatype/nexus3)

The default user is `admin` and the uniquely generated password can be found in the /nexus-data/admin.password

The first time you login it will prompt for New Password.

It will also prompt on whether to enable Anonymous Access.


### TODO

* Initialize password for admin user.
* Initialize anonymous access.
