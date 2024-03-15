# POO2-PROJECT
This is a PACMAN game written in JAVA.

Project Collaborators:
-# BALOOMOODY DAREN
-# BEEHARRY VIBAHAKARSINGH
-# YOGHESWAR SURJOO

Pacman Game in JavaFX

This Pacman game was developed in collaboration with BALOOMOODY DAREN,BEEHARRY VIBAHAKARSINGH  and YOGHESWAR SURJOO.
Prerequisites

Before running the game, ensure you have the following prerequisites:

    Eclipse workspace
    JavaFX SDK, which can be downloaded from the GluonHQ website

Setup

Follow these steps to configure the project before starting:

    Create a Java project named "Pacman."
    Configure the build path by:
        Right-clicking on the project.
        Selecting Build Path -> Configure Build Path.
        Under Libraries -> Module Path, click Add External JARS.
    Select all the libraries from the following path:
    openjfx-21.0.2_windows-x64_bin-sdk -> javafx-sdk-21.0.2 -> lib.
    Click Apply and Close.

After completing the above steps, proceed with the following:
Creation of Packages

Create a new package named "pacman" within the src folder.
Creation of Classes

Create the following two classes:

    Pacman.java
    Model.java

Ensure to select public static void main(String[] args) during class creation.
Run Configurations

    Click Run -> Run Configurations.

    Ensure the project name and main class are selected in the main section.

    Set the VM arguments under the argument section:

    arduino

--module-path "PATH_TO_LIB_FOLDER_IN_JAVAFX_SDK" --add-modules javafx.controls,javafx.fxml

Example:

arduino

    --module-path "C:\Users\toto\Downloads\openjfx-21.0.2_windows-x64_bin-sdk\javafx-sdk-21.0.2\lib" --add-modules javafx.controls,javafx.fxml

    Click Apply and Run.

Possible Issues

If the app is not visible in the Java Application section during run configurations, manually create it by selecting the project and main class. Provide a desired name, which will appear in the run section to execute the game.
Playing the Game

    Use the directional keys to move Pacman.
    Each time Pacman eats food, the points increase.
    If Pacman collides with a ghost or vice versa, the game ends.

New Game Version - Pacman V2

Pacman V2 retains the same concept as Pacman but introduces 5 different levels. To advance to a new level, the user must complete the initial level while respecting the number of hearts.
