# eviratec / schema / v1 / authorisation

## Examples

### Ex 1.

*Mr. John Smith*, is the holder of an, abstract *authorisation,* which was created on `2017-03-24 23:41:56.235902530+11:00`. It is not: *locked*, *flagged*, or *suspended*.  It's unique identifier is `ce08a4f5-2087-4934-8628-ca5e1c3265c2`.

```json
{
    "id": "ce08a4f5-2087-4934-8628-ca5e1c3265c2",
    "holder": {
      "name": "Mr. John Smith",
      "email": "john.smith@noreply.eviratec.software",
      "phone": "+61234567890"
    },
    "last_login": {
      // v1/authentication/attempt.json
    },
    "date_created": "2017-03-24 23:41:56.235902530+11:00",
    "is_locked": false,
    "is_flagged": false,
    "is_suspended": false
  }
}
```
