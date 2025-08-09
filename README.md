# drupal-search-assignment
This package contains a complete setup for:
- Advanced search with exposed filters using Search API
- Faceted search using the Facets module
- Bootstrap grid layout for exposed filter form

---

## 📦 Contents

- `modules/custom/bootstrap_filter`: Adds Bootstrap grid classes to Views exposed filters
- `config/sync`: Exported configuration files for:
  - Views (`Advanced Search`, `Faceted Search`)
  - Search API index & server
  - Facets (`Recipe category`, `Tags`, `Facet summary`)

---

## 🛠️ Prerequisites

- PHP 8.2+
- Composer
- MySQL
- Apache/Nginx
- Drupal 10.x
- Modules:
  - Search API
  - Search API Database
  - Facets
  - Views

---

## 🚀 Setup Instructions
1. Install dependencies
    composer install
2. Select installation profile
    During Drupal installation, choose:
    Demo: Umami Food Magazine (Experimental)

3. Import the database

    Locate the database file in the db folder.
    Import it into your MySQL server:

    mysql -u root -p my_pr < db/my_pr.sql

4. Configure database settings
    In web/sites/default/settings.php, update the database configuration:

    $databases['default']['default'] = [
      'database' => 'my_pr',
      'username' => 'root',
      'password' => '',
      'host' => '127.0.0.1',
      'driver' => 'mysql',
      'port' => '3306',
      'prefix' => '',
    ];

5. Login credentials
  Username: admin
  Password: admin@123

### 1. Clone Project
https://github.com/ashlnkey/my-pr.git
cd my-pr


