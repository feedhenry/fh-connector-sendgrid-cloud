# FeedHenry Sendgrid Connector

[![Dependency Status](https://img.shields.io/david/feedhenry-templates/fh-connector-sendgrid-cloud.svg?style=flat-square)](https://david-dm.org/feedhenry-templates/fh-connector-sendgrid-cloud)

The FeedHenry Sendgrid Connector. For more information on Sendgrid see: [https://github.com/sendgrid/sendgrid-nodejs](https://github.com/sendgrid/sendgrid-nodejs).

## Group Sendgrid Connector API

# Send email

Send an email

|              |                 | 
|--------------|-----------------|
| Endpoint     | /cloud/sendgrid |
| HTTP Method  | POST            |

#### Request (application/json)

##### Body

```json
{
  "to": "recipient",
  "subject": "email subject",
  "body": "message body"
}
```

#### Response 200 (application/json)

##### Body

```json
{
}
```

## Tests

All the tests are in the "test/" directory. The cloud app is using mocha as the test runner. 

### Unit tests

```shell
npm run unit
```

or

```shell
npm run test
```

### Unit coverage

```shell
npm run coverage
```
