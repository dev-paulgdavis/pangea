# News Project Django Settings

This project contains the Django settings for a Django project allowing you to use Pangea as a vault for your passwords and API keys. 
## Dependencies

Before running this project, make sure you have the following dependencies installed:

- `pangea.exceptions`
- `pangea.config`
- `pangea.services.vault.models.common`
- `pangea.services.vault.models.symmetric`
- `pangea.services.vault.vault`
- `pangea.utils`
- `dotenv`
- `django`
- `django_filters`
- `django_tables2`
- `widget_tweaks`

## Installation

1. Clone this repository to your local machine.
2. Install the required dependencies mentioned above using `pip install`.
3. Set up the environmental parameters for the VAULT token and the Pangea domain.
4. Replace the `SECRET_KEY` value with your own secret key.
5. Replace the `id` values for database and API key retrieval with your own secret vault IDs.
6. Set the `DEBUG` variable to `False` for production.
7. Update the `ALLOWED_HOSTS` list with the appropriate domain names or IP addresses.
8. Update the `DATABASES` dictionary with the required information for your database connection.

## Usage

To run the project, execute the following command:

```bash
python manage.py runserver
