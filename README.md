# zahida-docker-assignment1-part2
### Step1: Using the image created in part1
### Step2: Run the docker container
```
docker run djangoapp
```

![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/8bdcb590-bd65-44aa-9d4a-249da40e928f)


### Step3: Use Different Docker Container Commands
1. docker ps                 ---- to show all the active containers
LOG:
CONTAINER ID   IMAGE                COMMAND                  CREATED         STATUS         PORTS     NAMES
ff2c428413f7   python-djangopart2   "python3 manage.py r…"   6 minutes ago   Up 6 minutes             eager_fermi

2. docker stop ff2c428413f7         --- to stop a running container
   LOG:
   ff2c428413f7

3. docker rm                   --- to remove a stopped container
   docker rm ff2c428413f7
   LOG:
   ff2c428413f7
4. docker logs
![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/e525a4c0-64f5-44f9-9028-0e4f6d78ed20)


6. docker inspect ---- to inspect a container
   docker inspect 83aac4bdc6eed256021457ffce3bcd406295c5915fff45a2408b81082225b50f

7. 'docker exec' ---- to run a command inside container
   docker exec -d 83aac4bdc6eed256021457ffce3bcd406295c5915fff45a2408b81082225b50f touch execWorks
   ![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/e04cb60c-33cb-4873-8285-5b7fb46148ea)


9. docker attach
![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/160354fe-394b-42da-a9a2-804151f09f61)


10. docker commit b8260f76b1f5112b9b547b0e9840b70cb078da25c580d25b3d40240752200011 --- to create a new image from a container
![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/c8c01b50-7af8-4b46-95e3-f9578c2055e4)


9. docker cp --- to copy a file to or from container or between containers and host
![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/63552452-4cce-45c3-a0bc-f1b425399761)

8. docker stats --- to view the resource usage of containers
   LOG:
![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/656c7d71-5516-4aa8-8b73-465dd4761f57)

9. 
