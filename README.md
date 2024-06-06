# Contact Database Application Documentation

## Overview
The Contact Database Application is a web-based application that allows users to manage their contacts. It provides functionalities to add, edit, and delete contacts, as well as search for contacts based on various criteria.

## Architecture
The Contact Database Application follows a client-server architecture. The client-side is built using HTML, CSS, and JavaScript, while the server-side is implemented using ASP.NET Core. The application uses a SQL Server database to store contact information.

## Deployment using ARM Template
To deploy the Contact Database Application using an ARM template, follow these steps:

1. Create a new Azure Resource Group to host the application.
2. Create a new Azure SQL Database to store the contact information.
3. Create an ARM template file (`deploy.json`) and define the required resources, such as the Azure Web App, Azure SQL Database, and any other necessary resources.
4. Specify the parameters for the ARM template, such as the resource group name, database name, and connection string.
5. Use the Azure CLI or Azure PowerShell to deploy the ARM template to the Azure Resource Group.

## GitHub Actions Pipeline Workflow
To set up a GitHub Actions pipeline workflow for the Contact Database Application, follow these steps:

1. Create a new GitHub repository for the application.
2. Create a new workflow file (e.g., `.github/workflows/deploy.yml`) in the repository.
3. Define the workflow steps, such as checking out the repository, building the application, running tests, and deploying the application using the ARM template.
4. Specify the necessary environment variables, such as the Azure subscription ID, resource group name, and database connection string.
5. Commit and push the workflow file to the repository.

## Usage
Once the Contact Database Application is deployed and the GitHub Actions pipeline is set up, you can start using the application by accessing the web app URL. From there, you can perform various operations on your contacts, such as adding, editing, and deleting contacts, as well as searching for contacts based on different criteria.

## Contributing
If you would like to contribute to the Contact Database Application, please follow these guidelines:

1. Fork the repository and create a new branch for your changes.
2. Make your changes and ensure that the application is still functioning correctly.
3. Write tests for your changes to maintain code quality.
4. Submit a pull request with a detailed description of your changes.

## License
The Contact Database Application is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more information.
