Fetch reminders for user
========

Route
------

* `GET ​http://housingman.com/api/reminders?token=xresedr` fetch the user reminders.

Headers
-------

* `Accept: application/json`
* `Content-Type: application/json`

Example
-------

Request
-------

* `GET ​http://housingman.com/api/reminders?token=xresedr` fetch the user reminders.


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
        "description": "hai",
        "status": "open",
        "date": "2016-08-02"
    }, {
        "name": "testing",
        "lead_id": 1,
        "user_id": 1,
        "description": "hai",
        "status": "open",
        "date": "2016-08-02"
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

* `POST ​http://housingman.com/api/reminders?token=xresedr` fetch the user reminders.

Headers
-------

* `Accept: application/json`
* `Content-Type: application/json`

Example
-------

Request
-------

* `POST ​http://housingman.com/api/reminders?token=xresedr` create user reminders.


Body
----
```json
{
    "name": "testing",
    "lead_id": "1",
    "description": "hai",
    "status": "open",
    "date": "2/8/2016"
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
        "description": "hai",
        "status": "open",
        "date": "2016-08-02"
    }, {
        "name": "testing",
        "lead_id": 1,
        "user_id": 1,
        "description": "hai",
        "status": "open",
        "date": "2016-08-02"
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

Update Reminder
==============
Route
------

* `PUT ​http://housingman.com/api/reminders/:id?token=xresedr` update the user reminders.

Headers
-------

* `Accept: application/json`
* `Content-Type: application/json`

Example
-------

Request
-------

* `PUT ​http://housingman.com/api/reminders/1?token=xresedr` update user reminders.


Body
----
```json
{
    "name": "testing",
    "lead_id": "1",
    "description": "hai",
    "status": "open",
    "date": "2/8/2016"
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
        "description": "hai",
        "status": "open",
        "date": "2016-08-02"
    }, {
        "name": "testing",
        "lead_id": 1,
        "user_id": 1,
        "description": "hai",
        "status": "open",
        "date": "2016-08-02"
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

* `PUT ​http://housingman.com/api/reminders/:id?token=xresedr` delete the user reminders.

Headers
-------

* `Accept: application/json`
* `Content-Type: application/json`

Example
-------

Request
-------

* `DELETE ​http://housingman.com/api/reminders/1?token=xresedr` delete user reminders.


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