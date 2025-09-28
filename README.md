# Timestamp Microservice

A simple API that converts between Unix timestamps and UTC date strings.

This is the solution for the Timestamp Microservice project. Instructions for building your project can be found at: 
https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/timestamp-microservice



## Usage

- `GET /api/` - Returns current timestamp
- `GET /api/:date` - Converts date/timestamp to both formats

## Examples

- `/api/1451001600000` → Unix timestamp input
- `/api/2015-12-25` → Date string input
- `/api/` → Current time

Returns JSON with `unix` and `utc` keys, or `{error: "Invalid Date"}` for invalid input.

## Run

```bash
npm install
npm run dev
```

Visit `http://localhost:3000`