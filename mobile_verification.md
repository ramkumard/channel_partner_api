Mobile no verification
========

Route
------

* `POST ​http://housingman.com/api/verify_mobile` verify mobile no.


Headers
-------

* `Accept: application/json`
* `Content-Type: application/json`

Example
-------

Request
-------

* `​POST ​http://housingman.com/api/verify_mobile` verify mobile no.


Body
----

```json
{
    "mobile": "9994516652"
}
```

Response
--------

```json
{
    "data": [],
    "meta": {
        "status": 200,
        "message": "Otp Sent",
        "page_info": {
            "current_page": 1,
            "prev_page": null,
            "next_page": null,
            "total_pages": 0,
            "total": 0,
            "per_page": 10
        }
    }
}

```
