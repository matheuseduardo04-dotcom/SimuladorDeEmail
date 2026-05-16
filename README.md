# Email Simulator

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="60" height="60"/>
  &nbsp;&nbsp;
  <img src="https://flagcdn.com/w80/us.png" alt="English (US)" width="60"/>
</p>

A simple email simulator written in Python using Object-Oriented Programming. It models users, inboxes, and emails — allowing users to send, receive, read, and delete messages.

## Features

- Send emails between users
- Receive emails in a personal inbox
- List all emails with read/unread status
- Open and display full email content
- Automatically mark emails as read when opened
- Delete emails from the inbox
- Timestamp on every received email

## Project Structure

```
simuladordeemail/
└── email.py
```

The project is organized around three main classes:

- **`Email`** — represents an individual email message (sender, receiver, subject, body, timestamp, read status).
- **`Inbox`** — stores and manages a user's received emails.
- **`User`** — represents a person who can send emails and access their inbox.

## How to Run

Requirements: **Python 3.x**

```bash
python email.py
```

## Example Output

```
Email sent from Tory to Ramy!
Email sent from Ramy to Tory!

Ramy's Inbox:

Your Emails:
1. [Unread] From: Tory | Subject: Hello | Time: 2026-05-16 14:30

--- Email ---
From: Tory
To: Ramy
Subject: Hello
Received: 2026-05-16 14:30
Body: Hi Ramy, just saying hello!
------------
```

## Author

Developed by **Matheus** as part of programming logic exercises.
