# Free-vietnam-location-json

This is the free json file free location in viet nam

cities.js
district.js
wards.js

Object Structure
city:
    {
       "name": "An Giang",
        "slug": "an-giang",
        "type": "tinh",
        "name_with_type": "Tỉnh An Giang",
        "code": "89"
    }

district:
        {
           "name":"Chợ Đồn",
           "type":"huyen",
           "slug":"cho-don",
           "name_with_type":"Huyện Chợ Đồn",
           "path":"Chợ Đồn, Bắc Kạn",
           "path_with_type":"Huyện Chợ Đồn, Tỉnh Bắc Kạn",
           "code":"064",
           "parent_code":"06"
        }
"parent_code" of district object base on the "code" of city object
ward: 
    {
       "name": "Liêm Thuỷ",
        "type": "xa",
        "slug": "liem-thuy",
        "name_with_type": "Xã Liêm Thuỷ",
        "path": "Liêm Thuỷ, Na Rì, Bắc Kạn",
        "path_with_type": "Xã Liêm Thuỷ, Huyện Na Rì, Tỉnh Bắc Kạn",
        "code": "02197",
        "parent_code": "066"
    }
"parent_code" of ward object base on the "code" of district object
