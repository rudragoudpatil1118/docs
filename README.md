# Installation

-  Clone the code
-  Install dependencies using composer
    ```sh
    composer install
    ```
-  Rename .env.example to .env and modify the values according to your needs
-  Migrate Database tables
    ```sh
     - php artisan migrate
    ```
- Seed Tables
    ```sh
        php artisan db:seed
    ```
- Cache Clear
    ```sh
        php artisan cache:clear
        php artisan config:clear
    ```
- Creating New Model
    ```sh
        php artisan infyom:model ModelName --fromTable --tableName=table_name
        eg: php artisan infyom:model WeekDay --fromTable --tableName=week_days
    ```
- Genearte Graph QL Generators
    ```sh
        php artisan graphql:generate [type,query,mutation] [ModelName]
        eg: php artisan graphql:generate [type,query,mutation] [WeekDay]
    ```
