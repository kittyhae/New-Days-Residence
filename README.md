# New-Days-Residence

<div align="center">
  <img src="https://github.com/kittyhae/New-Days-Residence/assets/134063953/8f32fabb-8211-43b6-aecb-f00c5027a261" alt="LOADING_PAGE">
</div>
<br>
New Days Residence, the Rental Estate Tracker, empowers users with a suite of essential features. These include the ability to effortlessly add or remove apartments, facilitate property leases, manage property vacancies, and oversee transactions, providing a streamlined solution for effective and user-friendly rental property management.

## How to use

1. **Download the files in this repository.**
   
2. **Install JAR Files:**
   - Ensure all required JAR files are available for the New Days Residence application.
   - Copy the necessary JAR files into the project directory.

3. **Configure Build Path:**
   - If using an IDE like Eclipse or IntelliJ, configure the build path to include the JAR files.
     - For Eclipse:
       1. Right-click on the project.
       2. Select "Build Path" and choose "Configure Build Path."
       3. Under the "Libraries" tab, click "Add JARs" or "Add External JARs" to include the necessary JAR files.
     - For IntelliJ:
       1. Go to "File" > "Project Structure."
       2. Navigate to the "Modules" section.
       3. Under the "Dependencies" tab, click the "+" button to add JAR files to the project.
   - For Visual Studio Code (VS Code):
     1. Inside your project folder, create a new folder named "lib."
     2. Copy the required JAR files into the "lib" folder.
     3. Create a `.vscode` folder in the root of your project (if not already present).
     4. Inside the `.vscode` folder, create a `settings.json` file.
     5. Add the following configuration to include the JAR files:
        ```json
        {
            "java.project.referencedLibraries": [
              "lib/**/*.jar",
              "jackson-annotations-2.16.1.jar",
              "jackson-core-2.16.1.jar",
              "jackson-databind-2.16.1.jar",
              "TimingFramework-0.55.jar"
            ]
        }
        ```
     6. Save the changes to the `settings.json` file.
     7. Reload your VS Code window.

4. **To run the program, go to "NDRESIDENCES" > "APP" > `NewDaysResidences.java`**
