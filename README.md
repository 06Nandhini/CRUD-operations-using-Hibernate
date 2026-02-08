# CRUD Operations Using Hibernate

Perform CRUD operations on relational databases **without writing SQL queries**, using Hibernate.  
This project is **purely for learning purposes**.

Let’s start from the very scratch.

---

## Prerequisites

- Java JDK 17 or above (JDK 21 recommended)
- Maven
- MySQL
- Visual Studio Code (or any IDE)

---

## Step 1: JDK Installation

- Install **Visual Studio Code**
- Install **JDK 21** (any version from JDK 17 is valid)

**Important Note:**  
If you have already installed an older version of Java (since you might have started learning Java earlier),  
after installing the new JDK, make sure the **environment path variable** is set correctly.

---

## Step 2: Verify Installation

- Open the **Command Prompt**
- Make sure JDK is installed correctly:

```bash
javac --version
```
Expected result:
java 21.x.x

## Step 3: Install Maven
Download Maven from: https://maven.apache.org/

Download the Binary file, not the source file
(we are using Maven, not building it)

Set the environment variable MAVEN_HOME

Add the bin folder to the PATH

Verify installation (close and reopen command prompt):
```bash
mvn --version
```
## Step 4: Create a Project Folder
Run the following command:
If your are wrting the command in single line dont use '\'
```bash
mvn archetype:generate \
-DgroupId=com.example \
-DartifactId=HibernateDemo \
-DarchetypeArtifactId=maven-archetype-quickstart \
-DinteractiveMode=false
```
Result:

BUILD SUCCESS
## Step 5: Execution Order
Run the files in the following order:

- Open VS Code after completing the above steps

- Configure pom.xml

- Configure hibernate.cfg.xml

- Run Main.java and Employee_Details

- Perform CRUD operations as per your requirement

```bash
Note
While performing the Create operation, if you are rerunning the program multiple times,
make sure to use a different primary key to avoid conflicts.
```
