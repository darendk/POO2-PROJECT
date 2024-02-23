# POO2-PROJECT
This is a PACMAN game written in JAVA.

Project Collaborators:
-# BALOOMOODY DAREN
-# BEEHARRY VIBAHAKARSINGH
-# YOGHESWAR SURJOO

Pacman-game in javaFx in collaboration with BALOOMOODY DAREN and YOGHESWAR SURJOO.
A readme is been made so as users can easily know how to execute the game.
Prerequisites.
This section indicates what are the requirements that should be poccessed in order to be able to start.

    esclipse workspace
    JavaFX SDK, Which should be downloaded from the website GluonHQ or from the link below directly.

 https :://gluonhq.com/products/javafx/ 

Set up.
The steps found below will helps to configure a project properly before starting the coding part.

    we first create a java project with the name Pacman
    Once the project is created we need to configure the build path, To do so follow the steps below.

Steps

 Right click on the project which has been created.
 Click on build path -> Configure build path -> Libraries -> Module path -> Add External JARS
 
 Once add External JARS is been click, a JARS selection page will pop up
 Select all the librabies found in the Folder lib.
   openjfx-21.0.2_windows-x64_bin-sdk -> javafx-sdk-21.0.2 -> lib
   
Once all libraries is been selected, click on apply and close, A new file name 
`Reference libraries` will be created in the project file which will contained all the
libraries which have been selected.

After the above steps has been successfully been done we may proceed with the remaining procedures.
Creation of a new package.

   Create a new package as desire:
   In this case pacman.
   
Upon successful creation it will appear in the SRC folder

Creation of a new class.

   Create 2 new class as follows:
       1. Pacman.java
       2. Model.java
Make sure that public static void main(string[]arg) is been selected during the creation.

Once the class is been created we will need to run the configurations.

click on run -> run configurations
The name project and main class should be selected in the main section.

And then we need to set the vm arguments which is found in the argument section.
--module-path "THE PATH OF THE LIB FOLDER WHICH IS FOUND IN THE JAVAFX_SDK WHICH HAS 
BEEN DOWNLOADED" --add-modules javafx.controls,javafx.fxml

EXAMPLE:
--module-path "C:\Users\toto\Downloads\openjfx-21.0.2_windows-x64_bin-sdk\javafx-sdk-21.0.2
\lib" --add-modules javafx.controls,javafx.fxml

Once done apply and run.

Problem that might arise during the execution of the above steps.

   During the run configurations, User might found that their app is not visible in the 
   section java application found in the toolbar. However in this case user will to create it 
   manually, do so to user just need to select their desire project and main class. In the 
   section name a desire name and this name will appear in the section run to run the game.

Creation of the game.

   Copy and paste the code found in the Sourcecode file and paste it in 
   the Pacman.java and Model.java file

   Once copy save and run the project.

How to play the game.

   To move the Pacman simply use the direction key. Each time a food is been eat the amount 
   of points will increased. If the ghost touches the pacman or vice versa the game is over.

New Game Version---Pacman V2.

   The concept of pacman V2 is the same as Pacman, Thus the only change is that Pacman V2
   has 5 different level. However to change level the user must complete the intial level
   first repecting the number of heart.
