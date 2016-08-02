Active Lead
========

Route
------

* `POST ​http://housingman.com/api/leads` fetch the user leads.

Headers
-------

* `Accept: application/json`
* `Content-Type: application/json`

Example
-------

Request
-------

* `POST ​http://housingman.com/api/leads` fetch the user leads.


Body
----

Response
--------

```json
{
    "data": [{
        "lead": {
            "id": 44,
            "name": "Prashanth ",
            "email": "prashanth@housingman.com",
            "mobile": "9786848278",
            "project_id": 435,
            "created_at": "2015-12-28T13:43:40.369+05:30",
            "updated_at": "2015-12-28T13:43:40.369+05:30",
            "enquiry_type": null,
            "builder_id": null,
            "source": null,
            "user_id": null,
            "start_price": null,
            "end_price": null,
            "locations": null,
            "bhks": null,
            "prop_types": null
        },
        "status": "2"
    }],
    "meta": {
        "status": 200,
        "message": "",
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

Fetch Lead Based On Date
========

Route
------

* `POST ​http://housingman.com/api/fetch_leads?token=xresedr&date=2016-07-25` fetch the user leads.

Headers
-------

* `Accept: application/json`
* `Content-Type: application/json`

Example
-------

Request
-------

* `POST ​http://housingman.com/api/fetch_leads?token=xresedr&date=2016-07-25` fetch the user leads.


Body
----

Response
--------

```json
{
    "data": [{
        "lead": {
            "id": 44,
            "name": "Prashanth ",
            "email": "prashanth@housingman.com",
            "mobile": "9786848278",
            "project_id": 435,
            "created_at": "2015-12-28T13:43:40.369+05:30",
            "updated_at": "2015-12-28T13:43:40.369+05:30",
            "enquiry_type": null,
            "builder_id": null,
            "source": null,
            "user_id": null,
            "start_price": null,
            "end_price": null,
            "locations": null,
            "bhks": null,
            "prop_types": null
        },
        "status": "2"
    }],
    "meta": {
        "status": 200,
        "message": "",
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

Lead Show
Route
------

* `POST ​http://housingman.com/api/leads/1?token=xresedr` fetch the user leads.

Headers
-------

* `Accept: application/json`
* `Content-Type: application/json`

Example
-------

Request
-------

* `POST ​http://housingman.com/api/leads/1?token=xresedr` fetch the user leads.


Body
----

Response
--------

```json
{
    "data": [{
        "name": "Super Admin",
        "email": "admin@housingman.com",
        "mobile": "9677018354",
        "start_price": null,
        "end_price": null,
        "locations": null,
        "bhks": null,
        "prop_types": null,
        "project": {
            "id": 111,
            "builder_id": 226,
            "city_id": 1,
            "locality_id": 152,
            "meta_title": "",
            "meta_description": "",
            "meta_keywords": null,
            "name": "Maratt Pimento",
            "label": "Maratt Pimento",
            "permalink": "maratt-pimento",
            "total_no_of_units": 43,
            "description": "Pimento by Maratt, is an aesthetically designed, 25-level tower. Surrounded by over an acre of landscape, this exclusive development houses just 44 condovillas, each with a floor plate of over 4,000 square feet.\r\n\r\nConveniently located at J.P.Nagar, a prime locality in South Bangalore and opposite the upcoming Vega City mall, Pimento is a mere 6.5km from Mahatma Gandhi Road.",
            "address": "Maratt Estate, Bannerghatta Main Road, J.P. Nagar 4th Phase, Bangalore",
            "architect": "",
            "enabled": true,
            "project_image_file_name": "Maratt_Pimento-Thumbnail.jpg",
            "project_image_content_type": "image/jpeg",
            "project_image_file_size": 65829,
            "project_image_updated_at": "2015-11-28T17:26:05.822+05:30",
            "banner_image_file_name": "Maratt_Pimento_-Banner.jpg",
            "banner_image_content_type": "image/jpeg",
            "banner_image_file_size": 112605,
            "banner_image_updated_at": "2015-11-28T17:26:05.871+05:30",
            "created_at": "2015-11-04T14:48:34.999+05:30",
            "updated_at": "2015-12-10T19:26:55.678+05:30",
            "video_url": "https://www.youtube.com/watch?v=BGrz8Or0-Eo",
            "e_brochure_file_name": null,
            "e_brochure_content_type": null,
            "e_brochure_file_size": null,
            "e_brochure_updated_at": null,
            "latitude": null,
            "longitude": null,
            "price_on_request": false,
            "sold_out": false,
            "issuu_id": null,
            "seo_permalink": null,
            "user_id": null,
            "property_type": null,
            "project_tile_image_file_name": null,
            "project_tile_image_content_type": null,
            "project_tile_image_file_size": null,
            "project_tile_image_updated_at": null,
            "banner_image2_file_name": null,
            "banner_image2_content_type": null,
            "banner_image2_file_size": null,
            "banner_image2_updated_at": null,
            "banner_image3_file_name": null,
            "banner_image3_content_type": null,
            "banner_image3_file_size": null,
            "banner_image3_updated_at": null,
            "is_builder_verified": false
        }
    }],
    "meta": {
        "status": 200,
        "message": "",
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
