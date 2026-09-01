# Java-Internship-Tracker
## Overview
The Java Internship Tracker is a command-line application designed to help users organize and manage internship applications in one place. Users can record important information about each internship, including the company, position, location, application status, application date, job posting link, and personal notes.

The program allows internship information to be added, searched, edited, removed, saved, and loaded from text files. It also provides statistics that help users keep track of their application progress.

## Purpose
The purpose of this project is to provide a simple and organized way for students and internship applicants to keep track of multiple applications. When applying to many internships, it can become difficult to remember when an application was submitted, its current status, or other important details.

The Internship Tracker keeps this information together in one location and allows it to be saved for later use. This makes it easier for users to monitor their applications and update them as their internship search progresses.

## Features
  * Add and store internship applications.
  * Display all saved internships.
  * Search internships by company, state, status, or position.
  * Track application statuses.
  * Edit individual internship details.
  * Replace all information for an existing internship.
  * Load internship information from text files.
  * Create new internship tracker files.
  * Save changes to the current file.
  * Save internship information under a different file name.

## Character Limits
Before using the Internship Tracker, keep in mind that the saved text file uses fixed-width columns. Each field therefore has a maximum display length.
| Field           | Max Characters | 
| --------------- | -------------  | 
| Company         | 35             |
| Position        | 55             |
| City            | 25             |
| State           | 15             |
| Date Applied    | 12             |
| Link            | 70             |
| Notes           | 80             |

**Important:**  Make sure to follow these character limits when entering information. If you know that a company name, position, location, link, or note will be long, abbreviate it when possible so that the important information remains visible.

For example:

Instead of: Software Engineering and Technology Development Internship

you could enter: Software Engineering & Tech Development Intern

## Installation Guide
**Requirements**
Before downloading and running the Internship Tracker, first check whether Java is already installed on your computer.

Note: Throughout this guide, commands shown inside code blocks should be typed directly into the Terminal.

**Step-By-Step Process**

1. Check if Java Is Installed by opening the Terminal application on your computer. Type:
   ```
   java --version
   ```
&emsp; Press Enter

&emsp; If Java is installed, the Terminal should display information about the Java version installed on your 

&emsp; computer. Next, check that the Java compiler is also available by typing:

   ```
   java --version
   ```
&emsp; Press Enter.

&emsp; If both commands display version information, Java is installed and you can continue to step 3.

2. Install Java if needed.
If Terminal does not recognize the java or javac command, Java or the required Java Development Kit (JDK) may not be installed.
Follow the Java installation instructions provided here:

&emsp; https://www.cs.uakron.edu/~xiao/isp/JavaOnMacOS.html

&emsp; Follow the instructions on the linked page to install Java.

&emsp; Once you are finished, do not assume the installation worked. Check it again by closing and reopening

&emsp; Terminal, then repeating step 1

3. Download the Internship Tracker
The complete project is provided as a ZIP file in the main GitHub repository.
Download: Internship_Tracker.zip

&emsp; The file can be found here:

&emsp; https://github.com/cndekelengwe/Java-Internship-Tracker/blob/main/Internship_Tracker.zip

&emsp; Save the ZIP file somewhere that can be easily located, such as the Downloads or Desktop folder.

4. Extract the ZIP file. Double-click the ZIP file to extract its contents.
After extraction, open the resulting Internship_Tracker folder.
The Java source files needed to run the program should be located inside this folder.

5. Open the Project Folder in Terminal

&emsp; Open Terminal and navigate to the extracted Internship_Tracker folder using the cd command.

&emsp; For example, if the folder is on your Desktop:

   ```
   cd ~/Desktop/Internship_Tracker
   ```

&emsp; If the folder is in Downloads:

   ```
   cd ~/Downloads/Internship_Tracker
   ```

&emsp; You can check that you are in the correct folder by typing:

   ```
   ls
   ```

&emsp; The project files should appear in the Terminal.

6. Compile the Internship Tracker
Once you are inside the folder containing the Java source files, compile the program by typing:

   ```
   javac Internship.java InternshipTracker.java InternshipTrackerManagement.java
   ```

&emsp; Press Enter.

&emsp; If the command completes without displaying an error, the program compiled successfully.

7. Run the Internship Tracker
After the program has successfully compiled, type:

   ```
   java InternshipTrackerManagement
   ```

&emsp; Press Enter.

&emsp; The Internship Tracker should start and display its opening menu in the Terminal. If you see the Internship 

&emsp; Tracker menu, the setup was successful, and the program is ready to use.
