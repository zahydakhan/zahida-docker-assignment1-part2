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
![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/9b2082a0-5172-40ef-bed0-c07ef14e1824)

8. docker stats --- to view the resource usage of containers
   LOG:
![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/b8f9409c-4430-4903-9989-7eeee43297a7)

9. docker top  ----- view the running processes inside a container
    ![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/4d18da62-61ec-4017-8ff1-d46666345b1f)

10. docker stop ----- to stop a running container
![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/e137aad6-667c-4a40-9256-7b7d4651eec9)
    
11. 'docker start' command to start a stopped container
![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/4238980b-2633-4a52-befd-05ec70eeeef0)

12.  'docker pause' command to pause a running container
![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/820c71cc-6c7c-4c32-b135-850389bfd921)
    
13. 'docker unpause' command to unpause a paused container
![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/0a8c6b4d-af32-4c70-9f08-6d7e23345489)

14. 'docker rename' command to rename a container
![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/f6213c55-06d0-4825-987a-e6daf18f9569)

15. 'docker port' command to display the public-facing port that a container is listening on
![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/58b9e9af-2579-4b24-934a-e9d135fe610b)

16. 'docker update' command to update a container's resource limits
![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/5c29096d-cd74-4514-8178-6b10c0284b11)

17. 'docker restart' command to restart a running container
![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/4a4bf34a-ff47-4c03-9df9-0279d0f27ff2)
