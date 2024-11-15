﻿# Book-Your-Destination

### 1. Clone or Download the Repository
   - Go to the repository’s page on GitHub.
   - Click on **Code** and choose **Download ZIP** or copy the repository’s URL to clone it via Git.
   - To clone, use the following command in your terminal:
     ```bash
     git clone <repository-url>
     ```

### 2. Move the Project Folder to the Server Root Directory
   - If you’re using **XAMPP**, place the folder inside `xampp/htdocs`.
   - If you’re using **WAMP**, place it inside `wamp/www`.
   - If you’re using **LAMP** (Linux), place it inside `/var/www/html`.

### 3. Open PHPMyAdmin
   - Start your server (XAMPP/WAMP/LAMP).
   - Open [http://localhost/phpmyadmin](http://localhost/phpmyadmin) in your browser to access PHPMyAdmin.

### 4. Create and Import the Database
   - In PHPMyAdmin, create a new database by clicking on **New** and entering your database name.
   - Select your newly created database, go to the **Import** tab, and upload the database file provided with the project (usually a `.sql` file).

### 5. Run the Application
   - In your browser, navigate to `http://localhost/<your-folder-name>` (e.g., `http://localhost/travel` if you renamed the project folder as `travel`).
  
This should set up and launch your project. Let me know if you run into any issues!
