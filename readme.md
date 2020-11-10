# Global Entry Interview Openings Checker

This program is a modified fork of:

## Setup

- If you don't have a Twilio account, [create one]() for free, and create a free [phone number](https://www.twilio.com/console/phone-numbers). This is where your texts will originate from
- Install the dependencies `pip install -r requirements.txt`
- Copy `config.py.template` to a new file `config.py`
- Edit `config.py`:
  - Enter your Twilio [tokens](https://www.twilio.com/console)
  - Enter your Twilio ['from' phone number](https://www.twilio.com/console/phone-numbers)
  - Enter your desired destination cell number, amount of weeks to look ahead, and your city search string
- add this script to your crontab (see [virtualenv notes](https://stackoverflow.com/questions/3287038/cron-and-virtualenv)). Direct the output to a log file to keep track of it
- wait for it

*A [Two Hour Project](http://ma.rtijn.org/two-hour-projects/)*