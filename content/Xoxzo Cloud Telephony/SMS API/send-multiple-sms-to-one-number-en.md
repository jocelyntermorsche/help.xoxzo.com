Title: Is multiple sendings to one same number possible?
Date: 2017-10-27 13:20
Slug: send-mutiple-sms-to-one-number
Lang: en
Category: Xoxzo Cloud Telephony/SMS API

## when we test an API, it can be happen to send multiple SMS to a same phone number. Does this cause any problems?

Yes and No,
Although rhe detailed specifications varies from carrier to carrier and it is impossible for us to cover them all, there are functions to block the continuously flowing messages called 'anti-flooding' to avoid one phone to receive the similar messages repeatedly.

To keep testing, you may set different content in the body text and/or interval of sendings at 1 minutes.

We may follow up any failed sendings when you find.
Please contact us with the number that you send the message to, and the date and time that the messages were sent along with your email address registered to Xoxzo.
