
# NGL-Spammer
This Python script is used to automatically send messages to [ngl.link](https://ngl.link) service. It sends a specified message to a given username a certain number of times.

## Requirements

- Python 3.x

## Installation

1. download this code:
   ```bash
   git clone https://github.com/MarkyLozon/nglspam
2. Go to NGL-Spammer file:
    ```bash
     cd nglspam
3. Install the required libraries by running the following command:
    ```bash
    pip install -r requirements.txt
4. NGLSpamer.py Run:
     ```bash
     python NGLSpam.py
## Usage

1. Enter your username.
2. Enter the message you want to send.
3. Specify the number of messages to be sent.

The script will automatically start sending the specified message to the given username. Successful submissions will be marked with [+] while unsuccessful submissions will be marked with [-].

If there are 10 consecutive unsuccessful submissions, the script will wait for 5 seconds and then continue with the retry process.

