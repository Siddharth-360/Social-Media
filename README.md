# Social Network Laravel Application


### Installation

1. Clone the Social Network repository from GitHub:

    ```bash
    git clone https://github.com/Siddharth-360/Social-Media.git
    ```

2. Change into the project directory:

    ```bash
    cd Social_Network
    ```

3. Install PHP dependencies using Composer:

    ```bash
    composer install
    ```

4. Copy the `.env.example` file to `.env`:

    ```bash
    cp .env.example .env
    ```

5. Generate an application key:

    ```bash
    php artisan key:generate
    ```

6. Configure your database connection settings in the `.env` file. You'll need to set the following variables:

    ```
    DB_CONNECTION=mysql
    DB_HOST=your_database_host
    DB_PORT=your_database_port
    DB_DATABASE=your_database_name
    DB_USERNAME=your_database_username
    DB_PASSWORD=your_database_password
    ```

    Replace the placeholders with your actual database information.

7. Migrate the database to create the necessary tables:

    ```bash
    php artisan migrate
    ```

8. Install JavaScript dependencies using npm:

    ```bash
    npm install
    ```

9. Compile frontend assets:

    ```bash
    npm run dev
    ```
10. Start the development server:

    ```bash
    php artisan serve
    ```

    By default, the application will be accessible at `http://localhost:8000`.

