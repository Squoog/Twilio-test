# What is this?

This is a small project built to experiment with Twilio to send an SMS message to a phone number.

## How do I use this?

You can start by cloning this repository
Then, install dependencies using the command `npm install`

You'll then want to create a file and name it `.env`

Copy the contents of the `.env.test` file provided into this new file and replace the placeholder information with your Twilio account SID, authorization key, provided phone number, and the number of the recipient. Note that you must include the country code as part of the phone number.

Once complete, your .env file might look something like this:

```
TWILIO_ACCOUNT_SID='EEEEEEEEEEEEEEEEEEEEEEE'
TWILIO_AUTH_TOKEN='AAAAAAAAAAAAAAAAAAAAAAA'
SEND_FROM_NUMBER='+14050000000'
SEND_TO='+14160000000'
```

## Let's send the text!

Now that everything is set up, you can run the `send_sms.js` file, and your recipient should receive an SMS message saying `I like eggs` (provided that you have not edited the message before reaching this step)