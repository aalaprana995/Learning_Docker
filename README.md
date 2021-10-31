# Learning_Docker
This is a repository that has some starting points to help with docker.
## Basic Concept
- Docker is a way to package applications with all the required dependencies and configurations to run the application.
- Docker containers are portable, thus can be shared easily between developers and operational team making the development process fast.
- Containers live in container repositories and docker repositories can be public or private.
## Development Process Before-vs-After

### Before
- For developing an application, each developer has a local system on which he installs the required dependencies and configuration to run and develop features.
- Thus, each developer has a different installation process as they use different OS.
- This creates a room for lot of errors as each OS needs different commands and steps to be followed. It also  makes the process tedious for the developer.
- Developer and operational teams need to have good communication, or else any misundersatnding can lead to -----------. 
### After
- With container we donot have to directly install any application on local OS, because container is itself its own seperate environment.
- Fetching and running docker container is easy and we have to run the same command independent of the OS.
- We can have different version of the same application running without any problem on our system.
- No environmnet configuration needed on server.
- It improves and makes devops process faster and easy as developers and operational team works together.
### Difference between Docker Image and Docker Container
![Screenshot from 2021-10-31 11-53-21](https://user-images.githubusercontent.com/93336207/139593189-eeb2ed3a-02ce-4d78-8daa-21808ec024b7.png)
### Difference between Docker and Virtual Machine
![Screenshot from 2021-10-31 12-34-16](https://user-images.githubusercontent.com/93336207/139593567-ca6c3d03-d9f3-4ce0-b660-f5f8cc05cdd1.png)
**Advantages of Docker over VM**
- Docker image is smaller 
- Docker starts and runs faster.

**Disadvantage of Docker over VM**
- VM of any OS can run on any OS on local system, but this is not the case with docker,
![Screenshot from 2021-10-31 12-36-10](https://user-images.githubusercontent.com/93336207/139593726-af2f8cbc-ed1d-4963-b7c6-d30600e08d5e.png)

### My First Command
> docker run docker-image

This command internally does three things 
1) Fetch
2) Download 
3) Run

- We can run two different images with different versions with docker.
![Screenshot from 2021-10-31 11-55-58](https://user-images.githubusercontent.com/93336207/139592898-fdfb7115-29ee-48b2-b799-f24c0cc62a8c.png)
- When we update a version of image, only the layers that are different gets updated.
![Screenshot from 2021-10-31 11-54-56](https://user-images.githubusercontent.com/93336207/139592872-6b137cd6-2c85-4311-8b83-39ddd3000123.png)




