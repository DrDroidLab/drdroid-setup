# drdroid-setup
This Repository holds Docker compose file for setting up Dr Droid on your own and boost your monitoring and debugging.

# How to use?
1. Clone this repository
2. `cd droid-setup`
3. `docker-compose --file=DrDroid.docker-compose.yml up -d`
4. Once the command finishes, check that the docker containers are up by running `docker ps`
5. Create a sample user by running the following: 
`docker exec -it backend_server /bin/sh /code/scripts/first_user_creation.sh`

Once the user is created, connect to the machine's port 80 using a browser and login using following credentials:
Username -> **user@drdroid.io**
Password -> **password**

Now, you can use the platform by ingesting events using the APIs and use all the features.
