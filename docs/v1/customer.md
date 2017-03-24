# eviratec / schema / v1 / customer

## Examples

### Ex 1.

```json
{
    "id": "4a0b1275-7cbb-415d-91b1-254da442db76",
    "contact": {
      "person": {
        "name": "Mrs. Jane Smith",
        "email": "jane.smith@noreply.eviratec.software",
        "phone": "+61234567890"
      },
      "unread_messages": 0,
      "date_entered": "2017-03-24 23:12:14.369609611+11:00",
      "is_flagged": false
    },
    "accounts": [{
      "id": "3509a1ad-862c-4515-ac75-f6806c6ba1f8",
      "customer_id": "4a0b1275-7cbb-415d-91b1-254da442db76",
      "balance": {
        "units": 47.55,
        "currency": {
          "id": "5e488c2c-0d6d-4712-b5f0-8a7348ead291",
          "code": "AUD",
          "label": "Australian Dollars",
          "prefix": "$",
          "separator": {
            "thousands": ",",
            "decimal": "."
          },
        },
        "in": "dr"
      }
    }],
    "additional_contacts": [{
      "person": {
        "name": "Mr. John Smith",
        "email": "john.smith@noreply.eviratec.software",
        "phone": "+61234567890"
      },
      "unread_messages": 1,
      "date_entered": "2017-03-24 23:12:14.369609611+11:00",
      "is_flagged": false
    }],
    "date_opened": "2017-03-24 23:12:14.369609611+11:00",
    "is_suspended": false
  }
}
```
