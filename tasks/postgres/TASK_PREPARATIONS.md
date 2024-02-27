# Task Preparations

For the task 1 we will first prepare our environment in order to have one database up and running to the mentoring. 

To make our life easier we will use docker to start one container with latest postgres version.

So, for the first task it'll not be 100% related with DB, but it'll be related to create our DB:

1. Download and install any docker app:
   1. https://rancherdesktop.io/ -> I kind of recommend this one, but if you have mac with new arch processors it could have problems with it, so prefer colima.
   2. https://github.com/abiosoft/colima -> There is no visual interface like rancher, but work fine.
   3. https://www.docker.com/products/docker-desktop/ -> Please pay attention to the license if it'll require you to buy a license. IMHO I would avoid this option.
2. After install docker please go to `docker` folder and run the docker-compose file.
3. Try to connect to the Postgres database, you can use:
   1. https://www.pgadmin.org/ -> Quite famous for postgres
   2. https://dbeaver.io/ -> it'll work not only for postgres - my recommendation
   3. IntelliJ -> Onlyu if you are using it on your daily basis, if it's only for DB I would recommend other options
   4. Visual Studio
   5. Any other that are able to connect to postgres