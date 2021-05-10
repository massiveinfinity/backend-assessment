# Backend Assessment

Objective: To create an admin dashboard to manage companies and their employees

In this assessment, you will be required to demonstrate your understanding on:

1. MVC code structure
2. Authentication and basic security
3. Developing CRUD features with REST APIs
4. Eloquent and relationships
5. Database migrations and seeding
6. Form Validations
7. File management
8. Usage of any backend frameworks

## Requirements

1. Able to login into application as Adminstrator
2. Use database seedings to create the first Administrator user, e.g. with email admin@admin.com and password "password"
3. Design and develop database tables:
  - Companies
    - ID (unique)
    - Name (required)
    - Email
    - Logo
    - Website URL
  - Employees
    - ID (unique)
    - First name (required)
    - Last name (required)
    - Company (foreign Key to `Companies`)
    - Email
    - Phone
4. Use database migratinos to create the table schemas
5. Store companies logo locally in a `public` folder that is accessible via URL

## Other Tips

Feel free to use the language and framework you are familiar with.

### PHP 

You may use Laravel framework to assist with your development:
- Use basic Laravel resource controllers with default methods – index, create, store etc.
- Use Laravel’s validation function, using Request classes
- Use Laravel’s pagination for showing Companies/Employees list, 10 entries per page
- Use Laravel make:auth as default Bootstrap-based design theme, but remove ability to register

### NodeJS

You may use Express with Sequelize to assist with your development

## Deliverables

1. Submit your project codes into an online GIT repository (e.g. Github, Bitbucket, Gitlab)
2. Please use `.gitignore` to avoid uploading unnecessary files to the repo
3. Upload any screenshots into your repo, and attach to your `README` file
4. Provide necessary instructions to get the app installed and runnning


## Good luck! 💪

`const activity = brain !== Brain.Empty ? keepCoding() : drinkCoffee()`
