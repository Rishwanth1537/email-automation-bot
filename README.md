# Email Automation Bot using Python
This is a simple Python-based Email Automation Bot that sends scheduled emails on Monday, Wednesday, and Friday at 8:00 AM (or your custom time). It can be deployed on a cloud platform like PythonAnywhere to run continuously without needing to keep your computer on.

# 🔧 Features
Sends automated emails at scheduled times using Gmail's SMTP server.
Uses secure login via Google App Password.
Customizable subject and body.
Can be modified to send emails on any day/time.
Ideal for notifications, reminders, or demo bots.

# 🧰 Requirements
The following Python libraries are used:
# Library   	           Purpose
smtplib	   ->    To send emails using Gmail's SMTP \n
email.mime -> 	 To format the email with subject/body\n
schedule	 ->    To schedule the email on specific days\n
datetime	 ->    For logging timestamps\n
time	     ->    To keep the bot running with time checks\n

# 🛠 How It Works
The script defines sender and receiver email, subject, and body.
Uses the smtplib library to connect to Gmail’s SMTP server securely.
schedule library is used to run the send_email() function:
Every Monday, Wednesday, and Friday at 8:00 AM.
The program runs continuously in a loop and checks every minute for pending tasks.
To STOP the bot, simply close the terminal
