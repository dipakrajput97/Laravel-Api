<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as:

Laravel is accessible, yet powerful, providing tools needed for large, robust applications.

## Setup Laravel

 Please make sure that you install composer on your local machine/server.
 
 The following post help you to install the composer on your local machine/server. 
 
 <a href="https://www.hostinger.com/tutorials/how-to-install-composer">How to install Composer</a>
 
 Use any one option to install the laravel on your local machine.

	$ composer global require laravel/installer
	$ laravel new “project name”
	------------------OR------------------------
	$ composer create-project --prefer-dist 						 
	$ laravel/laravel “project name”
	
## Conning the Repository

	$ git clone git@github.com:dipakrajput97/Laravel-Api.git
	$ cd Laravel-Api
	$ php artisan serve

	It will run on the http://127.0.0.1:8000 please visit.

## Database connection

Just copy the all content from the root of your setup project .env-example file and create a new file with name .env with database credentials.If you are using the composer then you do not need to do anything just put the your database credential in .env file and run the application

	DB_CONNECTION=mysql
	DB_HOST=127.0.0.1
	DB_PORT=3306
	DB_DATABASE="your database name"
	DB_USERNAME="your user name"
	DB_PASSWORD="your password"

## Helpfull Commands

- Model creation
		
		$ php artisan make:model “name of module” -m

- Migrate tables 

		$ php artisan migrate

- Database seeding 

		$ php artisan make:seeder “Name of seeder”
		$ php artisan db:seed --class=”Name of the seeder”

- Controller Creation

		$ php artisan make:controller “Name of Controller”

## Responce code

- 200: OK. The standard success code and default option. 
- 201: Object created. Useful for the store actions. 
- 204: No content. When an action was executed successfully, but there is no content to return. 
- 206: Partial content. Useful when you have to return a paginated list of resources. 
- 400: Bad request. The standard option for requests that fail to pass validation. 
- 401: Unauthorized. The user needs to be authenticated. 
- 403: Forbidden. The user is authenticated, but does not have the permissions to perform an action. 
- 404: Not found. This will be returned automatically by Laravel when the resource is not found. 
- 500: Internal server error. Ideally you're not going to be explicitly returning this, but if something unexpected breaks,
   this is what your user is going to receive. 
- 503: Service unavailable. Pretty self explanatory, but also another code that is not going to be returned explicitly by the
  application. 

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of any modern web application framework, making it a breeze to get started learning the framework.

If you're not in the mood to read, [Laracasts](https://laracasts.com) contains over 1100 video tutorials on a range of topics including Laravel, modern PHP, unit testing, JavaScript, and more. Boost the skill level of yourself and your entire team by digging into our comprehensive video library.


## Contact

	Don't be hesitate to contact,mail me on dipaksinghrajput97@gmail.com for any further query related to Laravel,It will be much appriciated.

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).


## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
