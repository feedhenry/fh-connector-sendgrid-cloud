FORMAT: 1A

# FeedHenry Sendgrid Connector
[![Dependency Status](https://img.shields.io/david/feedhenry-templates/fh-connector-sendgrid-cloud.svg?style=flat-square)](https://david-dm.org/feedhenry-templates/fh-connector-sendgrid-cloud)

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

