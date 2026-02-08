# CRUD-operations-using-Hibernate
Perform CRUD operation on Relation without writing query only by using the Hibernate. Its purely for learning purpose!

Let's start from the very scratch to do this

Step 1:
  -Install Visual Studio Code
  -Install JDK 21(Any version from JDK 17 is valid) 
  **Important Note:
    If you have already installed older version of java(since you might start learning JAVA earlier, after installing the JDK make sure Environment path variable is setted correctly)
    **
Step 2:
  -Open the Command prompt
  Making sure:
    i) JDK installed correctly
          javac --version //result : java 21.x.x
Step 3:
    Install maven - https://maven.apache.org/
    Download Binary file not source file because here we are not going to build the maven just using maven
    Set environment system variable as %MAVEN_HOME% and path location include bin folder.
    Checking maven is installed correctly(close and reopen the command prompt)
        mvn -version
Step 4:
    Now Create a project folder
    Type command as:
      mvn archetype:generate -DgroupId=com.example -DartifactId=HibernateDemo -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode = false
    Result : BUILD SUCCESS
Step 5:
  Run the file in the order as
      i) load the VSCode by performing above 4 steps
      ii) po.xml
      iii)hibernate.cfg.xml
      iv) Main.java and Employee_Details
      v) perform CRUD operation according to your wish
Note:
  while perform Create operation, if you are rerunning the program again and again, make sure to use different primary key.
