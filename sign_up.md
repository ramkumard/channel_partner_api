Register User
========

Route
------

* `POST ​http://housingman.com/api/users` register user with housingman.


Headers
-------

* `Accept: application/json`
* `Content-Type: application/json`

Example
-------

Request
-------

* `POST ​http://housingman.com/api/users` register user with housingman.


Body
----

```json
{
    "user": {
        "name": "RamSampet",
        "mobile": "7872365567",
        "email": "ramac476@gmail.com",
        "image":"/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAAMCAgMCAgMDAwMEAwMEBQgFBQQEBQoHBwYIDAoMDAsKCwsNDhIQDQ4RDgsLEBYQERMUFRUVDA8XGBYUGBIUFRT/2wBDAQMEBAUEBQkFBQkUDQsNFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUF",
    	"image_name":"pic7",
    	"channel_partner_user_localities_attributes": {
            "0": {
                "locality_id": "1"
            }
        }
    }
}
//add others fields
```

Response
--------

```json
{
    "data": [{
        "id": 41,
        "email": "rama67@gmail.com",
        "name": "Ram",
        "own_car": false,
        "organization_name": null,
        "work_type": null,
        "profile_type": null,
        "address_one": null,
        "address_two": null,
        "mobile": "6646865376"
    }],
    "meta": {
        "status": 200,
        "message": "Successfully logged in",
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
