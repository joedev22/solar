Concept of project: 


The project accepts data for registered panels only, and to register a panel, a serial number along with latitude and longitude is required. 

The serial number must be exactly 16 characters in length 
(for ex. AAAA1111BBBB2222); latitude and longitude should contain 6 decimal places and must have valid values within latitude range (-90 to 90) and longitude range 
(-180 to 180) respectively.

Setup instructions:

    - Add your local database password to the .env file.

    - Create your database using your prefered MySQL client

    - In the Terminal / Command Line, navigate to this directory (The directory containing Readme.txt) and run the following commands:
        * composer install
        * php artisan migrate
        * php artisan serve

PS: My environnment dev was installed with vagrant 
