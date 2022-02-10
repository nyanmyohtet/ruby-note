# The Model View Controll (MVC) Pattern

HTTP Request

```
GET /about HTTP/1.1
Host: 127.0.0.1
...
```

## Route

Matcher for the URL that is requested.

`GET /about HTTP/1.1`

I see you request `/about` URL, we'll give that to the AboutController to handle it.

## Model

Database Wrapper

User:
* Query for records

## View

The response body content:
* HTML
* PDF
* CSV
* XML

This is what gets send back to the browser and displayed.

## Controller

Decide how to process a request and define a response
