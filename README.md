# Data Abstraction Assignment
> This is a school assignment with JUnit tests for a Customer banking system. The Customer can deposit and withdraw money into the system. There is a Customer class, as well as a Deposit class and a Withdraw class.
<br>
Course: Computer Programming 11

<br>

## Table of Contents
- [Technologies](#technologies)
- [How to run the project](#how-to-run-project)
- [References](#references)

<br>

## Technologies
* Java
* Testing: JUnit


<br>


## <a id="how-to-run-project">How to run the project</a>
### Prerequisites:
- Have a Git and GitHub account
- Have [Java JDK](https://adoptopenjdk.net/archive.html) installed 
  - This project uses jdk-11

### Configuration instructions:

You will need to install:
- [IntelliJ](https://www.jetbrains.com/idea/download/#section=windows) (executable)
  - This project uses the community version, which is free

Cloning the repository:
- Open Command Prompt
- `cd` into the folder you want the repository stored in
- Type: `git clone https://github.com/MonB003/DataAbstractionAssignment.git`

Configuring the SDK:
- In IntelliJ:
  - File > Project Structure > Project Settings > Project
    - Use SDK: 11 (2) version 11.0.16
    - Language level: 18 - No new language features
  - File > Project Structure > Project Settings > Modules
    - Use SDK: 11 (2) (version 11.0.16)

### Running the JUnit tests:
1. In IntelliJ, open the test class file you want to run (ex. CustomerTests.java)
   - The test files are in the TestCases folder
2. In the top navbar, click *Add Configuration...*
   - For the configuration, select *JUnit*
   - Give the configuration a name (ex. CustomerTests tests)
   - For the *Build and run* section:
    - Use java 11 SDK
    - For the class, select the test class file you want to run (either type in the class name or browse for the file)
   - Once the configuration information is filled out, click *Ok*
3. Click the green triangle in the top right corner (when hovered on, it says: Run 'CustomerTests tests')
4. A small popup window will appear with the results of the tests

<br>

## <a id="references">References</a>
- [School lecture video](https://www.youtube.com/watch?v=gIuEeYy-2rs)
