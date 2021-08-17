Getting Started with Programming in Java


Objective -Create Fist Java App

Step 1:

open IntelliJ
create new project
select Java as project type
    *Project SDK and new allow you to select option version of your choosing
Go with default version choice -click no additional buttons
click Next
click Create Project from Template
    command line app is autoselected
click Next

set project name to: FirstApp
set project location to: default
set base package to: ' ' (leave blank)
click Finish
expand First App with carrot/arrow
expand src folder with carrot/arrow (this is where the code we are looking at is located)
    ***class contains sections of code
    ***Required format to run applications= 'public static void' 'main' and '(String[] args)'
type: System.out.println("First line from app");
      System.out.println("Second line from app");
      System.out.println("Third line from app");

click green arrow to build and run application

DONE
Java application was created build, and run successfully.

//INSERT CODE//
public class Main {

    public static void main(String[] args) {
	System.out.println("First line from app");
	System.out.println("Second line from app");
	System.out.println("Third line from app");
    }
}


-------------------------------------------------------------------------------------------------

Step 2 Running the command line 
in IDE at top click edit-- copy path/reference -- absolute path
/Users/moleon/IdeaProjects/FirstApp/src/Main.java
 in terminal cd ~
 cd IdeaProjects/FirstApp/out/production/FirstApp
 run: ls see Main.class
 run: java Main 
    and the application runs (do not run: java Main.class)
-------------------------------------------------------------------------------------------------

Step 3 Locating the Java command

to view envrionment variables go to terminal
run: printenv
PATH should contain path to where java execution file is located(if java command in step 2 ran then it is correct and this is just confirming or allowing you to make edits if necessary)

-------------------------------------------------------------------------------------------------
Step 4  Adding a base package

when creating a project
name: Organized 
enter in base package input: com.pluralsight.organized (example package value) 

When running application on command line with package name

always copy path of class copy within out folder
/Users/moleon/IdeaProjects/Organized/out/production/Organized/com/pluralsight/organized/Main.class

run:cd IdeaProjects/Organized/out/production/Organized
run: ls
com
run: java com.pluralsight.organized.Main
We got organized!

-------------------------------------------------------------------------------------------------
Objective - Variables, Data Types, and Math Operators

