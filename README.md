# zahida-docker-assignment1-part2
### Step1: Using the image created in part1
### Step2: Run the docker container
```
docker run djangoapp
```
![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/9c642b26-65fe-4980-88d2-731e8d50158b)

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
![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/4aa0ddb0-8f11-44f8-a8b2-a5541c043cd3)

5. docker inspect ---- to inspect a container
   docker inspect 83aac4bdc6eed256021457ffce3bcd406295c5915fff45a2408b81082225b50f

6. 'docker exec' ---- to run a command inside container
   docker exec -d 83aac4bdc6eed256021457ffce3bcd406295c5915fff45a2408b81082225b50f touch execWorks 

7. docker attach
![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/3830733d-a2ad-46bf-8516-e9e459ef2961)

8. docker commit b8260f76b1f5112b9b547b0e9840b70cb078da25c580d25b3d40240752200011 --- to create a new image from a container

![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/d9e05ef7-616f-439e-927f-cd3094396290)

9. docker cp --- to copy a file to or from container or between containers and host
![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/63552452-4cce-45c3-a0bc-f1b425399761)

8. docker stats --- to view the resource usage of containers
   LOG:
![image](https://github.com/zahydakhan/zahida-docker-assignment1-part2/assets/45081511/656c7d71-5516-4aa8-8b73-465dd4761f57)

9. 
