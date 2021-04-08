# HahnApplicationProcess
Source files for the Hahn Application process

Here is the process for you to successfully run the applications: -

1. Download/clone the repository to your local repository
2. Extract the contents of zipped file (Hahn.ApplicationProcess.Application.zip)
3. Navigate to folder Hahn.ApplicationProcess.February2021.Web, which contains the API.
4. Execute dotnet restore to restore all the nuget dependencies
5. Navigate to folder Hahn.ApplicationProcess.February2021.Web.UI, which contains the UI.
6. Execute npm install to install all the dependencies for your application
7. Go to the root folder of Hahn.ApplicationProcess.Application
8. Execute the following commands
9. docker-compose build
10. docker-compose up
11. These two commands will bring up the API on port 5001 and the UI on port 5006
12. Browse to your localhost:5006 to enjoy the asset Manager

Just in case you have challenges with Docker, you can directy go in the Hahn.ApplicationProcess.February2021.Web folder and open command prompt, execute "dotnet restore" to restore all the packages. Then execute "dotnet run" to run the application. It will bring up https://localhost:5001/swagger which gives a rich Swagger UI describing the API endpoints.

Navigate to folder Hahn.ApplicationProcess.February2021.Web.UI and open command prompt. Execute "npm install" to install all dependencies. After success installation, run "au run" or "npm start" to start the application on localhost:8080. Open your browser using this address and enjoy the application.

The application when loaded, shows a list of seeded assets from the API. It also has a New Asset menu for adding new assets to the database. 
