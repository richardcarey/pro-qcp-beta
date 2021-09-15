# Web App

This project is dependant on  https://git.capeannenterprises.com/carepoint/pdf-service/

INTRODUCTION
------------

This is the core project for CarePoint application.
Project consists of several components (CarePoint Administration, E- Commerce, CarePoint - Account Central, CarePoint Pro-QCP)

 * CarePoint - Administration:
   Provides functionality for CarePoint Admin user to have an overview and manage Locations/Orders/Products/Users
   This component is built in Drupal 8.9.3, please see: https://www.drupal.org/project/drupal/releases/8.9.3 for more information.

 * E- Commerce:
   This project uses drupal Commerce 2.x platform, please see: https://docs.drupalcommerce.org/commerce2/ for more information.

 * CarePoint - Account Central:
   Account Central component provides functionality for end-users to manage their accounts (General account and biling information, administration roles 
   have the limited ability to manage other user roles, locations and Pro-QCP modules)

   This component is built in:
    - Drupal 8.9.3, please see: https://www.drupal.org/project/drupal/releases/8.9.3 (drupal REST API)
    - Angular (Angular CLI: 9.1.11, Angular: 9.1.12) please see: https://angular.io/docs
    - MariaDB-10.4.21
    - PHP 7.3.12
    - Apache/2.4.25 (Debian)

 * CarePoint - Pro-QCP (IQCP):
   Main component for CarePoint application business logic.
   Provides implementation of IQCP workflow and set of rules for Risk assessment process and Quality Control Plan.
   Main output of the component is IQCP and Suggestion Report.
   
   This component is built in:
    - Drupal 8.9.3, please see: https://www.drupal.org/project/drupal/releases/8.9.3
    - Angular (Angular CLI: 9.1.11, Angular: 9.1.12) please see: https://angular.io/docs
    - MariaDB-10.4.21
    - PHP 7.3.12
    - Apache/2.4.25 (Debian)
    - mongoDB, please see: https://docs.mongodb.com/

   

INSTALLATION
------------

 * Run application locally: 
  - Navigate to root of the web-app, run command: 
    `docker-compose -f local-docker-compose.yml up`
  - Open your browser and navigate to `http://localhost:8888/`
  - For running the Angular application please see: client-angular-app/README.md


