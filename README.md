# SMS_BOMBER_IPHONE
This is a Python-based SMS Bomber script. It sends a specified number of SMS messages to a target mobile number. The script uses multiple providers to send the SMS messages and supports multi-threading for concurrent requests.

Requirements :clipboard:

    Python 3
    requests library
    argparse library
    concurrent.futures library
    json library
    time library

Usage :gear:

To use the SMS Bomber, follow these steps:

    Run the script with the target mobile number as an argument. The mobile number should be without the country code and must be 10 digits long. For example:

bash

python3 bomber.py 1234567890

    You can specify additional options such as the number of SMS messages to send (default is 20), the country code without the (+) sign (default is 91), and the maximum number of concurrent HTTP(s) requests (default is 20). For example:

bash

python3 bomber.py 1234567890 --sms 50 --country 1 --threads 50

    If you want to use a proxy for bombing, use the --proxy option. It is advisable to use this option if you are bombing more than 50 SMS messages.

    If you want to see detailed output, use the --verbose option.

    If you want to verify all providers are working or not, use the --verify option.

Disclaimer :warning:

This script is intended for educational purposes only. Use of this script without the explicit consent of the target mobile owner is illegal and unethical. The author of this script takes no responsibility for any damages or harm caused by the use or misuse of this program. Please use responsibly.
