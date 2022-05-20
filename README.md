# InterviewCodeChallenge_Angular

Pre-Requisites:
* .Net Core 3.1 installed.
* Visual Studio or VS Code installed.
* npm and nvm.


Steps to Create the project (using Visual Studio)
* Launch Visual Studio as an administrator.
* Choose "Create a new project"
*   ![image](https://user-images.githubusercontent.com/6515261/169511752-eebc5e4b-f8be-4b66-80cb-128c3ce3305a.png)
*   Search for Angular template, choose project type "ASP.NET Core with React.js" and click "Next"
*   ![image](https://user-images.githubusercontent.com/6515261/169524156-03731e5d-5582-4af4-9eb0-acf7eee8a9bf.png)
*   Enter the project name as "InterviewCodeChallenge_Angular" and click "Next"
*   ![image](https://user-images.githubusercontent.com/6515261/169524282-02fe4fbc-2986-43b2-9715-0a35b4696b07.png)
*   Choose Framework -> .Net Core 3.1 and click on "Create"
*   ![image](https://user-images.githubusercontent.com/6515261/169512215-31dfe20e-4c8c-4dd6-8d13-b6f6a07665a0.png)
*   Try building and running the template project.

Run the Project using Visual Studio:

Troubleshooting:
* Build Failure with "The command "npm install" exited with code 1."
  ![image](https://user-images.githubusercontent.com/6515261/169524618-511527ce-129c-4439-a38d-d3707806acc9.png)
  * Resolution:
  *  Open the .csproj file and update the npm install command to install with force
  ![image](https://user-images.githubusercontent.com/6515261/169524867-7557cd41-baeb-4063-ad38-09313582af25.png)
  * If the above step doesn't work, try undoing the change, launch command prompt as administrator and try "npm i"
  
* UI not loading up
* Open the folder ClientApp in terminal and install the below command
  * "npm install zone.js@0.11.3 --save"  


Run the project using VS Code.
* Open the project folder using VSCode.
* Using terminal in the project directory, enter the command "dotnet build"
