# Django ToDo App

Django ToDo App is a simple application for managing your tasks and to-dos.

## Prerequisites

Before you get started, ensure that you have the following prerequisites:

Python installed on your system.

Django installed. You can install it using pip:
```bash
$ pip install Django
```

## Installation

To set up and run the app on your local machine, follow these steps:

Clone this repository to your local machine:
```bash
$ git clone <repository-url>
```

Replace <repository-url> with the URL of this repository.

Navigate to the cloned repository directory:
```bash
$ cd django-todo-app
```
Create the necessary database migrations by running:
```bash
$ python manage.py makemigrations
```
This command will generate the migration files required to set up your database.

Apply the migrations to create the database tables:
```bash
$ python manage.py migrate
```
Next, you'll need to create an admin user to manage your ToDo App. Run the following command and provide a username, password, and email for the admin user when prompted:
```bash
$ python manage.py createsuperuser
```
Your app is now almost ready. To start the server and make your ToDo App live, use the following command:
```bash
$ python manage.py runserver
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)