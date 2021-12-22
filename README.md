## "Tasks" Test Project

# How To Deploy it Locally

1. add to the **/etc/hosts** ```127.0.0.1 upt.local www.upt.local```
2. run in the terminal ```sudo chown -R $USER:$USER ./```
3. run in the terminal ```docker-compose up -d```
4. wait until containers running
5. run in the terminal ```docker exec -it upt-app bash```
6. run in the terminal (into the container) ```php artisan migrate```
7. open browser and visit the [page](http://upt.local/task/create)
8. [here](http://upt.local:8081) you can find Adminer
