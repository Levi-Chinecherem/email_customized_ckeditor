# O Sender - Email Sending System

O Sender is a simple Django-based email sending system that allows users to customize each email using CKEditor before sending it. This system is designed to be easy to use and flexible for different email content.

## Features

- **Email Customization:** Utilize CKEditor to customize the content of each email, making it personal and engaging.

## Getting Started

Follow these instructions to set up and run O Sender on your local machine.

### Prerequisites

- Python 3.x
- Django
- CKEditor
- Redis (Optional, for future Celery integration, the next coming o-sender)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Levi-Chinecherem/email_customized_ckeditor.git

   ```
2. Change to the project directory:

   ```bash
   cd email_customized_ckeditor
   ```
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
4. Apply database migrations:

   ```bash
   python manage.py migrate
   ```
5. Create a superuser:

   ```bash
   python manage.py createsuperuser
   ```
6. Run the development server:

   ```bash
   python manage.py runserver
   ```
7. Access the admin panel at http://127.0.0.1:8000/admin/ to add email templates.
8. Access the main application at http://127.0.0.1:8000/ to send emails with CKEditor customization.

## Usage

1. Log in with your superuser credentials.
2. Navigate to the "Email Templates" section in the admin panel to add pre-defined email templates.
3. Go to the main application and select a template to send.
4. Customize the email content using CKEditor.
5. Send the email.

## Contributing

Feel free to contribute to the development of O Sender by submitting issues or pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
