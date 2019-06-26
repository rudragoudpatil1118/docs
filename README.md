* Installation
  - Clone the code
  - Install dependencies using composer
  #+BEGIN_SRC sh
  composer install
  #+END_SRC
  - Rename .env.example to .env and modify the values according to your needs
  - Switch to your module folder
  - Migrate Database tables
    #+BEGIN_SRC sh
     - php artisan migrate
    #+END_SRC
  - Seed Tables
    #+BEGIN_SRC sh
     - php artisan db:seed
    #+END_SRC
