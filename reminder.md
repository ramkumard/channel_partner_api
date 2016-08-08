Fetch followups for user
========

Route
------

* `GET ​http://housingman.com/api/followups?token=xresedr` fetch the user followups.

Headers
-------

* `Accept: application/json`
* `Content-Type: application/json`

Example
-------

Request
-------

* `GET ​http://housingman.com/api/followups?token=xresedr` fetch the user followups.


Body
----

Response
--------

```json
{
    "data": [{
        "name": "testing",
        "lead_id": 1,
        "user_id": 1,
        "comments": "hai",
        "lead_status": "open",
        "next_schedule_at": "2016-08-02"
    }, {
        "name": "testing",
        "lead_id": 1,
        "user_id": 1,
        "comments": "hai",
        "lead_status": "open",
        "next_schedule_at": "2016-08-02"
    }],
    "meta": {
        "status": 200,
        "message": "",
        "page_info": {
            "current_page": 1,
            "prev_page": null,
            "next_page": null,
            "total_pages": 1,
            "total": 2,
            "per_page": 10
        }
    }
}
```

Create Reminder
==============
Route
------

* `POST ​http://housingman.com/api/followups?token=xresedr` fetch the user followups.

Headers
-------

* `Accept: application/json`
* `Content-Type: application/json`

Example
-------

Request
-------

* `POST ​http://housingman.com/api/followups?token=xresedr` create user followups.


Body
----
```json
{
    "name": "testing",
    "lead_id": "1",
    "comments": "hai",
    "lead_status": "open",
    "next_schedule_at": "2/8/2016"
}
```
Response
--------

```json
{
    "data": [{
        "name": "testing",
        "lead_id": 1,
        "user_id": 1,
        "comments": "hai",
        "lead_status": "open",
        "next_schedule_at": "2016-08-02"
    }, {
        "name": "testing",
        "lead_id": 1,
        "user_id": 1,
        "comments": "hai",
        "lead_status": "open",
        "next_schedule_at": "2016-08-02"
    }],
    "meta": {
        "status": 200,
        "message": "",
        "page_info": {
            "current_page": 1,
            "prev_page": null,
            "next_page": null,
            "total_pages": 1,
            "total": 2,
            "per_page": 10
        }
    }
}
```

Upnext_schedule_at Reminder
==============
Route
------

* `PUT ​http://housingman.com/api/followups/:id?token=xresedr` upnext_schedule_at the user followups.

Headers
-------

* `Accept: application/json`
* `Content-Type: application/json`

Example
-------

Request
-------

* `PUT ​http://housingman.com/api/followups/1?token=xresedr` upnext_schedule_at user followups.


Body
----
```json
{
    "name": "testing",
    "lead_id": "1",
    "comments": "hai",
    "lead_status": "open",
    "next_schedule_at": "2/8/2016"
}
```
Response
--------

```json
{
    "data": [{
        "name": "testing",
        "lead_id": 1,
        "user_id": 1,
        "comments": "hai",
        "lead_status": "open",
        "next_schedule_at": "2016-08-02"
    }, {
        "name": "testing",
        "lead_id": 1,
        "user_id": 1,
        "comments": "hai",
        "lead_status": "open",
        "next_schedule_at": "2016-08-02"
    }],
    "meta": {
        "status": 200,
        "message": "",
        "page_info": {
            "current_page": 1,
            "prev_page": null,
            "next_page": null,
            "total_pages": 1,
            "total": 2,
            "per_page": 10
        }
    }
}
```
Delete Reminder
==============
Route
------

* `PUT ​http://housingman.com/api/followups/:id?token=xresedr` delete the user followups.

Headers
-------

* `Accept: application/json`
* `Content-Type: application/json`

Example
-------

Request
-------

* `DELETE ​http://housingman.com/api/followups/1?token=xresedr` delete user followups.


```
Response
--------

```json
{
    "data": [],
    "meta": {
        "status": 200,
        "message": "Deleted",
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