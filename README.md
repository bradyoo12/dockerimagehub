# Relevant tools, techniques and frameworks
- Git
- Github
- Docker
- Unit test using pytest
- Flask
- Conda

# What I learned
- How to automate workflow of CI/CD for Dockerized app
- How to write yaml file in Github to automate docker file building and unit testing
  
# Steps
- Make a change in code on VS Code
- Commit the change in terminal : git add .; git commit -m "first commit";
- Push the commit to main branch: git push -u origin main
- Observe Actions tab on the branch e.g. bradyoo12/dockerimagehub
- Check the built docker file on docker hub. e.g. https://hub.docker.com/r/bradyoo12/flasktest-app
- Pull and Run the docker file: docker pull bradyoo12/flasktest-app; docker run -p 5000:5000 bradyoo12/flasktest-app:latest
- See the site running on your desktop. e.g. http://127.0.0.1:5000/

# Reference
- MLOPS Tutorial- Automating Workflow Of CI/CD for Dockerized Flask App Using Github Action [https://www.youtube.com/watch?v=qxpKCBV60U4](https://www.youtube.com/watch?v=9oALxmc5yEw)
