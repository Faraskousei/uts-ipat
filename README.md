
Please check the official laravel installation guide for server requirements before you start. [Official Documentation](https://laravel.com/docs/)

Clone the repository

    git clone https://github.com/firstioanmar/uts-ipat.git
    
Install all the dependencies using composer

    composer install
 
Copy the example env file and make the required configuration changes in the .env file

    copy .env.example to .env

Generate a new application key

    php artisan key:generate
     
Start the local development server

    php artisan serve
 
Access the project
[http://localhost:8080](http://localhost:8080)
