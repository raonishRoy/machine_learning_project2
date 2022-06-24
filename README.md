# machine_learning_project2
this is my first machine learning project
## Start Machine Learning project.

### Software and account Requirement.

1. [Github Account](https://github.com)
2. [Heroku Account](https://dashboard.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT cli](https://git-scm.com/downloads)
5. [GIT Documentation](https://git-scm.com/docs/gittutorial)

To activate virtual environment

'''
 conda create -p python=3.7 -y
  conda activate venv/
'''

To add file to git (all)
'''
  git add .
'''
or 
'''
 git add <file_name>
'''
note:-To ignore file or folder from git we can name of file or folder in .gitignore file
To check all version maintained by git
'''
 git commit -m "message"
'''
To send version /changes to github
'''
 git push origin main
'''
To check remote url
'''
 git remote -v
'''

To setup CI/CD pipeline in heroku we need 3 information

1. HEROKU_EMAIL = raonish001@gmail.com
2. HEROKU_API_KEY =2efc3bec-d480-42da-8236-86dddada3612
3. HEROKU_APP_NAME = ml-regression-app001



BUILD DOCKER IMAGE
'''
docker build -t <image_name>:<tagname> .
'''