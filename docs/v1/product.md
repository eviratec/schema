# eviratec / schema / v1 / product

## Examples

### Ex 1.

```json
{
  "id": "4a0b1275-7cbb-415d-91b1-254da442db76",
  "code": "YEMAYA2017GA",
  "headline": "Yemaya 2017 GA Ticket",
  "full_name": "Yemaya 2017 General Admission Ticket",
  "prices": [{
    "id": "ace03b7a-6e9f-44b5-be95-007bbffe6ba3",
    "amount": {
      "units": 349,
      "currency": {
        "id": "a8ee4bc7-1fd4-4302-86a3-9cfc1a0b9cd4",
        "code": "AUD",
        "label": "Australian Dollars",
        "prefix": "$",
        "separator": {
          "thousands": ",",
          "decimal": "."
        }
      }
    },
    "type": {
      "id": "639bcd91-2938-46e7-914d-d968e98e809c",
      "label": "1st Round (Before April)",
      "code": "1STGA"
    },
    "is_public": true,
    "date_from": "2017-03-01 00:00:00.000+11:00",
    "date_thru": "2017-04-01 00:00:00.000+11:00"
  }, {
    "id": "ff2eeded-7812-47b4-b1cc-64f496068504",
    "amount": {
      "units": 249,
      "currency": {
        "id": "a8ee4bc7-1fd4-4302-86a3-9cfc1a0b9cd4",
        "code": "AUD",
        "label": "Australian Dollars",
        "prefix": "$",
        "separator": {
          "thousands": ",",
          "decimal": "."
        }
      }
    },
    "type": {
      "id": "639bcd91-2938-46e7-914d-d968e98e809c",
      "label": "2nd Round",
      "code": "2NDGA"
    },
    "is_public": true,
    "date_from": "2017-04-01 00:00:00.000+11:00",
    "date_thru": "2017-05-01 00:00:00.000+11:00"
  }],
  "date_added": "2017-03-25 16:09:34.183781957+11:00",
  "is_purchaseable": true
}
```
