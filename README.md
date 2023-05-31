# Django Password Generator

This is a simple web application developed using the Django framework that allows users to generate random passwords with customizable options.

## Features

- Generate random passwords with adjustable length.
- Choose to include uppercase letters, lowercase letters, numbers, and special characters in the generated passwords.
- Copy the generated password to the clipboard with a single click.
- Responsive web design for seamless use on different devices.

## Requirements

- Python 3.x
- Django 3.x

## Installation

1. Clone the repository:

```shell
git clone https://github.com/eyongegbe/django-passwordgenerator.git
```

2. Navigate to the project directory:

```shell
cd django-password-generator
```

3. Create and activate a virtual environment (optional but recommended):

```shell
python3 -m venv myenv
source myenv/bin/activate
```

4. Install the required dependencies:

```shell
pip install -r requirements.txt
```

5. Run the Django development server:

```shell
python manage.py runserver
```

6. Access the application in your web browser at `http://localhost:8000`.

## Configuration

The application uses the default Django settings. However, you can customize certain aspects by modifying the `settings.py` file in the project directory.

- `SECRET_KEY`: Django secret key for securing sessions and passwords. It is recommended to generate a unique secret key for production use.
- `DEBUG`: Set to `True` during development for detailed error pages. Change to `False` for production.
- `ALLOWED_HOSTS`: Add the appropriate hosts or domains that will be allowed to access the application.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).