# Install Jenkins
<a href="https://github.com/ABOBAKAR-IT/Learn-Jenkins/tree/master/Install%20Jenkins">#Install Jenkins</a>

# Create First Job
<a href="https://github.com/ABOBAKAR-IT/Learn-Jenkins/tree/master/Create%20first%20job">#Create First Job</a>

# Install First Plugin
<a href="https://www.javatpoint.com/jenkins-managing-plugins">#Install First Plugin</a>

# Create First user
<a href="https://www.guru99.com/create-users-manage-permissions.html">#Create First user</a>

# Jenkins Role Base Access
<a href="https://www.guru99.com/create-users-manage-permissions.html">#Jenkins Role Base Access</a>

# use to Git Plugin
<a href="https://www.guru99.com/jenkins-github-integration.html">#use to Git Plugin</a>

# Clean Work Place
<a href="https://computingforgeeks.com/automatically-clean-up-jenkins-workspace-after-builds-complete/">#Clean Work Place</a>

# Trigger Build Remotely
<a href="">#Trigger Build Remotely</a>
first Install `Build Authorization Token Root Plugin` 
<img src="./image/build_auth">
create now job
<img src="./image/create_job">
build trigger
- click Trigger builds remotely (e.g., from scripts)
- create token
<img src="./image/build_trigger">

### use this link in web browser for job trigger
```
http://20.216.13.253:8083/buildByToken/build?job=WRITE_JOB_NAME&token=WRITE_TOKEN_NAME
```
### use this link in Shell  for job trigger
```
curl http://20.216.13.253:8083/buildByToken/build?job=WRITE_JOB_NAME\&token=WRITE_TOKEN_NAME
```