## Python script check your email and call your phone 

This script use Twillio to make calls!

### Reqiurements 

1- Twillio account
2- Python3, pip3
3- Gmail account 


### Set up Twillio 
Add the numbers we want to call as verified phone numbers in https://www.twilio.com/console/phone-numbers/verified, otherwise you will not be able to call them.


### Set up Gmail
We will use the imaplib library to track our emails, but the mail account needs to be less secure to use this library. https://www.youtube.com/watch?v=Y_u5KIeXiVI

### Set up python 

```

pip3 install twilio

```

### Start script 

```

touch /root/counter.txt

python3 twillio-calls.py

```