# eviratec / schema / v1 / customer / account

## Examples

### Ex 1.

```json
{
  "id": "3509a1ad-862c-4515-ac75-f6806c6ba1f8",
  "customer_id": "4a0b1275-7cbb-415d-91b1-254da442db76",
  "balance": {
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
    "units": 47.55,
    "in": "dr"
  }
}
```

### Ex 2.

```json
{
  "id": "3509a1ad-862c-4515-ac75-f6806c6ba1f8",
  "customer_id": "4a0b1275-7cbb-415d-91b1-254da442db76",
  "balance": {
    "currency": {
      "id": "7e0e33f1-7d0b-4316-b013-1ddfcf8ab019",
      "code": "GBP",
      "label": "British Pound",
      "prefix": "£",
      "separator": {
        "thousands": ",",
        "decimal": "."
      },
    },
    "units": 38.11,
    "in": "cr"
  }
}
```
