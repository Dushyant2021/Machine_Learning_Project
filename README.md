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

1. HEROKU_EMAIL = dushyant2031@gmail.com
2. HEROKU_API_KEY = 545286ff-4d6a-480f-ad12-ec54a764a305
3. HEROKU_API_NAME = ml-regression-app-2031