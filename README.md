# Laravel_VueJS_Blog_favorites
Laravel+VueJS blog application with ability to favorite posts and see all favorites

###### This Laravel & Vue JS application is an simple example with following functionality:

> - Example of Posts page with "Add to Favorites" finctionality
> - Example of simple integration of Vue JS components into Laravel application
> - Example of Laravel pagination and Favorites page


#### Installation

1. Install this code on your local system
     
    1. Fork this repository (click 'Fork' button in top right corner)
    2. Clone the forked repository on your local file system
    
        ```
        cd /path/to/install/location
        
        git clone https://github.com/Maksim1990/Laravel_VueJS_Blog_favorites.git
        ```

2. Change directory into the local clone of the repository

    ```
    cd Laravel_VueJS_Blog_favorites
    ```
3. Install [NPM](https://getcomposer.org) & [Composer](https://getcomposer.org) dependencies

    ```
    npm install
    
    composer install
    ```

4. Create a `.env` file by copying the sample

    ```
    cp .env.example .env
    ```
    
    Or for Windows:
    
    ```
    copy .env.example .env
    ```
 3. Set database connection by changing (if necessary) below credentials in `.env` file: 
     ```
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=homestead
    DB_USERNAME=homestead
    DB_PASSWORD=secret
    ```
    
  5. Compile all Sass and JS assets
      ```
      npm run dev
      ```
      Or in order to listen following changes run instead
      ```
      npm run watch
      ```
   6. Run migrations
      ```
      php artisan migrate
      ```
   7. Run Laravel built-in development server
      ```
      php artisan serve
      ```
   8. In order to run app go to following path [localhost:8000](http://localhost:8000/)
   
   9. Go to `/register` page and register new user
   
   10. Login with credentials of registered user
   
   ### 11. Enjoy withapplication!
    
      
 
 ###### Example home posts page with ability favorite specific post 

![Mockup for feature A](https://raw.githubusercontent.com/Maksim1990/Laravel_VueJS_Blog_favorites/master/storage/git/fav01.png)

###### Example page with all favorites posts

![Mockup for feature A](https://raw.githubusercontent.com/Maksim1990/Laravel_VueJS_Blog_favorites/master/storage/git/fav1.png)
