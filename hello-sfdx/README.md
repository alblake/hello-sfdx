# hello-sfdx

## Overview
The hello-sfdx project is a Salesforce DX project designed to facilitate the development and deployment of Salesforce applications. This project structure includes directories for Apex classes, custom objects, triggers, layouts, and scripts for SOQL queries.

## Project Structure
- **force-app/main/default/classes**: Contains Apex classes for business logic.
- **force-app/main/default/objects**: Holds custom objects and their definitions.
- **force-app/main/default/triggers**: Includes Apex triggers for record events.
- **force-app/main/default/layouts**: Defines page layouts for Salesforce record pages.
- **scripts/soql/queryAccounts.soql**: Contains a SOQL query for retrieving Account records.
- **sfdx-project.json**: Configuration file for the Salesforce DX project.

## Setup and Usage
1. Clone the repository to your local machine.
2. Install Salesforce CLI if not already installed.
3. Authenticate to your Salesforce org using the command:
   ```
   sfdx auth:web:login -a YourAlias
   ```
4. Push the source to your Salesforce org:
   ```
   sfdx force:source:push
   ```
5. Run the SOQL query in `scripts/soql/queryAccounts.soql` to retrieve Account data.

## Contributing
Feel free to contribute to this project by submitting issues or pull requests.