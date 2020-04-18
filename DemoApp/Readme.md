
Set of instruction to build your first docker application and run

>>Create a git repository for your application

>>build Dockerfile

>>Go to docker teminal

>>Clone git repository
    >>git clone -b version_name repository_url

>>build application
    >>docker build -t app_name:version_name .

>>check for container id
    >>docker images

>>provide port no. Map the default port no that is used inside the container to the host.
    >>docker run -d -p mapping_port:default_port container_id

>>find the ip address of the server
    >>docker-machine ls

>>go to browser and type in the url section
    >>ip_address:port_address

>>the application will be running
