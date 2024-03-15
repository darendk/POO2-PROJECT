# POO2-PROJECT
This is a PACMAN game written in JAVA.

Project Collaborators:
-# BALOOMOODY DAREN
-# BEEHARRY VIBAHAKARSINGH
-# YOGHESWAR SURJOO

Pacman Game in JavaFX

This Pacman game was developed in collaboration with BALOOMOODY DAREN,BEEHARRY VIBAHAKARSINGH  and YOGHESWAR SURJOO.
Prerequisites

# Prerequisites

Before starting, ensure you have the following prerequisites:

- Eclipse workspace
- JavaFX SDK, which can be downloaded from the website GluonHQ or from the following link:
  [JavaFX SDK](https://gluonhq.com/products/javafx/)

# Set up

Follow these steps to configure the project properly before starting the coding part:

1. Create a Java project named Pacman.
2. Configure the build path:
    - Right-click on the project.
    - Click on `Build Path` -> `Configure Build Path` -> `Libraries` -> `Module Path` -> `Add External JARS`.
    - Select all the libraries found in the Folder lib:
      `openjfx-21.0.2_windows-x64_bin-sdk -> javafx-sdk-21.0.2 -> lib`.
    - Click `Apply and Close`. This will create a new file named `Reference libraries` in the project containing all the selected libraries.

# Creation of a new package

Create a new package as desired (e.g., `pacman`). Upon successful creation, it will appear in the `SRC` folder.

# Creation of a new class

Create 2 new classes as follows:
1. Pacman.java
2. Model.java
Ensure that `public static void main(String[] args)` is selected during creation.

# Run Configurations

1. Click on `Run` -> `Run Configurations`.
2. Ensure the project name and main class are selected in the main section.
3. Set the VM arguments found in the argument section:
   `--module-path "THE PATH OF THE LIB FOLDER WHICH IS FOUND IN THE JAVAFX_SDK WHICH HAS BEEN DOWNLOADED" --add-modules javafx.controls,javafx.fxml`
   Example:
   `--module-path "C:\Users\toto\Downloads\openjfx-21.0.2_windows-x64_bin-sdk\javafx-sdk-21.0.2\lib" --add-modules javafx.controls,javafx.fxml`
4. Click `Apply` and then `Run`.

# Potential Problems

If the app is not visible in the `Java Application` section during run configurations, create it manually by selecting the desired project and main class. Then, name it accordingly.

# Creation of the Game

Copy and paste the code found in the Sourcecode file and paste it in the `Pacman.java` and `Model.java` files. Once done, save and run the project.

# How to Play the Game

To move the Pacman, simply use the directional keys. Each time a food is eaten, the points increase. If the ghost touches the Pacman or vice versa, the game is over.

# New Game Version - Pacman V2

Pacman V2 has the same concept as Pacman but with 5 different levels. To advance to the next level, the user must complete the initial level while respecting the number of lives.
