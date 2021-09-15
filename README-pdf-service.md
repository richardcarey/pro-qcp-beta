# PDF Service

This project is dependant on  https://git.capeannenterprises.com/carepoint/web-app/

INTRODUCTION
------------

This project is used for generating CarePoint PDF reports.

 * CarePoint - PDF Service:
   Provides functionality for generating CarePoint PDF reports using the PHP html2pdf - 5.2.2 library

   This component is built in:
    - PHP 7.4
    - html2pdf - 5.2.2, please see: https://github.com/spipu/html2pdf.git
    - 

   Dependencies:
    - Drupal 8.9.3, please see: https://www.drupal.org/project/drupal/releases/8.9.3 (drupal REST API)
    - MariaDB-10.4.21

   

INSTALLATION
------------

 * Run application locally: 
  - Navigate to root of the pdf-service, run command: 
    `docker-compose up --build`
  - Open your browser and navigate to `http://localhost:8029/`


