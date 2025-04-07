# test_python_rabbitmq Documentation

## 1. Installation of RabbitMQ

Install RabbitMQ on the server
Verify the installation
Start the RabbitMQ service

## 2. Setting up Virtual Environment

### Creating a virtual environment

`python -m venv venv`

### Activating the virtual environment

`source venv/bin/activate # for Unix/Linux/macOS
venv\Scripts\activate # for Windows`

## 3. Running the Message Receiver

Open a terminal
Navigate to the project directory
Run the message receiving script:

`python receive.py`

## 4. Running the Message Sender

Open a second terminal
Navigate to the project directory
Run the message sending script:

`python send.py`

## 5. Verification

Ensure that messages are transmitted correctly between scripts
Check logs for errors

## 6. Troubleshooting

Issue: Scripts are not interacting
Solution:

Check that the RabbitMQ server is running
Ensure both scripts are running in an active virtual environment
Verify correct file paths
Note: Make sure Python and necessary dependencies are installed before starting.
