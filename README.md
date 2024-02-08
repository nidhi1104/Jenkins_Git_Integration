Simple code to just check Jenkins-Git integration.
Steps to integrate jenkins to git: 
1. Install necessary plugins , ie . git integration plugin by clicking on Manage Plugin-> Available Plugin
2. Make a new freestyle project.
3. Go to configure->source code management. Select git and then give <YOUR_REPO_URL>
4. Go to Build Triggers, select POLL SCM and type five star with spaces within it, this will check for every minutes changes within the Git.
5. Go to Built Steps, write python3 jenkins_git_integration.py , ie <COMMAND_TO_RUN> <YOUR_FILE_NAME>
6. Click on Save.
7. Click on Build Now and you can see output on console output.
YAY! WE SUCESSFULLY INTEGRATE THE GIT REPO with JENKINS.
