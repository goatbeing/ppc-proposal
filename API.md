# API

## Prepunk Verify API

Simple API to verify if an ENS domain is a historical "Prepunk"

***

### Endpoints

#### Verify by Name

Lookup a Prepunk by ENS name.

```http
GET /api/name/{name}
```

**Example:**

```bash
curl "https://verify.prepunk.club/api/name/samsidsof"
```

**Response:**

```json
{
  "record": {
    "row_number": 86,
    "name": "samsidsof",
    "_hash": "\\x01576631a94308735b5033f0d175005f32efd05c4b1df02ff4071a8635442d36",
    "registered_date": "2017-05-10T12:06:37.000Z",
    "prepunk": "YES"
  }
}
```

***

#### Verify by Hash

Lookup a Prepunk by Keccak256 hash.

```http
GET /api/hash/{hash}
```

**Example:**

```bash
curl "https://verify.prepunk.club/api/hash/0x01576631a94308735b5033f0d175005f32efd05c4b1df02ff4071a8635442d36"
```

**Response:**

```json
{
  "record": {
    "row_number": 86,
    "name": "samsidsof",
    "_hash": "\\x01576631a94308735b5033f0d175005f32efd05c4b1df02ff4071a8635442d36",
    "registered_date": "2017-05-10T12:06:37.000Z",
    "prepunk": "YES"
  }
}
```
