# all-recipes

## Recipe Website - Symfony 7.2  

### About the Project  

This is a recipe website built with **Symfony 7.2** and **PHP 8.2**. The project is designed to explore the latest maintained version of Symfony while providing a platform to display recipes. It includes an admin panel for managing recipes.  

### Features  

- Public recipe listing  
- Admin panel to **create, update, view, and delete** recipes  
- Basic styling and responsive design  

### Installation  

#### Prerequisites  

- PHP 8.2 or higher  
- Composer  
- Symfony CLI  
- A database (MySQL, PostgreSQL, SQLite, etc.)  

#### Steps  

1. Clone the repository:  

   ```sh
   git clone <repository-url>
   cd <project-folder>
   ```  

2. Install dependencies:  

   ```sh
   composer install
   ```  

3. Configure the environment:  

   - Open `.env` file and update database credentials  

4. Create database schema:  

   ```sh
   symfony console doctrine:database:create
   symfony console doctrine:migrations:migrate
   ```  

5. Run the development server:  

   ```sh
   symfony server:start
   ```  

### Technologies Used  

- **Symfony 7.2** (PHP Framework)  
- **Twig** (Templating Engine)  
- **Doctrine ORM** (Database Management)  
- **Bootstrap/Tailwind CSS** (Frontend styling)  
- **Webpack Encore** (Asset management)  

### Future Enhancements  

- User authentication  
- Recipe categories and filters  
- Image uploads for recipes  
- User interactions (likes, comments, ratings)  
