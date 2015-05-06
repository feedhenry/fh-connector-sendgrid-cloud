FORMAT: 1A

# FeedHenry Sendgrid Connector

The FeedHenry Sendgrid Connector. For more information on Sendgrid see: [https://github.com/sendgrid/sendgrid-nodejs](https://github.com/sendgrid/sendgrid-nodejs).

# Group Sendgrid Connector API

# Sendgrid [/cloud/sendgrid]

Send email

## Sendgrid [POST] 

Send an email

+ Request (application/json)
    + Body
        {
          "to": "recipient",
          "subject": "email subject",
          "body": "message body"
        }

+ Response 200 (application/json)
    + Body
            {
            }

