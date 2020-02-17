### OOP PHP

#### Description

This project demonstrates use of PHP Object Oriented principles to make an HTML form generator with a MYSQL database.

- Please note that 'OOP - Inheritance' is yet to be added in to ensure *DRY (Don't Repeat Yourself)* is put into account. 

#### Installation
- Install Docker,  PHP and Composer
- Install `Valet` by following this documentation [the docs here](https://laravel.com/docs/6.x/valet)
- Clone this repo
- Spin up a docker-compose network by running:

```docker-compose up -d```

This will start MySQL (Port 3306), PHPMyAdmin(8000) and log monitor for all containers on port 8080.

- Using the PHPMyAdmin interface running on localhost port 8080, login with credentials as seen in docker-compose.yml, create a DB site, import the `site.sql` file in the SQL directory of our project 

- Change to the directory of the project you cloned. Run `valet park` in the terminal.
- In your browser, visit `project_folder_name.test` to see the project