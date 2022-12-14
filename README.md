## Machine_Learning_Project
This is first machine learning project.

### Requirements:

1. [Github Account](https://github.com)
2. [Heroku Account](https://dashboard.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT CLI](https://git-scm.com/downloads)
5. [GIT Documentation](https://git-scm.com/docs/gittutorial)

Creating conda environment
```
conda create -p venv python==3.7 -y 
```
```
pip install -r requirements.txt
```

To add files to git 
```
git add .
```

OR
```
git add <file_name>
```

Note: to ignore file or folder from git we can write name of file/folder in .gitignore file

git status
```
To check the git status
```

To check all version maintained by git
```
git log
```


To create version/commit all changes by git
```
git commit -m "message"
```

To send changes/version to github
```
git push origin main
```

To check remote url
```
git remote -v
```

To setup CI/CD pipeline in heroku we need 3 information

1. HEROKU_EMAIL
2. HEROKU_API_KEY 
3. HEROKU_API_NAME


BUILD DOCKER IMAGE
```
docker build -t <image_name>:<tagname> .
```
>Note: Image name for docker must be lowercase



To list docker image
```
docker images
```

Run docker image
```
docker run -p 5000:5000 -e PORT=5000 <IMAGE ID> 
```


To check running container in docker
```
docker ps
```

To stop docker container
```
docker stop <container_id>
```

```
python setup.py install
```

