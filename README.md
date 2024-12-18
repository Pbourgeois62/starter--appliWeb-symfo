# Symfony Project Initialization with Dunglas Symfony Docker

This project is based on the [Dunglas Symfony Docker](https://github.com/dunglas/symfony-docker) image, which provides an optimized and production-ready Docker setup for Symfony applications.

---

## **Dependencies**

### **Database**
- **doctrine/orm**: Object Relational Mapper (ORM) for database management.
- **doctrine/doctrine-bundle**: Integration of Doctrine with Symfony.
- **doctrine/doctrine-migrations-bundle**: For managing database migrations.

### **Security**
- **symfony/security-bundle**: Provides authentication and authorization mechanisms.
- **symfony/password-hasher**: For secure password management.

### **Front-End Tools**
- **Flowbite**: A CSS framework built on Tailwind CSS for rapid UI development.
- **symfony/twig-bundle**: For templating using Twig.
- **symfony/asset-mapper-bundle**: For managing front-end assets (CSS, JS, images).

### **Development Tools**
- **symfony/debug-bundle**: Debugging tools for development.
- **symfony/var-dumper**: Advanced debugging and logging.
- **symfony/maker-bundle**: CLI tool for generating boilerplate code.
- **phpstan/phpstan**: Static analysis tool for code quality.
- **roave/security-advisories**: To detect vulnerabilities in dependencies.

---

## **Docker Configuration**

This project uses the **Dunglas Symfony Docker** image, which includes pre-configured services to streamline development.  

### **Services**
1. **App Service**: Runs the Symfony application on PHP 8.2 with optimized settings.
2. **Caddy**: A modern web server for handling HTTPS and reverse proxying.
3. **Database Service**: Supports multiple databases (PostgreSQL, MariaDB, etc.).
4. **Database Visualization Service**: pgadmin4 for managing the database.