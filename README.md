# Scheduled Email Dispatcher

Scheduled Email Dispatcher is a user-friendly, GUI-based tool designed to streamline the process of sending periodic emails with attachments. Utilizing an SMTP server, this application aims to automate and simplify your email sending tasks, making it perfect for regular reports, newsletters, or any communication that follows a set schedule.

## Features

- **User-Friendly Interface**: Easy-to-navigate GUI that allows users to set up their email sending tasks without hassle.
- **SMTP Integration**: Secure and reliable email dispatch through integration with SMTP servers.
- **Schedule Flexibility**: Configure your email sending tasks to run periodically - daily, weekly, or at any custom interval.
- **Attachment Support**: Send documents, images, or any other files as attachments with your emails.
- **Email Customization**: Personalize your email subject, body, and attachments for each scheduled dispatch.

## Getting Started

### Prerequisites

- Python 3.x
- Access to an SMTP server (e.g., Gmail, Outlook)

### Installation

1. Clone the repository:
    ```
    git clone https://github.com/assaf-malki/scheduled-email-dispatcher.git
    ```

2. Navigate to the project directory:
    ```
    cd scheduled-email-dispatcher
    ```

3. Install the required packages:
    ```
    pip install -r requirements.txt
    ```

### Usage

1. Run the application:
    ```
    python app.py
    ```

2. Follow the GUI prompts to configure your SMTP server settings, email content, and scheduling preferences.

3. Save your settings and activate the scheduler. The application will handle the rest, sending your emails according to the schedule you set.

## License

Distributed under the MIT License. See `LICENSE` for more information.
