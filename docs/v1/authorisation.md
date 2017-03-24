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
      "id": "ce08a4f5-2087-4934-8628-ca5e1c3265c2",
      "date": "2017-03-24 23:52:05.411305144+11:00",
      "user_agent": "software.eviratec.crm.webclient/1.0.0-alpha1",
      "remote_address": "10.0.0.1",
      "is_flagged": false,
      "is_resolved": true,
      "auth_token": {
          "id": "ce08a4f5-2087-4934-8628-ca5e1c3265c2",
          "client_id": "093e631d-77e8-46e8-925a-fca90e2d8bdf",
          "token": "0121445f0c055ff43ed92da845593d0c38bc6b4a179f22079b9a3f06aaf633d1",
          "date_created": "2017-03-24 23:41:56.235902530+11:00",
          "expiry_seconds": 86400,
          "is_expired": false,
          "is_flagged": false,
          "is_suspended": false
        }
      },
      "resolution": {
        "id": "79de849f-93d4-4882-9b6f-f29732ffc4a0",
        "type": "success",
        "has_failed": false
      }
    },
    "date_created": "2017-03-24 23:41:56.235902530+11:00",
    "is_locked": false,
    "is_flagged": false,
    "is_suspended": false
  }
}
```
