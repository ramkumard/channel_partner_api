Search Project
========

Route
------

* `POST ​http://housingman.com/api/projects/search` fetch the projects.

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
{
   "keywords":"",
   "search_filter":{
      "price_range_any":[
         "2000000",
         "4000000"
      ],
      "bhk_range_any":[
         "2"
      ],
      "discount_range_any":[
         "0..200000",
         "200000..300000"
      ],
      "number_of_toilet_range_any":[
         "1"
      ]
   },
   "token":"axers",
   "page":"1"
}

Response
--------

```json
{
   "projects":[
      {
         "id":436,
         "label":"Definer Hi - Life",
         "permalink":"definer-hi-life",
         "total_no_of_units":224,
         "description":"Definer Group Hi Life Bangalore offers 2 and 3 BHK apartments to buyers that are sized between 926 and 1709 sq ft on an average. The project consists of 224 units and spreads over an area of 2.65 acres in all. Key amenities offered to residents at this project include a well equipped gymnasium, sports facilities, swimming pool, cafeteria, playing zone for kids, intercom facilities, rainwater harvesting system, jogging track, landscaped gardens, power backup facilities, car parking facilities, 24 hour security services, sewage treatment plant, piped gas connections, sauna, video surveillance, cricket pitch, amphitheatre, skating rink, sand pit and more. The project is located at Ramamurthy Nagar and offers great connectivity to several areas in Bangalore.",
         "address":"T.C. Palya Main Road, Bangalore",
         "image":"https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/projects/project_images/436/original/Definer-Hi-Life-thumbnail.jpg?1449643105",
         "end_date":"2017-06-01",
         "bhk":[
            "2 BHK",
            "3 BHK"
         ],
         "min_area_in_sqft":"1196.0",
         "max_area_in_sqft":"926.0",
         "price":3324340.0,
         "status":"On Launch",
         "project_plan":[

         ],
         "master_plan":[

         ],
         "exterior":[

         ],
         "interior":[

         ],
         "builder":{
            "id":89,
            "name":"Definer Ventures",
            "builder_logo":"https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/builders/builder_logos/89/original/Definer_Ventures.jpg?1448690554",
            "email":"rv@definer.in",
            "phone":"8023611333",
            "address":"First Floor, Achaiah Chetty Arcade, No:19, 1st cross, Achaiah Chetty Layout , RMV Extension, Sadashiv Nagar, Bangalore – 560 080First Floor, Achaiah Chetty Arcade, No:19, 1st cross, Achaiah Chetty Layout , RMV Extension, Sadashiv Nagar, Bangalore – 560 080"
         },
         "amenities":[
            [
               "24 X 7 Security",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/2/thumb/Security_B.png?1446725602"
            ],
            [
               "Cafeteria",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/4/thumb/Cafeteria.png?1446725620"
            ],
            [
               "Car Parking",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/5/thumb/Parking.png?1446725654"
            ],
            [
               "Children's play area",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/6/thumb/ChildrenPlayArea.png?1446725662"
            ],
            [
               "Club House",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/7/thumb/Clubhouse_A.png?1446725671"
            ],
            [
               "Gymnasium",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/9/thumb/Gym.png?1446725728"
            ],
            [
               "Intercom",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/11/thumb/Intercomm.png?1446725806"
            ],
            [
               "Jogging Track",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/21/thumb/JoggingTrack.png?1446726118"
            ],
            [
               "Landscaped Gardens",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/12/thumb/LandScapedGardens.png?1446725850"
            ],
            [
               "Power Backup",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/15/thumb/PowerBackup.png?1446725967"
            ],
            [
               "Rain Water Harvesting",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/16/thumb/RainWaterHarvesting.png?1446725989"
            ],
            [
               "Sports Facility",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/17/thumb/SportsFacility.png?1446726024"
            ],
            [
               "\tSwimming Pool",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/18/thumb/SwimmingPool.png?1446726038"
            ]
         ]
      },
      {
         "id":437,
         "label":"Definer Kingdom",
         "permalink":"definer-kingdom",
         "total_no_of_units":192,
         "description":"Definer Group Kingdom Bangalore is a novel project that offers 2 and 3 BHK apartments and consists of 232 units in all. Average home sizes range between 802 and 1697 sq. ft. at this project and it spreads over 3 acres of land. Key amenities offered to buyers at this project include a well-equipped gymnasium, intercom facilities, multipurpose room, swimming pool, power backup facilities, playing area for kids, rainwater harvesting system, jogging track, landscaped gardens, spa, guest rooms, pool tables and party hall. Located at Budigere Cross, the project is well linked to several areas like Jalahalli, Chikballapur, Brookefield, Vasanth Nagar, Frazer Town, JP Nagar Phase 7, Bommasandra, Varthur, Jakkur and Begur among others.",
         "address":"Opp. Old Madras Road, Near Budigere Cross, Bangalore",
         "image":"https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/projects/project_images/437/original/Definer-Kingdom-Thumbnail.jpg?1449643162",
         "end_date":"2017-12-01",
         "bhk":[
            "2 BHK",
            "3 BHK"
         ],
         "min_area_in_sqft":"1160.0",
         "max_area_in_sqft":"940.0",
         "price":2397980.0,
         "status":"On Launch",
         "project_plan":[

         ],
         "master_plan":[

         ],
         "exterior":[

         ],
         "interior":[

         ],
         "builder":{
            "id":89,
            "name":"Definer Ventures",
            "builder_logo":"https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/builders/builder_logos/89/original/Definer_Ventures.jpg?1448690554",
            "email":"rv@definer.in",
            "phone":"8023611333",
            "address":"First Floor, Achaiah Chetty Arcade, No:19, 1st cross, Achaiah Chetty Layout , RMV Extension, Sadashiv Nagar, Bangalore – 560 080First Floor, Achaiah Chetty Arcade, No:19, 1st cross, Achaiah Chetty Layout , RMV Extension, Sadashiv Nagar, Bangalore – 560 080"
         },
         "amenities":[
            [
               "24 X 7 Security",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/2/thumb/Security_B.png?1446725602"
            ],
            [
               "Car Parking",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/5/thumb/Parking.png?1446725654"
            ],
            [
               "Children's play area",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/6/thumb/ChildrenPlayArea.png?1446725662"
            ],
            [
               "Club House",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/7/thumb/Clubhouse_A.png?1446725671"
            ],
            [
               "Gymnasium",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/9/thumb/Gym.png?1446725728"
            ],
            [
               "Intercom",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/11/thumb/Intercomm.png?1446725806"
            ],
            [
               "Jogging Track",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/21/thumb/JoggingTrack.png?1446726118"
            ],
            [
               "Landscaped Gardens",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/12/thumb/LandScapedGardens.png?1446725850"
            ],
            [
               "Multipurpose Room",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/14/thumb/MultipurposeHall_B.png?1446725949"
            ],
            [
               "Power Backup",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/15/thumb/PowerBackup.png?1446725967"
            ],
            [
               "Rain Water Harvesting",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/16/thumb/RainWaterHarvesting.png?1446725989"
            ],
            [
               "\tSwimming Pool",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/18/thumb/SwimmingPool.png?1446726038"
            ]
         ]
      },
      {
         "id":525,
         "label":"Habitat Iluminar",
         "permalink":"habitat-iluminar",
         "total_no_of_units":412,
         "description":"",
         "address":"Mysore Road,Bangalore",
         "image":"https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/projects/project_images/525/original/Habitat-Iluminar-Thumbnail.jpg?1450447088",
         "end_date":"2018-08-01",
         "bhk":[
            "2 BHK",
            "3 BHK"
         ],
         "min_area_in_sqft":"1040.0",
         "max_area_in_sqft":"970.0",
         "price":3710250.0,
         "status":"On Launch",
         "project_plan":[

         ],
         "master_plan":[

         ],
         "exterior":[

         ],
         "interior":[

         ],
         "builder":{
            "id":175,
            "name":"Habitat Ventures",
            "builder_logo":"https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/builders/builder_logos/175/original/HVP_Realty_Pvt._Ltd..jpg?1448692413",
            "email":"info@habitatventures.com",
            "phone":"8041469220",
            "address":"#26, Shankarmutt Road,\r\nBasavangudi,\r\nBangalore - 560 004"
         },
         "amenities":[
            [
               "24 X 7 Security",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/2/thumb/Security_B.png?1446725602"
            ],
            [
               "Cafeteria",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/4/thumb/Cafeteria.png?1446725620"
            ],
            [
               "Car Parking",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/5/thumb/Parking.png?1446725654"
            ],
            [
               "Children's play area",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/6/thumb/ChildrenPlayArea.png?1446725662"
            ],
            [
               "Club House",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/7/thumb/Clubhouse_A.png?1446725671"
            ],
            [
               "Golf Course",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/8/thumb/GolfCourse.png?1446725679"
            ],
            [
               "Gymnasium",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/9/thumb/Gym.png?1446725728"
            ],
            [
               "Indoor Games",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/10/thumb/IndoorGames.png?1446725755"
            ],
            [
               "Intercom",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/11/thumb/Intercomm.png?1446725806"
            ],
            [
               "Jogging Track",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/21/thumb/JoggingTrack.png?1446726118"
            ],
            [
               "Landscaped Gardens",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/12/thumb/LandScapedGardens.png?1446725850"
            ],
            [
               "Power Backup",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/15/thumb/PowerBackup.png?1446725967"
            ],
            [
               "Sports Facility",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/17/thumb/SportsFacility.png?1446726024"
            ],
            [
               "\tSwimming Pool",
               "https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/amenities/amenity_logos/18/thumb/SwimmingPool.png?1446726038"
            ]
         ]
      }
   ],
   "filters":[
      {
         "price_range":{
            "name":"price",
            "scope":"price_range_any",
            "conds":{
               "0 - 50L":"0..5000000",
               "50L - 1Cr":"5000000..10000000"
            },
            "type":"checkbox",
            "labels":[
               [
                  "0 - 50L",
                  "0..5000000"
               ],
               [
                  "50L - 1Cr",
                  "5000000..10000000"
               ]
            ]
         }
      },
      {
         "discount_range":{
            "name":"discount",
            "scope":"discount_range_any",
            "conds":{
               "0 - 2L":"0..200000",
               "2L - 3L":"200000..300000",
               "3L - 4L":"300000..400000",
               "4L - 5L":"400000..500000"
            },
            "type":"checkbox",
            "labels":[
               [
                  "0 - 2L",
                  "0..200000"
               ],
               [
                  "2L - 3L",
                  "200000..300000"
               ],
               [
                  "3L - 4L",
                  "300000..400000"
               ],
               [
                  "4L - 5L",
                  "400000..500000"
               ]
            ]
         }
      },
      {
         "bhk_range":{
            "name":"bhk",
            "scope":"bhk_range_any",
            "conds":[
               "2",
               "1",
               "3"
            ],
            "type":"checkbox",
            "labels":[
               [
                  "2",
                  "2"
               ],
               [
                  "1",
                  "1"
               ],
               [
                  "3",
                  "3"
               ]
            ]
         }
      },
      {
         "number_of_toilet_range":{
            "name":"number_of_toilet",
            "scope":"number_of_toilet_range_any",
            "conds":[
               2,
               1,
               3
            ],
            "type":"checkbox",
            "labels":[
               [
                  2,
                  2
               ],
               [
                  1,
                  1
               ],
               [
                  3,
                  3
               ]
            ]
         }
      },
      {
         "max_possession_range":{
            "name":"max_possession",
            "scope":"max_possession_range_any",
            "conds":[

            ],
            "type":"checkbox",
            "labels":[

            ]
         }
      }
   ]
}
```


Project Show
Route
------

* `GET ​http://housingman.com/api/projects/golden-gate-orchids?token=xresedr` fetch the user project.

Headers
-------

* `Accept: application/json`
* `Content-Type: application/json`

Example
-------

Request
-------

* `POST ​http://housingman.com/api/projects/:permalink?token=xresedr` fetch the user project.


Body
----

Response
--------

```json
{
   "data":[
      {
         "id":537,
         "label":"Golden Gate Orchids",
         "permalink":"golden-gate-orchids",
         "total_no_of_units":167,
         "description":"Orchids reflects a very unique design and concept that truly helps life bloom in all its splendor. Designed to be a green,smart and visually appealing residential space that will be home to 167 luxury apartments, it will also be an IGBC Gold rated Green project offering 2,3,4 BHK apartments and Pent house options. A very expansive, feature rich Club house will make Orchids a sought after residential abode for the discerning few.\r\n\r\nThe spacious, open-plan apartments with large floor to lintel height corner windows, facing planted verandahs differentiate Orchids from other regular offerings, allowing unhindered views and generous light and air to the residents.\r\n\r\nThe park that runs the entire length of site, allowing tall tree planting forms a green reserve and buffer from the upcoming busy road. There is also a promenade that will be developed, linking the 3 access cores of the three blocks and guiding the user from the main reception lobby, offering a constant view of this front park. A variety of enclosed, open and semi-open recreational spaces will form points of interest along this path.",
         "address":"Thanisandra Main Road, Near Diana College, Chokkanahalli Village, Bangalore",
         "image":"https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/projects/project_images/537/original/Prisha-Orchids-Thumbnail.jpg?1450437732",
         "end_date":"2016-06-01",
         "bhk":[

         ],
         "min_area_in_sqft":null,
         "max_area_in_sqft":null,
         "price":null,
         "status":"On Launch",
         "project_plan":[

         ],
         "master_plan":[

         ],
         "exterior":[

         ],
         "interior":[

         ],
         "builder":{
            "id":154,
            "name":"Golden Gate Properties",
            "builder_logo":"https://s3-ap-southeast-1.amazonaws.com/s3local-bucket/builders/builder_logos/154/original/Golden_Gate_Properties_Ltd..jpg?1448692243",
            "email":"info@ggproperties.com",
            "phone":"7676460002",
            "address":"Golden House, #820, 80 Feet Road,\r\n8th Block, Koramangala,\r\nBangalore - 560 095"
         },
         "amenities":[

         ]
      }
   ],
   "meta":{
      "status":200,
      "message":"",
      "page_info":{
         "current_page":1,
         "prev_page":null,
         "next_page":null,
         "total_pages":1,
         "total":1,
         "per_page":10
      }
   }
}
```

Search Auto Complete
========

Route
------

* `GET ​http://housingman.com/api/projects/search_auto?token=xresedr&term=B` search the projects.

Headers
-------

* `Accept: application/json`
* `Content-Type: application/json`

Example
-------

Request
-------

* `GET ​http://housingman.com/api/projects/search_auto?token=xresedr&term=B` search the projects.


Body
----
```json

```

Response
--------

```json
{
   "data":[
      {
         "options":{
            "options":[
               {
                  "label":"Bangalore",
                  "category":"City"
               },
               {
                  "label":"Nambiar Urban Spaces",
                  "category":"Project"
               },
               {
                  "label":"Brigade Caladium ",
                  "category":"Project"
               },
               {
                  "label":"Nitesh British Columbia",
                  "category":"Project"
               },
               {
                  "label":"Brigade Omega ",
                  "category":"Project"
               },
               {
                  "label":"Chartered Hummingbird ",
                  "category":"Project"
               },
               {
                  "label":"Sobha Valley View",
                  "category":"Project"
               },
               {
                  "label":"MBR Scapple",
                  "category":"Project"
               },
               {
                  "label":"Sobha Morzaria Grandeur",
                  "category":"Project"
               },
               {
                  "label":"Century Breeze",
                  "category":"Project"
               },
               {
                  "label":"Pashmina Brookwoods",
                  "category":"Project"
               },
               {
                  "label":"Krishna Aquabay",
                  "category":"Project"
               },
               {
                  "label":"VBHC Vaibhava",
                  "category":"Project"
               },
               {
                  "label":"Embassy Oasis",
                  "category":"Project"
               },
               {
                  "label":"Redifice Urban Oasis",
                  "category":"Project"
               },
               {
                  "label":"Embassy Lake Terraces",
                  "category":"Project"
               },
               {
                  "label":"Ozone Urbana Aura",
                  "category":"Project"
               },
               {
                  "label":"Ozone Urbana Avenue",
                  "category":"Project"
               },
               {
                  "label":"Sobha Lifestyle Legacy",
                  "category":"Project"
               },
               {
                  "label":"Hoysala Habitat",
                  "category":"Project"
               },
               {
                  "label":"Prestige Garden Bay ",
                  "category":"Project"
               },
               {
                  "label":" Embassy Grove",
                  "category":"Project"
               },
               {
                  "label":"Esteem Emblem",
                  "category":"Project"
               },
               {
                  "label":"SNN Raj Greenbay ",
                  "category":"Project"
               },
               {
                  "label":"Bren Edgewaters ",
                  "category":"Project"
               },
               {
                  "label":"RBD Stillwaters Apartments",
                  "category":"Project"
               },
               {
                  "label":"RBD Stillwaters Villa",
                  "category":"Project"
               },
               {
                  "label":"Arun Kaustubha",
                  "category":"Project"
               },
               {
                  "label":"Shriram Hebbal One",
                  "category":"Project"
               },
               {
                  "label":"Mantri Webcity",
                  "category":"Project"
               },
               {
                  "label":"Nitesh Melbourne Park ",
                  "category":"Project"
               },
               {
                  "label":"Chitrakut Amber",
                  "category":"Project"
               },
               {
                  "label":"Kolte Mirabilis",
                  "category":"Project"
               },
               {
                  "label":"Sobha Silicon Oasis",
                  "category":"Project"
               },
               {
                  "label":"Bren Woods ",
                  "category":"Project"
               },
               {
                  "label":"LGCL Pueblo",
                  "category":"Project"
               },
               {
                  "label":"Unishire Belvedere Premia",
                  "category":"Project"
               },
               {
                  "label":"Radiant Silver Bell 2",
                  "category":"Project"
               },
               {
                  "label":"Bren Paddington ",
                  "category":"Project"
               },
               {
                  "label":"Blue Valley Sunshine",
                  "category":"Project"
               },
               {
                  "label":"Prestige Brooklyn Heights ",
                  "category":"Project"
               },
               {
                  "label":"Atlantis Liberty Square ",
                  "category":"Project"
               },
               {
                  "label":"HM Nimbus",
                  "category":"Project"
               },
               {
                  "label":"Rainbow Kishore Glendale",
                  "category":"Project"
               },
               {
                  "label":"Sobha The Park \u0026 The Plaza",
                  "category":"Project"
               },
               {
                  "label":"Mantri Global heights",
                  "category":"Project"
               },
               {
                  "label":"Ozone Urbana Alcove",
                  "category":"Project"
               },
               {
                  "label":"Ozone Urbana Aqua",
                  "category":"Project"
               },
               {
                  "label":"Ozone Urbana Irene",
                  "category":"Project"
               },
               {
                  "label":"Sobha Halcyon",
                  "category":"Project"
               },
               {
                  "label":"VBHC Serene Town",
                  "category":"Project"
               },
               {
                  "label":"Prestige Bagamane Temple Bells",
                  "category":"Project"
               },
               {
                  "label":"VBHC Palmhaven",
                  "category":"Project"
               },
               {
                  "label":"Zaffars Sterling Dewberries",
                  "category":"Project"
               },
               {
                  "label":"Brigade North Ridge",
                  "category":"Project"
               },
               {
                  "label":"Brigade Altamont",
                  "category":"Project"
               },
               {
                  "label":"Purva Palm Beach",
                  "category":"Project"
               },
               {
                  "label":"Bren Palms",
                  "category":"Project"
               },
               {
                  "label":"RJ Brooke Square",
                  "category":"Project"
               },
               {
                  "label":"Mantri Blossom",
                  "category":"Project"
               },
               {
                  "label":"Brigade Cosmopolis",
                  "category":"Project"
               },
               {
                  "label":"Brigade Panorama ",
                  "category":"Project"
               },
               {
                  "label":"GR Brundavan",
                  "category":"Project"
               },
               {
                  "label":"Habitat Iluminar",
                  "category":"Project"
               },
               {
                  "label":"Sobha Palladian",
                  "category":"Project"
               },
               {
                  "label":"Bren StarLight ",
                  "category":"Project"
               },
               {
                  "label":"Brigade Exotica",
                  "category":"Project"
               },
               {
                  "label":"Bairavi Cruz Luxor",
                  "category":"Project"
               },
               {
                  "label":"KMB La Palazzo",
                  "category":"Project"
               },
               {
                  "label":"Phoenix One Banglore West ",
                  "category":"Project"
               },
               {
                  "label":"Sobha Indraprastha",
                  "category":"Project"
               },
               {
                  "label":"Sukritha Buildmann Aaroha Villa",
                  "category":"Project"
               },
               {
                  "label":"Azven Breathe",
                  "category":"Project"
               },
               {
                  "label":"Suraj Trinity Bloom",
                  "category":"Project"
               },
               {
                  "label":"Bren Imperia",
                  "category":"Project"
               },
               {
                  "label":"Concorde Amber",
                  "category":"Project"
               },
               {
                  "label":"Mana Uber Verdant",
                  "category":"Project"
               },
               {
                  "label":"Surbacon Krishna Lilac",
                  "category":"Project"
               },
               {
                  "label":"Surbacon Maple",
                  "category":"Project"
               },
               {
                  "label":"Bhartiya Leela Residences",
                  "category":"Project"
               },
               {
                  "label":"Bhartiya Nikoo Homes 2",
                  "category":"Project"
               },
               {
                  "label":"Vaswani Brentwood",
                  "category":"Project"
               },
               {
                  "label":"Sobha Clovelly",
                  "category":"Project"
               },
               {
                  "label":"Lakeside Habitat Appartments ",
                  "category":"Project"
               },
               {
                  "label":"Sobha Dream Acres",
                  "category":"Project"
               },
               {
                  "label":"UKN Belvista",
                  "category":"Project"
               },
               {
                  "label":"VDB Azure",
                  "category":"Project"
               },
               {
                  "label":"Nitesh Knightsbridge",
                  "category":"Project"
               },
               {
                  "label":"Ajmal / Prestige Mayberry",
                  "category":"Project"
               },
               {
                  "label":"Brigade Lake Front ",
                  "category":"Project"
               },
               {
                  "label":"Prestige Bougainvillea - Platinum",
                  "category":"Project"
               },
               {
                  "label":"Sumadhura Lake Breeze",
                  "category":"Project"
               },
               {
                  "label":"VDB Nusa Dua Chromatic",
                  "category":"Project"
               },
               {
                  "label":"VDB Willow Farm",
                  "category":"Project"
               },
               {
                  "label":"VDB Willow Farm Villa",
                  "category":"Project"
               },
               {
                  "label":"Divya Sree Republic Of Whitefield",
                  "category":"Project"
               },
               {
                  "label":"Nitesh Columbus Square",
                  "category":"Project"
               },
               {
                  "label":"Krishna Brighton",
                  "category":"Project"
               },
               {
                  "label":"Bagaluru",
                  "category":"Locality"
               },
               {
                  "label":"Banasankari",
                  "category":"Locality"
               },
               {
                  "label":"Bannerghatta",
                  "category":"Locality"
               },
               {
                  "label":"Bannerghatta Road",
                  "category":"Locality"
               },
               {
                  "label":"Basapura",
                  "category":"Locality"
               },
               {
                  "label":"Basavanagar",
                  "category":"Locality"
               },
               {
                  "label":"Basavanagudi",
                  "category":"Locality"
               },
               {
                  "label":"Basaveshwara Nagar",
                  "category":"Locality"
               },
               {
                  "label":"Battarahalli",
                  "category":"Locality"
               },
               {
                  "label":"Begur",
                  "category":"Locality"
               },
               {
                  "label":"Begur Road",
                  "category":"Locality"
               },
               {
                  "label":"Bellandur",
                  "category":"Locality"
               },
               {
                  "label":"Bellary Road",
                  "category":"Locality"
               },
               {
                  "label":"Bidrahalli",
                  "category":"Locality"
               },
               {
                  "label":"Bommanahalli",
                  "category":"Locality"
               },
               {
                  "label":"Bommasandra",
                  "category":"Locality"
               },
               {
                  "label":"Bommenahalli",
                  "category":"Locality"
               },
               {
                  "label":"Chikbanavara",
                  "category":"Locality"
               },
               {
                  "label":"Chikkaballapur",
                  "category":"Locality"
               },
               {
                  "label":"Doddaballapur",
                  "category":"Locality"
               },
               {
                  "label":"Doddaballapur Road",
                  "category":"Locality"
               },
               {
                  "label":"Hebbal",
                  "category":"Locality"
               },
               {
                  "label":"HRBR Layout",
                  "category":"Locality"
               },
               {
                  "label":"Jeevanbheema Nagar",
                  "category":"Locality"
               },
               {
                  "label":"Lal bagh",
                  "category":"Locality"
               },
               {
                  "label":"Sarjapur Attibele Road",
                  "category":"Locality"
               },
               {
                  "label":"Thubarahalli",
                  "category":"Locality"
               },
               {
                  "label":"Nambiar Builders",
                  "category":"Developer"
               },
               {
                  "label":"Brigade Group",
                  "category":"Developer"
               },
               {
                  "label":"SNN Builders",
                  "category":"Developer"
               },
               {
                  "label":"Sobha Developers",
                  "category":"Developer"
               },
               {
                  "label":"MBR Homes",
                  "category":"Developer"
               },
               {
                  "label":"Total Environment Building Systems",
                  "category":"Developer"
               },
               {
                  "label":"Pashmina Builders \u0026 Developers",
                  "category":"Developer"
               },
               {
                  "label":"Nisarga Builders",
                  "category":"Developer"
               },
               {
                  "label":"Value \u0026 Budget Housing Corporation",
                  "category":"Developer"
               },
               {
                  "label":"Embassy Property Development",
                  "category":"Developer"
               },
               {
                  "label":"Veracious Builders \u0026 Developers",
                  "category":"Developer"
               },
               {
                  "label":"Vishwas Bawa Builders \u0026 Developers",
                  "category":"Developer"
               },
               {
                  "label":"Bren Corporation",
                  "category":"Developer"
               },
               {
                  "label":"RBD Shelters",
                  "category":"Developer"
               },
               {
                  "label":"Regal Urban",
                  "category":"Developer"
               },
               {
                  "label":"Chitrakut Builders \u0026 Developers",
                  "category":"Developer"
               },
               {
                  "label":"Blue Valley Properties",
                  "category":"Developer"
               },
               {
                  "label":"Atlantis Builders",
                  "category":"Developer"
               },
               {
                  "label":"Rainbow Properties",
                  "category":"Developer"
               },
               {
                  "label":"SGR Buildtech",
                  "category":"Developer"
               },
               {
                  "label":"RJ Builders",
                  "category":"Developer"
               },
               {
                  "label":"Habitat Ventures",
                  "category":"Developer"
               },
               {
                  "label":"Bairavi Properties \u0026 Construction",
                  "category":"Developer"
               },
               {
                  "label":"KMB Estates",
                  "category":"Developer"
               },
               {
                  "label":"NCC Urban Infrastructure",
                  "category":"Developer"
               },
               {
                  "label":"Sukritha Buildmann",
                  "category":"Developer"
               },
               {
                  "label":"Ahad Builders ",
                  "category":"Developer"
               },
               {
                  "label":"Astro Builders \u0026 Developers",
                  "category":"Developer"
               },
               {
                  "label":"Surbacon Development",
                  "category":"Developer"
               },
               {
                  "label":"Bhartiya City Developers",
                  "category":"Developer"
               },
               {
                  "label":"Value DesignBuild",
                  "category":"Developer"
               },
               {
                  "label":"Vishnu Priya Group of Builders \u0026 Developers",
                  "category":"Developer"
               },
               {
                  "label":"Gajanana Buildtech",
                  "category":"Developer"
               },
               {
                  "label":"Aditya Builders \u0026 Developers",
                  "category":"Developer"
               },
               {
                  "label":"Manito Builders",
                  "category":"Developer"
               },
               {
                  "label":"Zed Builders Corporation",
                  "category":"Developer"
               }
            ],
            "status":200
         }
      }
   ],
   "meta":{
      "status":200,
      "message":"",
      "page_info":{
         "current_page":1,
         "prev_page":null,
         "next_page":null,
         "total_pages":1,
         "total":1,
         "per_page":10
      }
   }
}
```