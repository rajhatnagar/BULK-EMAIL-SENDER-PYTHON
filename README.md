# Bulk Email Sender Python Script using SMTP

This is a Python script that allows you to send bulk emails using the Simple Mail Transfer Protocol (SMTP). The project demonstrates how to automate the process of sending emails to a large number of recipients.

## Overview

The script reads recipient email addresses and their details from a CSV file. It then sends personalized emails to each recipient using the provided email template. The script utilizes the SMTP protocol to connect to an email server and send emails in bulk.

## Features

- Read recipient details from a CSV file.
- Customize email content using a template with placeholders.
- Utilize the `smtplib` library to send emails via SMTP.
- Efficiently handle bulk email sending with error handling.

## Prerequisites

- Python 3.x installed on your machine.
- Basic knowledge of Python and CSV file handling.

## Usage

1. Install the required packages using `pip install -r requirements.txt`.
2. Modify the `config.json` file with your SMTP server details and email template.
3. Create a CSV file (`recipients.csv`) containing recipient details (name, email, etc.).
4. Run the script: `python bulk_email_sender.py`.

## Configuration

- Customize the `config.json` file to match your SMTP server settings.
- Adjust the `email_template.html` file to suit your email content.
- Ensure your SMTP server allows the specified email address to send emails.

## Security Considerations

- Be cautious when using personal or sensitive information in the email template.
- Avoid hardcoding sensitive information (such as passwords) in your scripts.

## Disclaimer

This script is intended for educational and legitimate use. Do not use it for spamming or any malicious activities. Always adhere to email sending guidelines and privacy regulations.

## License

This project is licensed under the [MIT License](LICENSE).
