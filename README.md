# Fail2ban sms action

## About

Provides an action for Fail2ban program to send text messages using Twilio API.
## How to use

In short:
* Move sms.conf into into /etc/fail2ban/actions.conf
* Configure jail.local to include sms action where wanted
* Ensure fail2ban-sms.sh is located at /home/all/ are change the paths in sms.conf
* Create a secret.conf in the same dir as fail2ban-sms.sh

Or read [my blogpost](http://toonketels.github.com/post/2013-03-23-fail2ban-send-sms-user-banned/).

