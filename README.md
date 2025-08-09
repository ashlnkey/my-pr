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
composer install
composer require drush/drush:*
drush cim

### 1. Clone Project
git clone https://github.com/ashlnkey/drupal-search-assignment.git
cd drupal_search_package


