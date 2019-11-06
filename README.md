# Vietnam Location json file


[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Json files

  - cities.json
  - districts.json
  - wards.json

# Features!

  - City object structure (key base on code field)
    ```json
        {
            "name": "An Giang",
            "slug": "an-giang",
            "type": "tinh",
            "name_with_type": "Tỉnh An Giang",
            "code": "89"
        }
    ```
  - District object structure (key base on code field, city reference base on parent_code field )
    ```json
        {
           "name": "Ia H Drai",
           "type": "huyen",
           "slug": "ia-h-drai",
           "name_with_type": "Huyện Ia H Drai",
           "path": "Ia H Drai, Kon Tum",
           "path_with_type": "Huyện Ia H Drai, Tỉnh Kon Tum",
           "code": "618",
           "parent_code": "62"
        }
    ```
  - Ward object structure(key base on code field, districty reference base on parent_code field)
    ```json
        {
            "name": "Đổng Xá",
            "type": "xa",
            "slug": "dong-xa",
            "name_with_type": "Xã Đổng Xá",
            "path": "Đổng Xá, Na Rì, Bắc Kạn",
            "path_with_type": "Xã Đổng Xá, Huyện Na Rì, Tỉnh Bắc Kạn",
            "code": "02194",
            "parent_code": "066"
        }
    ```

**Free files, Hell Yeah!**

