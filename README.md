# Campaign Management System

This is a campaign management system developed using Django. It allows you to send out email and SMS campaigns to individuals and businesses. The system leverages templates to generate campaign content and modify specific details before delivering them.

## Features

- Create and manage campaigns
- Select and customize campaign templates
- Send email campaigns using SMTP
- Send SMS campaigns using a third-party SMS service provider
- View campaign details and recipients

## Installation

1. Clone the repository:

```bash
git clone https://github.com/abhaymettu/campaign-management.git
```

2. Create a virtual environment:

```bash
cd campaign-management
python3 -m venv venv
```

3. Activate the virtual environment:

On macOS and Linux:
```bash
source venv/bin/activate
```

On Windows:
```bash
venv\Scripts\activate
```

4. Install the dependencies:

```bash
pip install -r requirements.txt
```

5. Configure the project:

- Open the `campaign_management/settings.py` file and set up your database settings, email configuration, and any other necessary configurations.

6. Run database migrations:

```bash
python manage.py migrate
```

7. Create a superuser account:

```bash
python manage.py createsuperuser
```

8. Start the development server:

```bash
python manage.py runserver
```

The campaign management system should now be accessible at `http://localhost:8000`.

## Usage

1. Log in to the admin panel using your superuser account at `http://localhost:8000/admin/`.

2. Create campaign templates by navigating to "Templates" and adding new templates with content placeholders.

3. Create campaigns by navigating to "Campaigns" and filling in the campaign details, selecting a template, and customizing specific details.

4. Add recipients to campaigns by navigating to "Recipients" and adding email addresses and phone numbers.

5. Send out email and SMS campaigns by selecting the desired campaign and choosing the appropriate action.

## Contributing

Contributions to the campaign management system are welcome! If you'd like to contribute/improve on my project, please follow these steps:

1. Fork the repository.

2. Create a new branch:

```bash
git checkout -b feature/your-feature-name
```

3. Make your changes and commit them:

```bash
git commit -m "Add your commit message here"
```

4. Push your changes to your forked repository:

```bash
git push origin feature/your-feature-name
```

5. Open a pull request describing your changes.

Please ensure that your contributions adhere to the project's coding standards and guidelines.
