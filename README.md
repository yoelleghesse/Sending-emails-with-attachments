The Automated Email Sender is a Python script that sends an email to a specified recipient using the yagmail library. It allows you to send emails with custom subjects and contents, including text and file attachments.

Install dependencies:

``pip install yagmail``

Set up environment variables:

- Ensure you have set up your Gmail address as the sender (sender).
- Use a Gmail app password as the password for the yagmail SMTP connection.

Customize the email content:

- Modify the receiver, subject, and contents variables to specify the recipient email address, email subject, and email contents.
- You can include text content and file attachments in the contents variable. Ensure that the file paths are correct.

Run the script:

``python automated_email_sender.py``
