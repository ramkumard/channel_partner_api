Otp no verification
========

Route
------

* `POST ​http://housingman.com/api/verify_otp` verify mobile otp.


Headers
-------

* `Accept: application/json`
* `Content-Type: application/json`

Example
-------

Request
-------

* `​POST ​http://housingman.com/api/verify_otp` verify mobile otp.


Body
----

```json
{
	"mobile": "9994516652",
	"otp": "2"
}
```

Response
--------

```json
{
	"data": [],
	"meta": {
		"status": 200,
		"message": "Otp Verified.Continue Registration",
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
```Login Response
{
	"data": [{
		"id": 40,
		"email": "ramac37@gmail.com",
		"name": "Ram",
		"own_car": false,
		"organization_name": null,
		"work_type": null,
		"profile_type": null,
		"address_one": null,
		"address_two": null,
		"mobile": "1234567890"
	}],
	"meta": {
		"status": 200,
		"message": "Otp Verified",
		"page_info": {
			"current_page": 1,
			"prev_page": null,
			"next_page": null,
			"total_pages": 1,
			"total": 1,
			"per_page": 10
		}
	}
}
```
