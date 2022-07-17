# Create a New Build Job in Jenkins Freestyle Project
### Step 1) Login to Jenkins
To create a Jenkins freestyle job, log on to your Jenkins dashboard by visiting your Jenkins installation path. Usually, it will be hosted on localhost at `http://localhost:8080` or `http://SERVER_IP:8080` If you have installed Jenkins in another path, use the appropriate URL to access your dashboard.

### Step 2) Create New Item

Click on “New Item” at the top left-hand side of your dashboard.

### Step 3) Enter Item details


- Enter the name of the item you want to create. We shall use the “Demo-first” for this demo.
- Select Freestyle project
- Click Okay

### Step 4) Enter Project details

Enter the details of the project you want to test.

### Step 5) Enter repository URL

- Under Source Code Management, Enter your repository URL. We have a test repository located at https://github.com/abobakar-it/firstJava.git
- It is also possible for you to use a local repository.

- If your GitHub repository is private, Jenkins will first validate your login credentials with GitHub and only then pull the source code from your GitHub repository.
 
 ### Step 6) Tweak the settings

- Now that you have provided all the details, it’s time to build the code. Tweak the settings under the build section to build the code at the time you want. You can even schedule the build to happen periodically, at set times.

Under build,

1. Click on “Add build step”

2. Click on “Execute Shell” and add the commands you want to execute during the build process.

Here, I have added the java commands to compile the java code.<br>

 I have added the following windows commands:

- javac HelloWorld.java

- java HelloWorld
 ### Step 7) Save the project

When you have entered all the data,

- Click Apply
- Save the project.

### Step 8) Build Source code

Now, in the main screen, Click the Build Now button on the left-hand side to build the source code.

### Step 9) Check the status

After clicking on Build now, you can see the status of the build you run under Build History.

### Step 10) See the console output

Click on the build number and then Click on console output to see the status of the build you run. It should show you a success message, provided you have followed the setup properly as shown in the below Jenkins create new job example.


<a href="https://www.guru99.com/create-builds-jenkins-freestyle-project.html">more detail</a>