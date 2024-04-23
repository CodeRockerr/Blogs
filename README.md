# Blogs
## Cloud Computing IA2 -- Adit Shah (21BCP419)
## Running a three-tier-application using Docker

To run Three Tier Application using Docker, we need to first clone a Full Stack Project. We can use any of our Full Stack Project but if we don’t have one then we can use someone else project also. Here, I have used a very easy simple project on GitLab. The link to this project is https://gitlab.com/nanuchi/developing-with-docker. This project is made using HTML, CSS, JavaScript, Express and MongoDB.

1. First you need to clone the Project Repository from the link using command
git clone https://gitlab.com/nanuchi/developing-with-docker
![image](https://github.com/CodeRockerr/Blogs/assets/102573837/924c3e84-4736-42dc-9780-3d1be51512c6)

2. Then create a mongo network
![image](https://github.com/CodeRockerr/Blogs/assets/102573837/1a18f50d-248d-4e86-a6d8-97ea0cc5379c)

3. Pull mongo image
![image](https://github.com/CodeRockerr/Blogs/assets/102573837/5bcb0ac9-ca94-4b54-b14b-c33104f542d5)

4. pull mongo-express image
![image](https://github.com/CodeRockerr/Blogs/assets/102573837/46cd8f31-402d-460d-92fb-2a65ae271d55)

5. Run both the images using docker
![image](https://github.com/CodeRockerr/Blogs/assets/102573837/e115c9f2-5310-451a-94bc-ad9e2fe0fa61)
![image](https://github.com/CodeRockerr/Blogs/assets/102573837/3dccb032-11a9-45b2-b45b-bf3b71fe7781)

6. Open mongo-express in any browser, where you can create databases
![image](https://github.com/CodeRockerr/Blogs/assets/102573837/08195e95-5f9b-48f3-be5d-4a267ccf2234)
![image](https://github.com/CodeRockerr/Blogs/assets/102573837/7b1e3602-61fd-4084-8fa3-a891b211a520)

7. Create a Dockerfile and add below commands to the file
![image](https://github.com/CodeRockerr/Blogs/assets/102573837/0d92352a-c732-49fc-ab9f-8dfbe935920e)

8. Build a Docker image of the project
![image](https://github.com/CodeRockerr/Blogs/assets/102573837/599ef05a-cc02-4818-bd68-659707cb0d59)
![image](https://github.com/CodeRockerr/Blogs/assets/102573837/039e78ef-95a9-42d2-896e-b4feca157c58)

9. Run the created image of your project
![image](https://github.com/CodeRockerr/Blogs/assets/102573837/87ab0840-9664-449e-923d-ce98753d4a4e)

10. Open your project in any browser by searching _localhost:3000_ (There can be different ports)
Below is my simple project that I have deployed using Docker.
![image](https://github.com/CodeRockerr/Blogs/assets/102573837/64f56fd7-39fc-4794-8659-17711a251e83)

11. You can also see the change in MongoDB database when I make changes in the project.
![image](https://github.com/CodeRockerr/Blogs/assets/102573837/f8c60b05-d052-4506-939d-a4ab3e8a47cc)

So, this is how you can deploy yourr three-tier-application using Docker!!

## Uploading Image to DockerHub
12. Finally, we will upload our project image to DockerHub for better containerization.
For that, you need to log-in or create a new account on DockerHub if you don't have one.
![image](https://github.com/CodeRockerr/Blogs/assets/102573837/1c2c3203-9d7d-4ef1-9bb7-a897c47208cd)

To run a Three Tier Application, we need to run three Docker Containers simultaneously. So, it is necessary to run all these containers inside a network to avoid their interaction with other containers.

So, this is a step-by-step method to deploy your project using Docker.
Thank you for reading my Blog!!
