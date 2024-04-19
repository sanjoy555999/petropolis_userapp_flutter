## 1. 200 GET /api/v1/config
 
**Model**
 
Paste you model hear
 
<details>
 
<summary>Example</summary>
 
```json
{
     "brand_setting": "1",
     "digital_product_setting": "1",
     "system_default_currency": 3,
     "digital_payment": true,
     "cash_on_delivery": true,
     "seller_registration": "1",
     "pos_active": "0",
     "company_phone": "000000000",
     "company_email": "Copy@6amtech.com",
     "company_logo": "https://store.petropolis.in/storage/app/public/company/2021-05-25-60ad1b313a9d4.png",
     "company_cover_image": "https://store.petropolis.in/storage/app/public/logo/",
     "company_name": "Petropolis",
     "company_fav_icon": "https://store.petropolis.in/storage/app/public/company/2021-03-02-603df1634614f.png",
     "delivery_country_restriction": null,
     "delivery_zip_code_area_restriction": 1,
     "base_urls": {
          "product_image_url": "https://store.petropolis.in/storage/app/public/product",
          "product_thumbnail_url": "https://store.petropolis.in/storage/app/public/product/thumbnail",
          "digital_product_url": "https://store.petropolis.in/storage/app/public/product/digital-product",
          "brand_image_url": "https://store.petropolis.in/storage/app/public/brand",
          "customer_image_url": "https://store.petropolis.in/storage/app/public/profile",
          "banner_image_url": "https://store.petropolis.in/storage/app/public/banner",
          "category_image_url": "https://store.petropolis.in/storage/app/public/category",
          "review_image_url": "https://store.petropolis.in/storage/app/public",
          "seller_image_url": "https://store.petropolis.in/storage/app/public/seller",
          "shop_image_url": "https://store.petropolis.in/storage/app/public/shop",
          "notification_image_url": "https://store.petropolis.in/storage/app/public/notification",
          "delivery_man_image_url": "https://store.petropolis.in/storage/app/public/delivery-man",
          "support_ticket_image_url": "https://store.petropolis.in/storage/app/public/support-ticket",
          "chatting_image_url": "https://store.petropolis.in/storage/app/public/chatting"
     },
     "static_urls": {
          "contact_us": "https://store.petropolis.in/contacts",
          "brands": "https://store.petropolis.in/brands",
          "categories": "https://store.petropolis.in/categories",
          "customer_account": "https://store.petropolis.in/user-account"
     },
     "about_us": "<p>this is about us page. hello and hi from about page description..</p>",
     "privacy_policy": "<p>my privacy policy</p>\r\n\r\n<p>&nbsp;</p>",
     "faq": [],
     "terms_&_conditions": "<p>terms and conditions</p>",
     "refund_policy": {
          "status": 1,
          "content": ""
     },
     "return_policy": {
          "status": 1,
          "content": ""
     },
     "cancellation_policy": {
          "status": 1,
          "content": ""
     },
     "currency_list": [
          {
               "id": 1,
               "name": "USD",
               "symbol": "$",
               "code": "USD",
               "exchange_rate": "1",
               "status": true,
               "created_at": null,
               "updated_at": "2021-06-27T13:39:37.000000Z"
          },
          {
               "id": 2,
               "name": "BDT",
               "symbol": "৳",
               "code": "BDT",
               "exchange_rate": "84",
               "status": true,
               "created_at": null,
               "updated_at": "2021-07-06T11:52:58.000000Z"
          },
          {
               "id": 3,
               "name": "Indian Rupee",
               "symbol": "₹",
               "code": "INR",
               "exchange_rate": "1",
               "status": true,
               "created_at": "2020-10-15T17:23:04.000000Z",
               "updated_at": "2024-04-04T14:19:05.000000Z"
          },
          {
               "id": 4,
               "name": "Euro",
               "symbol": "€",
               "code": "EUR",
               "exchange_rate": "100",
               "status": true,
               "created_at": "2021-05-25T21:00:23.000000Z",
               "updated_at": "2021-06-04T18:25:29.000000Z"
          },
          {
               "id": 5,
               "name": "YEN",
               "symbol": "¥",
               "code": "JPY",
               "exchange_rate": "110",
               "status": true,
               "created_at": "2021-06-10T22:08:31.000000Z",
               "updated_at": "2021-06-26T14:21:10.000000Z"
          },
          {
               "id": 6,
               "name": "Ringgit",
               "symbol": "RM",
               "code": "MYR",
               "exchange_rate": "4.16",
               "status": true,
               "created_at": "2021-07-03T11:08:33.000000Z",
               "updated_at": "2021-07-03T11:10:37.000000Z"
          },
          {
               "id": 7,
               "name": "Rand",
               "symbol": "R",
               "code": "ZAR",
               "exchange_rate": "14.26",
               "status": true,
               "created_at": "2021-07-03T11:12:38.000000Z",
               "updated_at": "2021-07-03T11:12:42.000000Z"
          }
     ],
     "currency_symbol_position": "left",
     "business_mode": "multi",
     "maintenance_mode": false,
     "language": [
          {
               "code": "en",
               "name": "english"
          }
     ],
     "colors": [
          {
               "id": 1,
               "name": "IndianRed",
               "code": "#CD5C5C",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 2,
               "name": "LightCoral",
               "code": "#F08080",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 3,
               "name": "Salmon",
               "code": "#FA8072",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 4,
               "name": "DarkSalmon",
               "code": "#E9967A",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 5,
               "name": "LightSalmon",
               "code": "#FFA07A",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 6,
               "name": "Crimson",
               "code": "#DC143C",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 7,
               "name": "Red",
               "code": "#FF0000",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 8,
               "name": "FireBrick",
               "code": "#B22222",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 9,
               "name": "DarkRed",
               "code": "#8B0000",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 10,
               "name": "Pink",
               "code": "#FFC0CB",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 11,
               "name": "LightPink",
               "code": "#FFB6C1",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 12,
               "name": "HotPink",
               "code": "#FF69B4",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 13,
               "name": "DeepPink",
               "code": "#FF1493",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 14,
               "name": "MediumVioletRed",
               "code": "#C71585",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 15,
               "name": "PaleVioletRed",
               "code": "#DB7093",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 17,
               "name": "Coral",
               "code": "#FF7F50",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 18,
               "name": "Tomato",
               "code": "#FF6347",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 19,
               "name": "OrangeRed",
               "code": "#FF4500",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 20,
               "name": "DarkOrange",
               "code": "#FF8C00",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 21,
               "name": "Orange",
               "code": "#FFA500",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 22,
               "name": "Gold",
               "code": "#FFD700",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 23,
               "name": "Yellow",
               "code": "#FFFF00",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 24,
               "name": "LightYellow",
               "code": "#FFFFE0",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 25,
               "name": "LemonChiffon",
               "code": "#FFFACD",
               "created_at": "2018-11-05T02:12:26.000000Z",
               "updated_at": "2018-11-05T02:12:26.000000Z"
          },
          {
               "id": 26,
               "name": "LightGoldenrodYellow",
               "code": "#FAFAD2",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 27,
               "name": "PapayaWhip",
               "code": "#FFEFD5",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 28,
               "name": "Moccasin",
               "code": "#FFE4B5",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 29,
               "name": "PeachPuff",
               "code": "#FFDAB9",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 30,
               "name": "PaleGoldenrod",
               "code": "#EEE8AA",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 31,
               "name": "Khaki",
               "code": "#F0E68C",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 32,
               "name": "DarkKhaki",
               "code": "#BDB76B",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 33,
               "name": "Lavender",
               "code": "#E6E6FA",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 34,
               "name": "Thistle",
               "code": "#D8BFD8",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 35,
               "name": "Plum",
               "code": "#DDA0DD",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 36,
               "name": "Violet",
               "code": "#EE82EE",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 37,
               "name": "Orchid",
               "code": "#DA70D6",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 39,
               "name": "Magenta",
               "code": "#FF00FF",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 40,
               "name": "MediumOrchid",
               "code": "#BA55D3",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 41,
               "name": "MediumPurple",
               "code": "#9370DB",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 42,
               "name": "Amethyst",
               "code": "#9966CC",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 43,
               "name": "BlueViolet",
               "code": "#8A2BE2",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 44,
               "name": "DarkViolet",
               "code": "#9400D3",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 45,
               "name": "DarkOrchid",
               "code": "#9932CC",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 46,
               "name": "DarkMagenta",
               "code": "#8B008B",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 47,
               "name": "Purple",
               "code": "#800080",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 48,
               "name": "Indigo",
               "code": "#4B0082",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 49,
               "name": "SlateBlue",
               "code": "#6A5ACD",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 50,
               "name": "DarkSlateBlue",
               "code": "#483D8B",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 51,
               "name": "MediumSlateBlue",
               "code": "#7B68EE",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 52,
               "name": "GreenYellow",
               "code": "#ADFF2F",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 53,
               "name": "Chartreuse",
               "code": "#7FFF00",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 54,
               "name": "LawnGreen",
               "code": "#7CFC00",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 55,
               "name": "Lime",
               "code": "#00FF00",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 56,
               "name": "LimeGreen",
               "code": "#32CD32",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 57,
               "name": "PaleGreen",
               "code": "#98FB98",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 58,
               "name": "LightGreen",
               "code": "#90EE90",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 59,
               "name": "MediumSpringGreen",
               "code": "#00FA9A",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 60,
               "name": "SpringGreen",
               "code": "#00FF7F",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 61,
               "name": "MediumSeaGreen",
               "code": "#3CB371",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 62,
               "name": "SeaGreen",
               "code": "#2E8B57",
               "created_at": "2018-11-05T02:12:27.000000Z",
               "updated_at": "2018-11-05T02:12:27.000000Z"
          },
          {
               "id": 63,
               "name": "ForestGreen",
               "code": "#228B22",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 64,
               "name": "Green",
               "code": "#008000",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 65,
               "name": "DarkGreen",
               "code": "#006400",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 66,
               "name": "YellowGreen",
               "code": "#9ACD32",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 67,
               "name": "OliveDrab",
               "code": "#6B8E23",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 68,
               "name": "Olive",
               "code": "#808000",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 69,
               "name": "DarkOliveGreen",
               "code": "#556B2F",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 70,
               "name": "MediumAquamarine",
               "code": "#66CDAA",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 71,
               "name": "DarkSeaGreen",
               "code": "#8FBC8F",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 72,
               "name": "LightSeaGreen",
               "code": "#20B2AA",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 73,
               "name": "DarkCyan",
               "code": "#008B8B",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 74,
               "name": "Teal",
               "code": "#008080",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 75,
               "name": "Aqua",
               "code": "#00FFFF",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 77,
               "name": "LightCyan",
               "code": "#E0FFFF",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 78,
               "name": "PaleTurquoise",
               "code": "#AFEEEE",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 79,
               "name": "Aquamarine",
               "code": "#7FFFD4",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 80,
               "name": "Turquoise",
               "code": "#40E0D0",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 81,
               "name": "MediumTurquoise",
               "code": "#48D1CC",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 82,
               "name": "DarkTurquoise",
               "code": "#00CED1",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 83,
               "name": "CadetBlue",
               "code": "#5F9EA0",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 84,
               "name": "SteelBlue",
               "code": "#4682B4",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 85,
               "name": "LightSteelBlue",
               "code": "#B0C4DE",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 86,
               "name": "PowderBlue",
               "code": "#B0E0E6",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 87,
               "name": "LightBlue",
               "code": "#ADD8E6",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 88,
               "name": "SkyBlue",
               "code": "#87CEEB",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 89,
               "name": "LightSkyBlue",
               "code": "#87CEFA",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 90,
               "name": "DeepSkyBlue",
               "code": "#00BFFF",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 91,
               "name": "DodgerBlue",
               "code": "#1E90FF",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 92,
               "name": "CornflowerBlue",
               "code": "#6495ED",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 94,
               "name": "RoyalBlue",
               "code": "#4169E1",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 95,
               "name": "Blue",
               "code": "#0000FF",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 96,
               "name": "MediumBlue",
               "code": "#0000CD",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 97,
               "name": "DarkBlue",
               "code": "#00008B",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 98,
               "name": "Navy",
               "code": "#000080",
               "created_at": "2018-11-05T02:12:28.000000Z",
               "updated_at": "2018-11-05T02:12:28.000000Z"
          },
          {
               "id": 99,
               "name": "MidnightBlue",
               "code": "#191970",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 100,
               "name": "Cornsilk",
               "code": "#FFF8DC",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 101,
               "name": "BlanchedAlmond",
               "code": "#FFEBCD",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 102,
               "name": "Bisque",
               "code": "#FFE4C4",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 103,
               "name": "NavajoWhite",
               "code": "#FFDEAD",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 104,
               "name": "Wheat",
               "code": "#F5DEB3",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 105,
               "name": "BurlyWood",
               "code": "#DEB887",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 106,
               "name": "Tan",
               "code": "#D2B48C",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 107,
               "name": "RosyBrown",
               "code": "#BC8F8F",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 108,
               "name": "SandyBrown",
               "code": "#F4A460",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 109,
               "name": "Goldenrod",
               "code": "#DAA520",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 110,
               "name": "DarkGoldenrod",
               "code": "#B8860B",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 111,
               "name": "Peru",
               "code": "#CD853F",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 112,
               "name": "Chocolate",
               "code": "#D2691E",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 113,
               "name": "SaddleBrown",
               "code": "#8B4513",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 114,
               "name": "Sienna",
               "code": "#A0522D",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 115,
               "name": "Brown",
               "code": "#A52A2A",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 116,
               "name": "Maroon",
               "code": "#800000",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 117,
               "name": "White",
               "code": "#FFFFFF",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 118,
               "name": "Snow",
               "code": "#FFFAFA",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 119,
               "name": "Honeydew",
               "code": "#F0FFF0",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 120,
               "name": "MintCream",
               "code": "#F5FFFA",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 121,
               "name": "Azure",
               "code": "#F0FFFF",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 122,
               "name": "AliceBlue",
               "code": "#F0F8FF",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 123,
               "name": "GhostWhite",
               "code": "#F8F8FF",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 124,
               "name": "WhiteSmoke",
               "code": "#F5F5F5",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 125,
               "name": "Seashell",
               "code": "#FFF5EE",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 126,
               "name": "Beige",
               "code": "#F5F5DC",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 127,
               "name": "OldLace",
               "code": "#FDF5E6",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 128,
               "name": "FloralWhite",
               "code": "#FFFAF0",
               "created_at": "2018-11-05T02:12:29.000000Z",
               "updated_at": "2018-11-05T02:12:29.000000Z"
          },
          {
               "id": 129,
               "name": "Ivory",
               "code": "#FFFFF0",
               "created_at": "2018-11-05T02:12:30.000000Z",
               "updated_at": "2018-11-05T02:12:30.000000Z"
          },
          {
               "id": 130,
               "name": "AntiqueWhite",
               "code": "#FAEBD7",
               "created_at": "2018-11-05T02:12:30.000000Z",
               "updated_at": "2018-11-05T02:12:30.000000Z"
          },
          {
               "id": 131,
               "name": "Linen",
               "code": "#FAF0E6",
               "created_at": "2018-11-05T02:12:30.000000Z",
               "updated_at": "2018-11-05T02:12:30.000000Z"
          },
          {
               "id": 132,
               "name": "LavenderBlush",
               "code": "#FFF0F5",
               "created_at": "2018-11-05T02:12:30.000000Z",
               "updated_at": "2018-11-05T02:12:30.000000Z"
          },
          {
               "id": 133,
               "name": "MistyRose",
               "code": "#FFE4E1",
               "created_at": "2018-11-05T02:12:30.000000Z",
               "updated_at": "2018-11-05T02:12:30.000000Z"
          },
          {
               "id": 134,
               "name": "Gainsboro",
               "code": "#DCDCDC",
               "created_at": "2018-11-05T02:12:30.000000Z",
               "updated_at": "2018-11-05T02:12:30.000000Z"
          },
          {
               "id": 135,
               "name": "LightGrey",
               "code": "#D3D3D3",
               "created_at": "2018-11-05T02:12:30.000000Z",
               "updated_at": "2018-11-05T02:12:30.000000Z"
          },
          {
               "id": 136,
               "name": "Silver",
               "code": "#C0C0C0",
               "created_at": "2018-11-05T02:12:30.000000Z",
               "updated_at": "2018-11-05T02:12:30.000000Z"
          },
          {
               "id": 137,
               "name": "DarkGray",
               "code": "#A9A9A9",
               "created_at": "2018-11-05T02:12:30.000000Z",
               "updated_at": "2018-11-05T02:12:30.000000Z"
          },
          {
               "id": 138,
               "name": "Gray",
               "code": "#808080",
               "created_at": "2018-11-05T02:12:30.000000Z",
               "updated_at": "2018-11-05T02:12:30.000000Z"
          },
          {
               "id": 139,
               "name": "DimGray",
               "code": "#696969",
               "created_at": "2018-11-05T02:12:30.000000Z",
               "updated_at": "2018-11-05T02:12:30.000000Z"
          },
          {
               "id": 140,
               "name": "LightSlateGray",
               "code": "#778899",
               "created_at": "2018-11-05T02:12:30.000000Z",
               "updated_at": "2018-11-05T02:12:30.000000Z"
          },
          {
               "id": 141,
               "name": "SlateGray",
               "code": "#708090",
               "created_at": "2018-11-05T02:12:30.000000Z",
               "updated_at": "2018-11-05T02:12:30.000000Z"
          },
          {
               "id": 142,
               "name": "DarkSlateGray",
               "code": "#2F4F4F",
               "created_at": "2018-11-05T02:12:30.000000Z",
               "updated_at": "2018-11-05T02:12:30.000000Z"
          },
          {
               "id": 143,
               "name": "Black",
               "code": "#000000",
               "created_at": "2018-11-05T02:12:30.000000Z",
               "updated_at": "2018-11-05T02:12:30.000000Z"
          }
     ],
     "unit": [
          "kg",
          "pc",
          "gms",
          "ltrs"
     ],
     "shipping_method": "inhouse_shipping",
     "email_verification": false,
     "phone_verification": false,
     "country_code": "IN",
     "social_login": [
          {
               "login_medium": "google",
               "status": false
          },
          {
               "login_medium": "facebook",
               "status": false
          },
          {
               "login_medium": "apple",
               "status": false
          }
     ],
     "currency_model": "single_currency",
     "forgot_password_verification": "email",
     "announcement": {
          "status": null,
          "color": null,
          "text_color": null,
          "announcement": null
     },
     "pixel_analytics": null,
     "software_version": "14.4",
     "decimal_point_settings": 2,
     "inhouse_selected_shipping_type": "order_wise",
     "billing_input_by_customer": 1,
     "minimum_order_limit": 1,
     "wallet_status": 1,
     "loyalty_point_status": 1,
     "loyalty_point_exchange_rate": 0,
     "loyalty_point_minimum_point": 0,
     "payment_methods": [],
     "offline_payment": null,
     "payment_method_image_path": "https://store.petropolis.in/storage/app/public/payment_modules/gateway_image",
     "ref_earning_status": "0",
     "active_theme": "default",
     "popular_tags": [
          {
               "id": 1,
               "tag": "pedigree",
               "visit_count": 0,
               "created_at": "2024-04-04T10:40:41.000000Z",
               "updated_at": "2024-04-04T10:40:41.000000Z"
          },
          {
               "id": 2,
               "tag": "dry food",
               "visit_count": 0,
               "created_at": "2024-04-04T10:40:41.000000Z",
               "updated_at": "2024-04-04T10:40:41.000000Z"
          },
          {
               "id": 3,
               "tag": "dog food",
               "visit_count": 0,
               "created_at": "2024-04-04T10:40:41.000000Z",
               "updated_at": "2024-04-04T10:40:41.000000Z"
          },
          {
               "id": 4,
               "tag": "dog dry food",
               "visit_count": 0,
               "created_at": "2024-04-04T10:40:41.000000Z",
               "updated_at": "2024-04-04T10:40:41.000000Z"
          },
          {
               "id": 5,
               "tag": "pedigree food",
               "visit_count": 0,
               "created_at": "2024-04-04T10:40:41.000000Z",
               "updated_at": "2024-04-04T10:40:41.000000Z"
          }
     ],
     "guest_checkout": 0,
     "upload_picture_on_delivery": null,
     "user_app_version_control": {
          "for_android": {
               "status": 1,
               "version": "14.1",
               "link": ""
          },
          "for_ios": {
               "status": 1,
               "version": "14.1",
               "link": ""
          }
     },
     "seller_app_version_control": {
          "for_android": {
               "status": 1,
               "version": "14.1",
               "link": ""
          },
          "for_ios": {
               "status": 1,
               "version": "14.1",
               "link": ""
          }
     },
     "delivery_man_app_version_control": {
          "for_android": {
               "status": 1,
               "version": "14.1",
               "link": ""
          },
          "for_ios": {
               "status": 1,
               "version": "14.1",
               "link": ""
          }
     },
     "add_funds_to_wallet": 0,
     "minimum_add_fund_amount": 0,
     "maximum_add_fund_amount": 0,
     "inhouse_temporary_close": {
          "status": 0
     },
     "inhouse_vacation_add": {
          "status": 0,
          "vacation_start_date": null,
          "vacation_end_date": null,
          "vacation_note": null
     },
     "free_delivery_status": 1,
     "free_delivery_over_amount": 0,
     "free_delivery_responsibility": "admin",
     "free_delivery_over_amount_seller": 1000,
     "minimum_order_amount_status": 1,
     "minimum_order_amount": 0,
     "minimum_order_amount_by_seller": 0,
     "order_verification": 1,
     "referral_customer_signup_url": "https://store.petropolis.in?referral_code=",
     "system_timezone": "UTC",
     "refund_day_limit": "1"
}
```
 
</details>
 
## 2. 200 GET /api/v1/banners
 
**Model**
 
Paste you model hear
 
<details>
 
<summary>Example</summary>
 
```json
[
     {
          "id": 1,
          "photo": "2024-04-04-660e889015edc.webp",
          "banner_type": "Main Banner",
          "theme": "default",
          "published": 1,
          "created_at": "2024-04-04T11:01:36.000000Z",
          "updated_at": "2024-04-04T11:02:16.000000Z",
          "url": "https://store.petropolis.in/storage/app/public/Main%20Banner.jpg",
          "resource_type": "category",
          "resource_id": 1,
          "title": null,
          "sub_title": null,
          "button_text": null,
          "background_color": null
     }
]
```
 
</details>
 
## 3. 200 GET /api/v1/categories?guest_id=1
 
**Model**
 
Paste you model hear
 
<details>
 
<summary>Example</summary>
 
```json
[
     {
          "id": 1,
          "name": "Dogs",
          "slug": "dogs",
          "icon": "2024-04-04-660e7f3a8efec.webp",
          "parent_id": 0,
          "position": 0,
          "created_at": "2024-04-04T10:21:46.000000Z",
          "updated_at": "2024-04-04T10:21:46.000000Z",
          "home_status": 0,
          "priority": 1,
          "product_count": 1,
          "childes": [
               {
                    "id": 2,
                    "name": "Dog Food",
                    "slug": "dog-food",
                    "icon": "def.png",
                    "parent_id": 1,
                    "position": 1,
                    "created_at": "2024-04-04T10:22:28.000000Z",
                    "updated_at": "2024-04-04T10:22:28.000000Z",
                    "home_status": 0,
                    "priority": 1,
                    "sub_category_product_count": 1,
                    "childes": [
                         {
                              "id": 3,
                              "name": "Dog Dry Food",
                              "slug": "dog-dry-food",
                              "icon": "def.png",
                              "parent_id": 2,
                              "position": 2,
                              "created_at": "2024-04-04T10:22:55.000000Z",
                              "updated_at": "2024-04-04T10:22:55.000000Z",
                              "home_status": 0,
                              "priority": 1,
                              "sub_sub_category_product_count": 0,
                              "translations": []
                         }
                    ],
                    "translations": []
               }
          ],
          "translations": []
     }
]
```
 
</details>
 
## 4. 200 GET /api/v1/products/latest?guest_id=1&limit=10&&offset=1
 
**Model**
 
Paste you model hear
 
<details>
 
<summary>Example</summary>
 
```json
{
     "total_size": 1,
     "limit": 10,
     "offset": 1,
     "products": [
          {
               "id": 1,
               "added_by": "admin",
               "user_id": 1,
               "name": "Pedigree Chicken and Vegetables Adult Dry Dog Food",
               "slug": "pedigree-chicken-and-vegetables-adult-dry-dog-food-uvJj6q",
               "product_type": "physical",
               "category_ids": [
                    {
                         "id": "1",
                         "position": 1
                    },
                    {
                         "id": "2",
                         "position": 2
                    }
               ],
               "category_id": 1,
               "sub_category_id": 2,
               "sub_sub_category_id": null,
               "brand_id": 1,
               "unit": "kg",
               "min_qty": 1,
               "refundable": 1,
               "digital_product_type": null,
               "digital_file_ready": null,
               "images": [
                    "2024-04-04-660e83a921e35.webp",
                    "2024-04-04-660e83a93f1f2.webp",
                    "2024-04-04-660e83a9629b4.webp"
               ],
               "color_image": [],
               "thumbnail": "2024-04-04-660e83a98db91.png",
               "featured": null,
               "flash_deal": null,
               "video_provider": "youtube",
               "video_url": null,
               "colors": [],
               "variant_product": 0,
               "attributes": [
                    1
               ],
               "choice_options": [
                    {
                         "name": "choice_1",
                         "title": "Weight",
                         "options": [
                              "1 Kg",
                              "    2.8 Kg",
                              "    5.5 Kg",
                              "    10 Kg",
                              "    15 Kg",
                              "    20 Kg",
                              "    370 gm"
                         ]
                    }
               ],
               "variation": [
                    {
                         "type": "1Kg",
                         "price": 269,
                         "sku": "PCAVADDF-1KG",
                         "qty": 10
                    },
                    {
                         "type": "2.8Kg",
                         "price": 269,
                         "sku": "PCAVADDF-2.8KG",
                         "qty": 10
                    },
                    {
                         "type": "5.5Kg",
                         "price": 269,
                         "sku": "PCAVADDF-5.5KG",
                         "qty": 10
                    },
                    {
                         "type": "10Kg",
                         "price": 269,
                         "sku": "PCAVADDF-10KG",
                         "qty": 10
                    },
                    {
                         "type": "15Kg",
                         "price": 269,
                         "sku": "PCAVADDF-15KG",
                         "qty": 10
                    },
                    {
                         "type": "20Kg",
                         "price": 269,
                         "sku": "PCAVADDF-20KG",
                         "qty": 10
                    },
                    {
                         "type": "370gm",
                         "price": 100,
                         "sku": "PCAVADDF-370GM",
                         "qty": 10
                    }
               ],
               "published": 0,
               "unit_price": 269,
               "purchase_price": 0,
               "tax": 18,
               "tax_type": "percent",
               "tax_model": "include",
               "discount": 10,
               "discount_type": "percent",
               "current_stock": 70,
               "minimum_order_qty": 1,
               "details": "<p data-mce-fragment=\"1\" style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\">Pedigree offers dogs complete and balanced dog food for a healthy and active life. Pedigree Adult Dry Dog Food in Chicken and Vegetable Flavor is a wholesome meal packed with essential nutrients vital to the overall health of your pet. The goodness of quality ingredients, including chicken and vegetables, blends into a tasty and healthy diet for your furry friend. When fed as per the feeding guidelines (refer to the back of the pack), you will see the 5 Signs of Good Health in your pet. These signs include healthy skin and coat (from a blend of Zinc and Omega Fatty Acids); strong bones and teeth (from Ca:P ratio and levels); healthy digestion (from dietary fiber); strong muscles (from Protein); strong immune system (from Vitamins (Vitamin E) and Minerals). At Pedigree, recipes are developed based on research from the Waltham Centre for Pet Nutrition. Every product from Pedigree meets the requirements laid down by NRC 2006 of the U.S. National Academy of Science. Give your furry companion healthy and lip-smacking mealtimes with Pedigree.</p><p data-mce-fragment=\"1\" style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span style=\"font-weight: 700;\">Key Features:</span></p><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">COMPLETE AND BALANCED DOG FOOD: Pedigree Wet Dog Food provides complete and balanced nutrition for adult dogs.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">DELICIOUS FLAVOR: Pedigree Adult Dry Dog Food in Chicken and Vegetables Flavor is packed with mouth-watering kibbles to delight your dog.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">QUALITY INGREDIENTS: This tasty and healthy food is made with high-quality ingredients, including chicken and vegetables for the right nutrition.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">NOURISHING FOOD: This dry dog food is specially formulated for adult dogs with essential nutrients and high protein.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">5 SIGNS OF GOOD HEALTH: It gives them a shiny coat and keeps their bones and teeth strong. It also helps with healthy digestion, builds strong muscles, and strengthens the immune system.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"></ul><p style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span style=\"font-weight: 700;\">Ingredients:</span></p><p style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span data-sheets-root=\"1\" data-sheets-value=\"{\"1\":2,\"2\":\"Cereals and Cereal by-products, Chicken and Chicken by-products and/or Meat and Meat by-products, Soybean Meal, Soybean Oil, Di-calcium phosphate, Iodised Salt, Antioxidants, Distilled Monoglycerides, Choline Chloride, Vitamins and Minerals, Carrot Powder, Peas Powder, Zinc Sulphate Monohydrate, Permitted Preservatives & Flavors.\"}\" data-sheets-userformat=\"{\"2\":14591,\"3\":{\"1\":0,\"3\":1},\"4\":{\"1\":3,\"3\":2},\"5\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"6\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"7\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"8\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"9\":1,\"10\":1,\"14\":{\"1\":3,\"3\":1},\"15\":\"Calibri\",\"16\":11}\">Cereals and Cereal by-products, Chicken and Chicken by-products and/or Meat and Meat by-products, Soybean Meal, Soybean Oil, Di-calcium phosphate, Iodised Salt, Antioxidants, Distilled Monoglycerides, Choline Chloride, Vitamins and Minerals, Carrot Powder, Peas Powder, Zinc Sulphate Monohydrate, Permitted Preservatives & Flavors.</span></p>",
               "free_shipping": 0,
               "attachment": null,
               "created_at": "2024-04-04T10:40:41.000000Z",
               "updated_at": "2024-04-08T11:43:55.000000Z",
               "status": 1,
               "featured_status": 1,
               "meta_title": "Pedigree Chicken and Vegetables Adult Dry Dog Food",
               "meta_description": "Pedigree offers dogs complete and balanced dog food for a healthy and active life. Pedigree Adult Dry Dog Food in Chicken and Vegetable Flavor is a wholesome meal packed with essential nutrie",
               "meta_image": "2024-04-04-660e83a9b9dba.png",
               "request_status": 1,
               "denied_note": null,
               "shipping_cost": 0,
               "multiply_qty": 0,
               "temp_shipping_cost": null,
               "is_shipping_cost_updated": null,
               "code": "164357",
               "reviews_count": 0,
               "wish_list_count": 0,
               "flash_deal_status": 0,
               "flash_deal_end_date": 0,
               "colors_formatted": [],
               "rating": [],
               "tags": [
                    {
                         "id": 1,
                         "tag": "pedigree",
                         "visit_count": 0,
                         "created_at": "2024-04-04T10:40:41.000000Z",
                         "updated_at": "2024-04-04T10:40:41.000000Z",
                         "pivot": {
                              "product_id": 1,
                              "tag_id": 1
                         }
                    },
                    {
                         "id": 2,
                         "tag": "dry food",
                         "visit_count": 0,
                         "created_at": "2024-04-04T10:40:41.000000Z",
                         "updated_at": "2024-04-04T10:40:41.000000Z",
                         "pivot": {
                              "product_id": 1,
                              "tag_id": 2
                         }
                    },
                    {
                         "id": 3,
                         "tag": "dog food",
                         "visit_count": 0,
                         "created_at": "2024-04-04T10:40:41.000000Z",
                         "updated_at": "2024-04-04T10:40:41.000000Z",
                         "pivot": {
                              "product_id": 1,
                              "tag_id": 3
                         }
                    },
                    {
                         "id": 4,
                         "tag": "dog dry food",
                         "visit_count": 0,
                         "created_at": "2024-04-04T10:40:41.000000Z",
                         "updated_at": "2024-04-04T10:40:41.000000Z",
                         "pivot": {
                              "product_id": 1,
                              "tag_id": 4
                         }
                    },
                    {
                         "id": 5,
                         "tag": "pedigree food",
                         "visit_count": 0,
                         "created_at": "2024-04-04T10:40:41.000000Z",
                         "updated_at": "2024-04-04T10:40:41.000000Z",
                         "pivot": {
                              "product_id": 1,
                              "tag_id": 5
                         }
                    }
               ],
               "seller": null,
               "flash_deal_products": [],
               "translations": [],
               "reviews": []
          }
     ]
}
```
 
</details>
 
## 5. 200 GET /api/v1/dealsoftheday/deal-of-the-day
 
**Model**
 
Paste you model hear
 
<details>
 
<summary>Example</summary>
 
```json
{
     "id": 1,
     "added_by": "admin",
     "user_id": 1,
     "name": "Pedigree Chicken and Vegetables Adult Dry Dog Food",
     "slug": "pedigree-chicken-and-vegetables-adult-dry-dog-food-uvJj6q",
     "product_type": "physical",
     "category_ids": [
          {
               "id": "1",
               "position": 1
          },
          {
               "id": "2",
               "position": 2
          }
     ],
     "category_id": 1,
     "sub_category_id": 2,
     "sub_sub_category_id": null,
     "brand_id": 1,
     "unit": "kg",
     "min_qty": 1,
     "refundable": 1,
     "digital_product_type": null,
     "digital_file_ready": null,
     "images": [
          "2024-04-04-660e83a921e35.webp",
          "2024-04-04-660e83a93f1f2.webp",
          "2024-04-04-660e83a9629b4.webp"
     ],
     "color_image": [],
     "thumbnail": "2024-04-04-660e83a98db91.png",
     "featured": null,
     "flash_deal": null,
     "video_provider": "youtube",
     "video_url": null,
     "colors": [],
     "variant_product": 0,
     "attributes": [
          1
     ],
     "choice_options": [
          {
               "name": "choice_1",
               "title": "Weight",
               "options": [
                    "1 Kg",
                    "    2.8 Kg",
                    "    5.5 Kg",
                    "    10 Kg",
                    "    15 Kg",
                    "    20 Kg",
                    "    370 gm"
               ]
          }
     ],
     "variation": [
          {
               "type": "1Kg",
               "price": 269,
               "sku": "PCAVADDF-1KG",
               "qty": 10
          },
          {
               "type": "2.8Kg",
               "price": 269,
               "sku": "PCAVADDF-2.8KG",
               "qty": 10
          },
          {
               "type": "5.5Kg",
               "price": 269,
               "sku": "PCAVADDF-5.5KG",
               "qty": 10
          },
          {
               "type": "10Kg",
               "price": 269,
               "sku": "PCAVADDF-10KG",
               "qty": 10
          },
          {
               "type": "15Kg",
               "price": 269,
               "sku": "PCAVADDF-15KG",
               "qty": 10
          },
          {
               "type": "20Kg",
               "price": 269,
               "sku": "PCAVADDF-20KG",
               "qty": 10
          },
          {
               "type": "370gm",
               "price": 100,
               "sku": "PCAVADDF-370GM",
               "qty": 10
          }
     ],
     "published": 0,
     "unit_price": 269,
     "purchase_price": 0,
     "tax": 18,
     "tax_type": "percent",
     "tax_model": "include",
     "discount": 10,
     "discount_type": "percent",
     "current_stock": 70,
     "minimum_order_qty": 1,
     "details": "<p data-mce-fragment=\"1\" style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\">Pedigree offers dogs complete and balanced dog food for a healthy and active life. Pedigree Adult Dry Dog Food in Chicken and Vegetable Flavor is a wholesome meal packed with essential nutrients vital to the overall health of your pet. The goodness of quality ingredients, including chicken and vegetables, blends into a tasty and healthy diet for your furry friend. When fed as per the feeding guidelines (refer to the back of the pack), you will see the 5 Signs of Good Health in your pet. These signs include healthy skin and coat (from a blend of Zinc and Omega Fatty Acids); strong bones and teeth (from Ca:P ratio and levels); healthy digestion (from dietary fiber); strong muscles (from Protein); strong immune system (from Vitamins (Vitamin E) and Minerals). At Pedigree, recipes are developed based on research from the Waltham Centre for Pet Nutrition. Every product from Pedigree meets the requirements laid down by NRC 2006 of the U.S. National Academy of Science. Give your furry companion healthy and lip-smacking mealtimes with Pedigree.</p><p data-mce-fragment=\"1\" style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span style=\"font-weight: 700;\">Key Features:</span></p><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">COMPLETE AND BALANCED DOG FOOD: Pedigree Wet Dog Food provides complete and balanced nutrition for adult dogs.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">DELICIOUS FLAVOR: Pedigree Adult Dry Dog Food in Chicken and Vegetables Flavor is packed with mouth-watering kibbles to delight your dog.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">QUALITY INGREDIENTS: This tasty and healthy food is made with high-quality ingredients, including chicken and vegetables for the right nutrition.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">NOURISHING FOOD: This dry dog food is specially formulated for adult dogs with essential nutrients and high protein.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">5 SIGNS OF GOOD HEALTH: It gives them a shiny coat and keeps their bones and teeth strong. It also helps with healthy digestion, builds strong muscles, and strengthens the immune system.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"></ul><p style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span style=\"font-weight: 700;\">Ingredients:</span></p><p style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span data-sheets-root=\"1\" data-sheets-value=\"{\"1\":2,\"2\":\"Cereals and Cereal by-products, Chicken and Chicken by-products and/or Meat and Meat by-products, Soybean Meal, Soybean Oil, Di-calcium phosphate, Iodised Salt, Antioxidants, Distilled Monoglycerides, Choline Chloride, Vitamins and Minerals, Carrot Powder, Peas Powder, Zinc Sulphate Monohydrate, Permitted Preservatives & Flavors.\"}\" data-sheets-userformat=\"{\"2\":14591,\"3\":{\"1\":0,\"3\":1},\"4\":{\"1\":3,\"3\":2},\"5\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"6\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"7\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"8\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"9\":1,\"10\":1,\"14\":{\"1\":3,\"3\":1},\"15\":\"Calibri\",\"16\":11}\">Cereals and Cereal by-products, Chicken and Chicken by-products and/or Meat and Meat by-products, Soybean Meal, Soybean Oil, Di-calcium phosphate, Iodised Salt, Antioxidants, Distilled Monoglycerides, Choline Chloride, Vitamins and Minerals, Carrot Powder, Peas Powder, Zinc Sulphate Monohydrate, Permitted Preservatives & Flavors.</span></p>",
     "free_shipping": 0,
     "attachment": null,
     "created_at": "2024-04-04T10:40:41.000000Z",
     "updated_at": "2024-04-08T11:43:55.000000Z",
     "status": 1,
     "featured_status": 1,
     "meta_title": "Pedigree Chicken and Vegetables Adult Dry Dog Food",
     "meta_description": "Pedigree offers dogs complete and balanced dog food for a healthy and active life. Pedigree Adult Dry Dog Food in Chicken and Vegetable Flavor is a wholesome meal packed with essential nutrie",
     "meta_image": "2024-04-04-660e83a9b9dba.png",
     "request_status": 1,
     "denied_note": null,
     "shipping_cost": 0,
     "multiply_qty": 0,
     "temp_shipping_cost": null,
     "is_shipping_cost_updated": null,
     "code": "164357",
     "reviews_count": 0,
     "colors_formatted": [],
     "rating": [],
     "translations": [],
     "reviews": []
}
```
 
</details>
 
## 6. 200 GET /api/v1/categories/products/1?guest_id=1
 
**Model**
 
Paste you model hear
 
<details>
 
<summary>Example</summary>
 
```json
[
     {
          "id": 1,
          "added_by": "admin",
          "user_id": 1,
          "name": "Pedigree Chicken and Vegetables Adult Dry Dog Food",
          "slug": "pedigree-chicken-and-vegetables-adult-dry-dog-food-uvJj6q",
          "product_type": "physical",
          "category_ids": [
               {
                    "id": "1",
                    "position": 1
               },
               {
                    "id": "2",
                    "position": 2
               }
          ],
          "category_id": 1,
          "sub_category_id": 2,
          "sub_sub_category_id": null,
          "brand_id": 1,
          "unit": "kg",
          "min_qty": 1,
          "refundable": 1,
          "digital_product_type": null,
          "digital_file_ready": null,
          "images": [
               "2024-04-04-660e83a921e35.webp",
               "2024-04-04-660e83a93f1f2.webp",
               "2024-04-04-660e83a9629b4.webp"
          ],
          "color_image": [],
          "thumbnail": "2024-04-04-660e83a98db91.png",
          "featured": null,
          "flash_deal": null,
          "video_provider": "youtube",
          "video_url": null,
          "colors": [],
          "variant_product": 0,
          "attributes": [
               1
          ],
          "choice_options": [
               {
                    "name": "choice_1",
                    "title": "Weight",
                    "options": [
                         "1 Kg",
                         "    2.8 Kg",
                         "    5.5 Kg",
                         "    10 Kg",
                         "    15 Kg",
                         "    20 Kg",
                         "    370 gm"
                    ]
               }
          ],
          "variation": [
               {
                    "type": "1Kg",
                    "price": 269,
                    "sku": "PCAVADDF-1KG",
                    "qty": 10
               },
               {
                    "type": "2.8Kg",
                    "price": 269,
                    "sku": "PCAVADDF-2.8KG",
                    "qty": 10
               },
               {
                    "type": "5.5Kg",
                    "price": 269,
                    "sku": "PCAVADDF-5.5KG",
                    "qty": 10
               },
               {
                    "type": "10Kg",
                    "price": 269,
                    "sku": "PCAVADDF-10KG",
                    "qty": 10
               },
               {
                    "type": "15Kg",
                    "price": 269,
                    "sku": "PCAVADDF-15KG",
                    "qty": 10
               },
               {
                    "type": "20Kg",
                    "price": 269,
                    "sku": "PCAVADDF-20KG",
                    "qty": 10
               },
               {
                    "type": "370gm",
                    "price": 100,
                    "sku": "PCAVADDF-370GM",
                    "qty": 10
               }
          ],
          "published": 0,
          "unit_price": 269,
          "purchase_price": 0,
          "tax": 18,
          "tax_type": "percent",
          "tax_model": "include",
          "discount": 10,
          "discount_type": "percent",
          "current_stock": 70,
          "minimum_order_qty": 1,
          "details": "<p data-mce-fragment=\"1\" style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\">Pedigree offers dogs complete and balanced dog food for a healthy and active life. Pedigree Adult Dry Dog Food in Chicken and Vegetable Flavor is a wholesome meal packed with essential nutrients vital to the overall health of your pet. The goodness of quality ingredients, including chicken and vegetables, blends into a tasty and healthy diet for your furry friend. When fed as per the feeding guidelines (refer to the back of the pack), you will see the 5 Signs of Good Health in your pet. These signs include healthy skin and coat (from a blend of Zinc and Omega Fatty Acids); strong bones and teeth (from Ca:P ratio and levels); healthy digestion (from dietary fiber); strong muscles (from Protein); strong immune system (from Vitamins (Vitamin E) and Minerals). At Pedigree, recipes are developed based on research from the Waltham Centre for Pet Nutrition. Every product from Pedigree meets the requirements laid down by NRC 2006 of the U.S. National Academy of Science. Give your furry companion healthy and lip-smacking mealtimes with Pedigree.</p><p data-mce-fragment=\"1\" style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span style=\"font-weight: 700;\">Key Features:</span></p><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">COMPLETE AND BALANCED DOG FOOD: Pedigree Wet Dog Food provides complete and balanced nutrition for adult dogs.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">DELICIOUS FLAVOR: Pedigree Adult Dry Dog Food in Chicken and Vegetables Flavor is packed with mouth-watering kibbles to delight your dog.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">QUALITY INGREDIENTS: This tasty and healthy food is made with high-quality ingredients, including chicken and vegetables for the right nutrition.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">NOURISHING FOOD: This dry dog food is specially formulated for adult dogs with essential nutrients and high protein.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">5 SIGNS OF GOOD HEALTH: It gives them a shiny coat and keeps their bones and teeth strong. It also helps with healthy digestion, builds strong muscles, and strengthens the immune system.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"></ul><p style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span style=\"font-weight: 700;\">Ingredients:</span></p><p style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span data-sheets-root=\"1\" data-sheets-value=\"{\"1\":2,\"2\":\"Cereals and Cereal by-products, Chicken and Chicken by-products and/or Meat and Meat by-products, Soybean Meal, Soybean Oil, Di-calcium phosphate, Iodised Salt, Antioxidants, Distilled Monoglycerides, Choline Chloride, Vitamins and Minerals, Carrot Powder, Peas Powder, Zinc Sulphate Monohydrate, Permitted Preservatives & Flavors.\"}\" data-sheets-userformat=\"{\"2\":14591,\"3\":{\"1\":0,\"3\":1},\"4\":{\"1\":3,\"3\":2},\"5\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"6\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"7\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"8\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"9\":1,\"10\":1,\"14\":{\"1\":3,\"3\":1},\"15\":\"Calibri\",\"16\":11}\">Cereals and Cereal by-products, Chicken and Chicken by-products and/or Meat and Meat by-products, Soybean Meal, Soybean Oil, Di-calcium phosphate, Iodised Salt, Antioxidants, Distilled Monoglycerides, Choline Chloride, Vitamins and Minerals, Carrot Powder, Peas Powder, Zinc Sulphate Monohydrate, Permitted Preservatives & Flavors.</span></p>",
          "free_shipping": 0,
          "attachment": null,
          "created_at": "2024-04-04T10:40:41.000000Z",
          "updated_at": "2024-04-08T11:43:55.000000Z",
          "status": 1,
          "featured_status": 1,
          "meta_title": "Pedigree Chicken and Vegetables Adult Dry Dog Food",
          "meta_description": "Pedigree offers dogs complete and balanced dog food for a healthy and active life. Pedigree Adult Dry Dog Food in Chicken and Vegetable Flavor is a wholesome meal packed with essential nutrie",
          "meta_image": "2024-04-04-660e83a9b9dba.png",
          "request_status": 1,
          "denied_note": null,
          "shipping_cost": 0,
          "multiply_qty": 0,
          "temp_shipping_cost": null,
          "is_shipping_cost_updated": null,
          "code": "164357",
          "reviews_count": 0,
          "wish_list_count": 0,
          "flash_deal_status": 0,
          "flash_deal_end_date": 0,
          "colors_formatted": [],
          "flash_deal_products": [],
          "rating": [],
          "tags": [
               {
                    "id": 1,
                    "tag": "pedigree",
                    "visit_count": 0,
                    "created_at": "2024-04-04T10:40:41.000000Z",
                    "updated_at": "2024-04-04T10:40:41.000000Z",
                    "pivot": {
                         "product_id": 1,
                         "tag_id": 1
                    }
               },
               {
                    "id": 2,
                    "tag": "dry food",
                    "visit_count": 0,
                    "created_at": "2024-04-04T10:40:41.000000Z",
                    "updated_at": "2024-04-04T10:40:41.000000Z",
                    "pivot": {
                         "product_id": 1,
                         "tag_id": 2
                    }
               },
               {
                    "id": 3,
                    "tag": "dog food",
                    "visit_count": 0,
                    "created_at": "2024-04-04T10:40:41.000000Z",
                    "updated_at": "2024-04-04T10:40:41.000000Z",
                    "pivot": {
                         "product_id": 1,
                         "tag_id": 3
                    }
               },
               {
                    "id": 4,
                    "tag": "dog dry food",
                    "visit_count": 0,
                    "created_at": "2024-04-04T10:40:41.000000Z",
                    "updated_at": "2024-04-04T10:40:41.000000Z",
                    "pivot": {
                         "product_id": 1,
                         "tag_id": 4
                    }
               },
               {
                    "id": 5,
                    "tag": "pedigree food",
                    "visit_count": 0,
                    "created_at": "2024-04-04T10:40:41.000000Z",
                    "updated_at": "2024-04-04T10:40:41.000000Z",
                    "pivot": {
                         "product_id": 1,
                         "tag_id": 5
                    }
               }
          ],
          "seller": null,
          "translations": [],
          "reviews": []
     }
]
```
 
</details>
 
## 7. 200 GET /api/v1/products/details/pedigree-chicken-and-vegetables-adult-dry-dog-food-uvJj6q?guest_id=1
 
**Model**
 
Paste you model hear
 
<details>
 
<summary>Example</summary>
 
```json
{
     "id": 1,
     "added_by": "admin",
     "user_id": 1,
     "name": "Pedigree Chicken and Vegetables Adult Dry Dog Food",
     "slug": "pedigree-chicken-and-vegetables-adult-dry-dog-food-uvJj6q",
     "product_type": "physical",
     "category_ids": [
          {
               "id": "1",
               "position": 1
          },
          {
               "id": "2",
               "position": 2
          }
     ],
     "category_id": 1,
     "sub_category_id": 2,
     "sub_sub_category_id": null,
     "brand_id": 1,
     "unit": "kg",
     "min_qty": 1,
     "refundable": 1,
     "digital_product_type": null,
     "digital_file_ready": null,
     "images": [
          "2024-04-04-660e83a921e35.webp",
          "2024-04-04-660e83a93f1f2.webp",
          "2024-04-04-660e83a9629b4.webp"
     ],
     "color_image": [],
     "thumbnail": "2024-04-04-660e83a98db91.png",
     "featured": null,
     "flash_deal": null,
     "video_provider": "youtube",
     "video_url": null,
     "colors": [],
     "variant_product": 0,
     "attributes": [
          1
     ],
     "choice_options": [
          {
               "name": "choice_1",
               "title": "Weight",
               "options": [
                    "1 Kg",
                    "    2.8 Kg",
                    "    5.5 Kg",
                    "    10 Kg",
                    "    15 Kg",
                    "    20 Kg",
                    "    370 gm"
               ]
          }
     ],
     "variation": [
          {
               "type": "1Kg",
               "price": 269,
               "sku": "PCAVADDF-1KG",
               "qty": 10
          },
          {
               "type": "2.8Kg",
               "price": 269,
               "sku": "PCAVADDF-2.8KG",
               "qty": 10
          },
          {
               "type": "5.5Kg",
               "price": 269,
               "sku": "PCAVADDF-5.5KG",
               "qty": 10
          },
          {
               "type": "10Kg",
               "price": 269,
               "sku": "PCAVADDF-10KG",
               "qty": 10
          },
          {
               "type": "15Kg",
               "price": 269,
               "sku": "PCAVADDF-15KG",
               "qty": 10
          },
          {
               "type": "20Kg",
               "price": 269,
               "sku": "PCAVADDF-20KG",
               "qty": 10
          },
          {
               "type": "370gm",
               "price": 100,
               "sku": "PCAVADDF-370GM",
               "qty": 10
          }
     ],
     "published": 0,
     "unit_price": 269,
     "purchase_price": 0,
     "tax": 18,
     "tax_type": "percent",
     "tax_model": "include",
     "discount": 10,
     "discount_type": "percent",
     "current_stock": 70,
     "minimum_order_qty": 1,
     "details": "<p data-mce-fragment=\"1\" style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\">Pedigree offers dogs complete and balanced dog food for a healthy and active life. Pedigree Adult Dry Dog Food in Chicken and Vegetable Flavor is a wholesome meal packed with essential nutrients vital to the overall health of your pet. The goodness of quality ingredients, including chicken and vegetables, blends into a tasty and healthy diet for your furry friend. When fed as per the feeding guidelines (refer to the back of the pack), you will see the 5 Signs of Good Health in your pet. These signs include healthy skin and coat (from a blend of Zinc and Omega Fatty Acids); strong bones and teeth (from Ca:P ratio and levels); healthy digestion (from dietary fiber); strong muscles (from Protein); strong immune system (from Vitamins (Vitamin E) and Minerals). At Pedigree, recipes are developed based on research from the Waltham Centre for Pet Nutrition. Every product from Pedigree meets the requirements laid down by NRC 2006 of the U.S. National Academy of Science. Give your furry companion healthy and lip-smacking mealtimes with Pedigree.</p><p data-mce-fragment=\"1\" style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span style=\"font-weight: 700;\">Key Features:</span></p><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">COMPLETE AND BALANCED DOG FOOD: Pedigree Wet Dog Food provides complete and balanced nutrition for adult dogs.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">DELICIOUS FLAVOR: Pedigree Adult Dry Dog Food in Chicken and Vegetables Flavor is packed with mouth-watering kibbles to delight your dog.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">QUALITY INGREDIENTS: This tasty and healthy food is made with high-quality ingredients, including chicken and vegetables for the right nutrition.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">NOURISHING FOOD: This dry dog food is specially formulated for adult dogs with essential nutrients and high protein.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">5 SIGNS OF GOOD HEALTH: It gives them a shiny coat and keeps their bones and teeth strong. It also helps with healthy digestion, builds strong muscles, and strengthens the immune system.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"></ul><p style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span style=\"font-weight: 700;\">Ingredients:</span></p><p style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span data-sheets-root=\"1\" data-sheets-value=\"{\"1\":2,\"2\":\"Cereals and Cereal by-products, Chicken and Chicken by-products and/or Meat and Meat by-products, Soybean Meal, Soybean Oil, Di-calcium phosphate, Iodised Salt, Antioxidants, Distilled Monoglycerides, Choline Chloride, Vitamins and Minerals, Carrot Powder, Peas Powder, Zinc Sulphate Monohydrate, Permitted Preservatives & Flavors.\"}\" data-sheets-userformat=\"{\"2\":14591,\"3\":{\"1\":0,\"3\":1},\"4\":{\"1\":3,\"3\":2},\"5\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"6\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"7\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"8\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"9\":1,\"10\":1,\"14\":{\"1\":3,\"3\":1},\"15\":\"Calibri\",\"16\":11}\">Cereals and Cereal by-products, Chicken and Chicken by-products and/or Meat and Meat by-products, Soybean Meal, Soybean Oil, Di-calcium phosphate, Iodised Salt, Antioxidants, Distilled Monoglycerides, Choline Chloride, Vitamins and Minerals, Carrot Powder, Peas Powder, Zinc Sulphate Monohydrate, Permitted Preservatives & Flavors.</span></p>",
     "free_shipping": 0,
     "attachment": null,
     "created_at": "2024-04-04T10:40:41.000000Z",
     "updated_at": "2024-04-08T11:43:55.000000Z",
     "status": 1,
     "featured_status": 1,
     "meta_title": "Pedigree Chicken and Vegetables Adult Dry Dog Food",
     "meta_description": "Pedigree offers dogs complete and balanced dog food for a healthy and active life. Pedigree Adult Dry Dog Food in Chicken and Vegetable Flavor is a wholesome meal packed with essential nutrie",
     "meta_image": "2024-04-04-660e83a9b9dba.png",
     "request_status": 1,
     "denied_note": null,
     "shipping_cost": 0,
     "multiply_qty": 0,
     "temp_shipping_cost": null,
     "is_shipping_cost_updated": null,
     "code": "164357",
     "wish_list_count": 0,
     "colors_formatted": [],
     "average_review": 0,
     "inhouse_vacation_start_date": null,
     "inhouse_vacation_end_date": null,
     "inhouse_temporary_close": 0,
     "reviews_count": 0,
     "reviews": [],
     "seller": null,
     "tags": [
          {
               "id": 1,
               "tag": "pedigree",
               "visit_count": 0,
               "created_at": "2024-04-04T10:40:41.000000Z",
               "updated_at": "2024-04-04T10:40:41.000000Z",
               "pivot": {
                    "product_id": 1,
                    "tag_id": 1
               }
          },
          {
               "id": 2,
               "tag": "dry food",
               "visit_count": 0,
               "created_at": "2024-04-04T10:40:41.000000Z",
               "updated_at": "2024-04-04T10:40:41.000000Z",
               "pivot": {
                    "product_id": 1,
                    "tag_id": 2
               }
          },
          {
               "id": 3,
               "tag": "dog food",
               "visit_count": 0,
               "created_at": "2024-04-04T10:40:41.000000Z",
               "updated_at": "2024-04-04T10:40:41.000000Z",
               "pivot": {
                    "product_id": 1,
                    "tag_id": 3
               }
          },
          {
               "id": 4,
               "tag": "dog dry food",
               "visit_count": 0,
               "created_at": "2024-04-04T10:40:41.000000Z",
               "updated_at": "2024-04-04T10:40:41.000000Z",
               "pivot": {
                    "product_id": 1,
                    "tag_id": 4
               }
          },
          {
               "id": 5,
               "tag": "pedigree food",
               "visit_count": 0,
               "created_at": "2024-04-04T10:40:41.000000Z",
               "updated_at": "2024-04-04T10:40:41.000000Z",
               "pivot": {
                    "product_id": 1,
                    "tag_id": 5
               }
          }
     ],
     "translations": []
}
```
 
</details>
 
## 8. 200 GET /api/v1/cart?guest_id=16
 
**Model**
 
Paste you model hear
 
<details>
 
<summary>Example</summary>
 
```json
[
     {
          "id": 2,
          "customer_id": 16,
          "cart_group_id": "guest-sBglx-1713538915",
          "product_id": 1,
          "product_type": "physical",
          "digital_product_type": null,
          "color": null,
          "choices": {
               "choice_1": "1 Kg"
          },
          "variations": {
               "Weight": "1 Kg"
          },
          "variant": "1Kg",
          "quantity": 1,
          "price": 269,
          "tax": 48.42,
          "discount": 26.9,
          "tax_model": "include",
          "slug": "pedigree-chicken-and-vegetables-adult-dry-dog-food-uvJj6q",
          "name": "Pedigree Chicken and Vegetables Adult Dry Dog Food",
          "thumbnail": "2024-04-04-660e83a98db91.png",
          "seller_id": 1,
          "seller_is": "admin",
          "created_at": "2024-04-19T15:01:55.000000Z",
          "updated_at": "2024-04-19T15:01:55.000000Z",
          "shop_info": "Petropolis",
          "shipping_cost": 0,
          "shipping_type": "order_wise",
          "is_guest": 1,
          "is_product_available": 1,
          "minimum_order_amount_info": 0,
          "free_delivery_order_amount": {
               "status": 0,
               "amount": 0,
               "percentage": 100,
               "amount_need": -242.1,
               "shipping_cost_saved": 0,
               "cart_id": "guest-sBglx-1713538915",
               "responsibility": "admin"
          },
          "product": {
               "id": 1,
               "name": "Pedigree Chicken and Vegetables Adult Dry Dog Food",
               "slug": "pedigree-chicken-and-vegetables-adult-dry-dog-food-uvJj6q",
               "current_stock": 70,
               "minimum_order_qty": 1,
               "total_current_stock": 10,
               "translations": [],
               "reviews": []
          },
          "shop": null
     }
]
```
 
</details>
 
## 9. 200 GET /api/v1/shipping-method/by-seller/1/admin
 
**Model**
 
Paste you model hear
 
<details>
 
<summary>Example</summary>
 
```json
[
     {
          "id": 2,
          "creator_id": 1,
          "creator_type": "admin",
          "title": "Normal Items",
          "cost": "100.00",
          "duration": "Same day",
          "status": true,
          "created_at": "2021-05-25T20:57:04.000000Z",
          "updated_at": "2024-04-04T09:00:57.000000Z"
     },
     {
          "id": 9,
          "creator_id": 1,
          "creator_type": "admin",
          "title": "Heavy & Veterinary Products",
          "cost": "100.00",
          "duration": "2-3 Days",
          "status": true,
          "created_at": "2024-04-04T09:00:44.000000Z",
          "updated_at": "2024-04-04T09:00:44.000000Z"
     }
]
```
 
</details>
 
## 10. 200 POST /api/v1/auth/register
 
**Model**
 
Paste you model hear
 
<details>
 
<summary>Example</summary>
 
```json
{
     "token": "eyJ0eXAiOiJKV1QiLCJhbGciOiJSUzI1NiJ9.eyJhdWQiOiIxIiwianRpIjoiYWIzN2YzMzM1Njc5MTEzYmU0ZWNkMGU0ZWVmZmRhOTU5MDZiYTIzZTA0ZGI0MGJiMGNiNzNmODgyZjY4NzgxYjcyMjBiMjJjZjc4ZDJiMWIiLCJpYXQiOjE3MTM1MzkzMjQuNzExMjA2OTEyOTk0Mzg0NzY1NjI1LCJuYmYiOjE3MTM1MzkzMjQuNzExMjEwMDEyNDM1OTEzMDg1OTM3NSwiZXhwIjoxNzQ1MDc1MzI0LjcwMDE5MDA2NzI5MTI1OTc2NTYyNSwic3ViIjoiMyIsInNjb3BlcyI6W119.e9sVeZQL0bvGOx0N_iIqW7Zn0RngBiRSqjHL_cLP2yqZe45qPpiqtjsTm_9OFK79xAGAhbFPVsuDMCB4V6YjBy3zAkFgpQVj7fqm7coqtJ7-aeHw9nF5HizaD0G4xW9wazUGKavu5fT_q-YIw-QsKE960TJnc8JqJi88x06Y0pPUDPF64MBcdRSatKxOL3yBtzqrS1U5xeGlQMvrh7it7hwxp8HoKoaR7jbQANvVnEzErn8v8V1nJMtfuDVQKMbmnDNm_FTnDLIbUVQ2hzAC6AbxFuCIf8qOL8igSQt2OfeAuPQz2l7VRBPgG7bnqTMSQnssX8cA0EkUrFI17sBSmHF0R-YyXU4dQopkTYjBiznIts3MQ-rF49b_bJj-TTeSzK8yoaLSnrzwr0XWDjlnOUidJNl7Llw55QRfltm3dl-q-ttI94FraEvnImfHJYn9lx2W_0QEcYvzOcBVQFXpmktDHEBPlkDvSIQ46KAv0qCkJhHn3QwFNo97oN5ff9s6lRRIsLhKqEk-XWlqt9sbaMxPa9GahCOqugKSm_ctq8bsc8MRUlTxvkCeLH7aujB2LK8ZwRmkIBZ8380i4y7IutZuLCCM8vZIOXZiffD9dxYvF0IKKQdyM85oqhIcVkGh_GiKPa2oi3Gc2mpCBbmHk2ffQ-0kJ4OBWTMgbNJFZd4"
}
```
 
</details>
 
## 11. 200 GET /api/v1/customer/info
 
**Model**
 
Paste you model hear
 
<details>
 
<summary>Example</summary>
 
```json
{
     "id": 3,
     "name": null,
     "f_name": "demo",
     "l_name": "user1",
     "phone": "+911234567890",
     "image": "def.png",
     "email": "demouser1@gmail.com",
     "email_verified_at": null,
     "created_at": "2024-04-19T15:08:44.000000Z",
     "updated_at": "2024-04-19T15:08:44.000000Z",
     "street_address": null,
     "country": null,
     "city": null,
     "zip": null,
     "house_no": null,
     "apartment_no": null,
     "cm_firebase_token": "dgioO5PXSVa79WqgG3IiX6:APA91bGs6RhWoX58-Pp9jSjgpQ6dNxyrjanTVG6YdJ-deKzdbrDcol_qvUoMcX0mkyM8uYJEQapvRi1mQy5fvWp9_wdnHPFbr-PuLbif4WYZLILbNc45pZ9s_dsib-XhOzQfAvD2FQtC",
     "is_active": 1,
     "payment_card_last_four": null,
     "payment_card_brand": null,
     "payment_card_fawry_token": null,
     "login_medium": null,
     "social_id": null,
     "is_phone_verified": 0,
     "temporary_token": "Xn0SXnQntlEoNR4SRF9tcwJLTeOurHWFqkDn04C1",
     "is_email_verified": 0,
     "wallet_balance": null,
     "loyalty_point": null,
     "login_hit_count": 0,
     "is_temp_blocked": 0,
     "temp_block_time": null,
     "referral_code": "VH7EGVOBZSESG9CG7XVB",
     "referred_by": null,
     "app_language": "en",
     "referral_user_count": 0,
     "orders_count": 0
}
```
 
</details>
 
## 12. 200 GET /api/v1/customer/wish-list
 
**Model**
 
Paste you model hear
 
<details>
 
<summary>Example</summary>
 
```json
[
     {
          "id": 2,
          "customer_id": 3,
          "product_id": 1,
          "created_at": "2024-04-19T15:10:29.000000Z",
          "updated_at": "2024-04-19T15:10:29.000000Z",
          "productFullInfo": {
               "id": 1,
               "added_by": "admin",
               "user_id": 1,
               "name": "Pedigree Chicken and Vegetables Adult Dry Dog Food",
               "slug": "pedigree-chicken-and-vegetables-adult-dry-dog-food-uvJj6q",
               "product_type": "physical",
               "category_ids": [
                    {
                         "id": "1",
                         "position": 1
                    },
                    {
                         "id": "2",
                         "position": 2
                    }
               ],
               "category_id": 1,
               "sub_category_id": 2,
               "sub_sub_category_id": null,
               "brand_id": 1,
               "unit": "kg",
               "min_qty": 1,
               "refundable": 1,
               "digital_product_type": null,
               "digital_file_ready": null,
               "images": [
                    "2024-04-04-660e83a921e35.webp",
                    "2024-04-04-660e83a93f1f2.webp",
                    "2024-04-04-660e83a9629b4.webp"
               ],
               "color_image": [],
               "thumbnail": "2024-04-04-660e83a98db91.png",
               "featured": null,
               "flash_deal": null,
               "video_provider": "youtube",
               "video_url": null,
               "colors": [],
               "variant_product": 0,
               "attributes": [
                    1
               ],
               "choice_options": [
                    {
                         "name": "choice_1",
                         "title": "Weight",
                         "options": [
                              "1 Kg",
                              "    2.8 Kg",
                              "    5.5 Kg",
                              "    10 Kg",
                              "    15 Kg",
                              "    20 Kg",
                              "    370 gm"
                         ]
                    }
               ],
               "variation": [
                    {
                         "type": "1Kg",
                         "price": 269,
                         "sku": "PCAVADDF-1KG",
                         "qty": 10
                    },
                    {
                         "type": "2.8Kg",
                         "price": 269,
                         "sku": "PCAVADDF-2.8KG",
                         "qty": 10
                    },
                    {
                         "type": "5.5Kg",
                         "price": 269,
                         "sku": "PCAVADDF-5.5KG",
                         "qty": 10
                    },
                    {
                         "type": "10Kg",
                         "price": 269,
                         "sku": "PCAVADDF-10KG",
                         "qty": 10
                    },
                    {
                         "type": "15Kg",
                         "price": 269,
                         "sku": "PCAVADDF-15KG",
                         "qty": 10
                    },
                    {
                         "type": "20Kg",
                         "price": 269,
                         "sku": "PCAVADDF-20KG",
                         "qty": 10
                    },
                    {
                         "type": "370gm",
                         "price": 100,
                         "sku": "PCAVADDF-370GM",
                         "qty": 10
                    }
               ],
               "published": 0,
               "unit_price": 269,
               "purchase_price": 0,
               "tax": 18,
               "tax_type": "percent",
               "tax_model": "include",
               "discount": 10,
               "discount_type": "percent",
               "current_stock": 70,
               "minimum_order_qty": 1,
               "details": "<p data-mce-fragment=\"1\" style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\">Pedigree offers dogs complete and balanced dog food for a healthy and active life. Pedigree Adult Dry Dog Food in Chicken and Vegetable Flavor is a wholesome meal packed with essential nutrients vital to the overall health of your pet. The goodness of quality ingredients, including chicken and vegetables, blends into a tasty and healthy diet for your furry friend. When fed as per the feeding guidelines (refer to the back of the pack), you will see the 5 Signs of Good Health in your pet. These signs include healthy skin and coat (from a blend of Zinc and Omega Fatty Acids); strong bones and teeth (from Ca:P ratio and levels); healthy digestion (from dietary fiber); strong muscles (from Protein); strong immune system (from Vitamins (Vitamin E) and Minerals). At Pedigree, recipes are developed based on research from the Waltham Centre for Pet Nutrition. Every product from Pedigree meets the requirements laid down by NRC 2006 of the U.S. National Academy of Science. Give your furry companion healthy and lip-smacking mealtimes with Pedigree.</p><p data-mce-fragment=\"1\" style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span style=\"font-weight: 700;\">Key Features:</span></p><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">COMPLETE AND BALANCED DOG FOOD: Pedigree Wet Dog Food provides complete and balanced nutrition for adult dogs.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">DELICIOUS FLAVOR: Pedigree Adult Dry Dog Food in Chicken and Vegetables Flavor is packed with mouth-watering kibbles to delight your dog.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">QUALITY INGREDIENTS: This tasty and healthy food is made with high-quality ingredients, including chicken and vegetables for the right nutrition.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">NOURISHING FOOD: This dry dog food is specially formulated for adult dogs with essential nutrients and high protein.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">5 SIGNS OF GOOD HEALTH: It gives them a shiny coat and keeps their bones and teeth strong. It also helps with healthy digestion, builds strong muscles, and strengthens the immune system.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"></ul><p style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span style=\"font-weight: 700;\">Ingredients:</span></p><p style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span data-sheets-root=\"1\" data-sheets-value=\"{\"1\":2,\"2\":\"Cereals and Cereal by-products, Chicken and Chicken by-products and/or Meat and Meat by-products, Soybean Meal, Soybean Oil, Di-calcium phosphate, Iodised Salt, Antioxidants, Distilled Monoglycerides, Choline Chloride, Vitamins and Minerals, Carrot Powder, Peas Powder, Zinc Sulphate Monohydrate, Permitted Preservatives & Flavors.\"}\" data-sheets-userformat=\"{\"2\":14591,\"3\":{\"1\":0,\"3\":1},\"4\":{\"1\":3,\"3\":2},\"5\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"6\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"7\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"8\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"9\":1,\"10\":1,\"14\":{\"1\":3,\"3\":1},\"15\":\"Calibri\",\"16\":11}\">Cereals and Cereal by-products, Chicken and Chicken by-products and/or Meat and Meat by-products, Soybean Meal, Soybean Oil, Di-calcium phosphate, Iodised Salt, Antioxidants, Distilled Monoglycerides, Choline Chloride, Vitamins and Minerals, Carrot Powder, Peas Powder, Zinc Sulphate Monohydrate, Permitted Preservatives & Flavors.</span></p>",
               "free_shipping": 0,
               "attachment": null,
               "created_at": "2024-04-04T10:40:41.000000Z",
               "updated_at": "2024-04-08T11:43:55.000000Z",
               "status": 1,
               "featured_status": 1,
               "meta_title": "Pedigree Chicken and Vegetables Adult Dry Dog Food",
               "meta_description": "Pedigree offers dogs complete and balanced dog food for a healthy and active life. Pedigree Adult Dry Dog Food in Chicken and Vegetable Flavor is a wholesome meal packed with essential nutrie",
               "meta_image": "2024-04-04-660e83a9b9dba.png",
               "request_status": 1,
               "denied_note": null,
               "shipping_cost": 0,
               "multiply_qty": 0,
               "temp_shipping_cost": null,
               "is_shipping_cost_updated": null,
               "code": "164357",
               "translations": [],
               "reviews": [],
               "colors_formatted": []
          },
          "product_full_info": {
               "id": 1,
               "added_by": "admin",
               "user_id": 1,
               "name": "Pedigree Chicken and Vegetables Adult Dry Dog Food",
               "slug": "pedigree-chicken-and-vegetables-adult-dry-dog-food-uvJj6q",
               "product_type": "physical",
               "category_ids": "[{\"id\":\"1\",\"position\":1},{\"id\":\"2\",\"position\":2}]",
               "category_id": 1,
               "sub_category_id": 2,
               "sub_sub_category_id": null,
               "brand_id": 1,
               "unit": "kg",
               "min_qty": 1,
               "refundable": 1,
               "digital_product_type": null,
               "digital_file_ready": null,
               "images": "[\"2024-04-04-660e83a921e35.webp\",\"2024-04-04-660e83a93f1f2.webp\",\"2024-04-04-660e83a9629b4.webp\"]",
               "color_image": "[]",
               "thumbnail": "2024-04-04-660e83a98db91.png",
               "featured": null,
               "flash_deal": null,
               "video_provider": "youtube",
               "video_url": null,
               "colors": "[]",
               "variant_product": 0,
               "attributes": "[\"1\"]",
               "choice_options": "[{\"name\":\"choice_1\",\"title\":\"Weight\",\"options\":[\"1 Kg\",\"    2.8 Kg\",\"    5.5 Kg\",\"    10 Kg\",\"    15 Kg\",\"    20 Kg\",\"    370 gm\"]}]",
               "variation": "[{\"type\":\"1Kg\",\"price\":269,\"sku\":\"PCAVADDF-1KG\",\"qty\":10},{\"type\":\"2.8Kg\",\"price\":269,\"sku\":\"PCAVADDF-2.8KG\",\"qty\":10},{\"type\":\"5.5Kg\",\"price\":269,\"sku\":\"PCAVADDF-5.5KG\",\"qty\":10},{\"type\":\"10Kg\",\"price\":269,\"sku\":\"PCAVADDF-10KG\",\"qty\":10},{\"type\":\"15Kg\",\"price\":269,\"sku\":\"PCAVADDF-15KG\",\"qty\":10},{\"type\":\"20Kg\",\"price\":269,\"sku\":\"PCAVADDF-20KG\",\"qty\":10},{\"type\":\"370gm\",\"price\":100,\"sku\":\"PCAVADDF-370GM\",\"qty\":10}]",
               "published": 0,
               "unit_price": 269,
               "purchase_price": 0,
               "tax": 18,
               "tax_type": "percent",
               "tax_model": "include",
               "discount": 10,
               "discount_type": "percent",
               "current_stock": 70,
               "minimum_order_qty": 1,
               "details": "<p data-mce-fragment=\"1\" style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\">Pedigree offers dogs complete and balanced dog food for a healthy and active life. Pedigree Adult Dry Dog Food in Chicken and Vegetable Flavor is a wholesome meal packed with essential nutrients vital to the overall health of your pet. The goodness of quality ingredients, including chicken and vegetables, blends into a tasty and healthy diet for your furry friend. When fed as per the feeding guidelines (refer to the back of the pack), you will see the 5 Signs of Good Health in your pet. These signs include healthy skin and coat (from a blend of Zinc and Omega Fatty Acids); strong bones and teeth (from Ca:P ratio and levels); healthy digestion (from dietary fiber); strong muscles (from Protein); strong immune system (from Vitamins (Vitamin E) and Minerals). At Pedigree, recipes are developed based on research from the Waltham Centre for Pet Nutrition. Every product from Pedigree meets the requirements laid down by NRC 2006 of the U.S. National Academy of Science. Give your furry companion healthy and lip-smacking mealtimes with Pedigree.</p><p data-mce-fragment=\"1\" style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span style=\"font-weight: 700;\">Key Features:</span></p><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">COMPLETE AND BALANCED DOG FOOD: Pedigree Wet Dog Food provides complete and balanced nutrition for adult dogs.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">DELICIOUS FLAVOR: Pedigree Adult Dry Dog Food in Chicken and Vegetables Flavor is packed with mouth-watering kibbles to delight your dog.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">QUALITY INGREDIENTS: This tasty and healthy food is made with high-quality ingredients, including chicken and vegetables for the right nutrition.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">NOURISHING FOOD: This dry dog food is specially formulated for adult dogs with essential nutrients and high protein.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">5 SIGNS OF GOOD HEALTH: It gives them a shiny coat and keeps their bones and teeth strong. It also helps with healthy digestion, builds strong muscles, and strengthens the immune system.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"></ul><p style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span style=\"font-weight: 700;\">Ingredients:</span></p><p style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span data-sheets-root=\"1\" data-sheets-value=\"{\"1\":2,\"2\":\"Cereals and Cereal by-products, Chicken and Chicken by-products and/or Meat and Meat by-products, Soybean Meal, Soybean Oil, Di-calcium phosphate, Iodised Salt, Antioxidants, Distilled Monoglycerides, Choline Chloride, Vitamins and Minerals, Carrot Powder, Peas Powder, Zinc Sulphate Monohydrate, Permitted Preservatives & Flavors.\"}\" data-sheets-userformat=\"{\"2\":14591,\"3\":{\"1\":0,\"3\":1},\"4\":{\"1\":3,\"3\":2},\"5\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"6\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"7\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"8\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"9\":1,\"10\":1,\"14\":{\"1\":3,\"3\":1},\"15\":\"Calibri\",\"16\":11}\">Cereals and Cereal by-products, Chicken and Chicken by-products and/or Meat and Meat by-products, Soybean Meal, Soybean Oil, Di-calcium phosphate, Iodised Salt, Antioxidants, Distilled Monoglycerides, Choline Chloride, Vitamins and Minerals, Carrot Powder, Peas Powder, Zinc Sulphate Monohydrate, Permitted Preservatives & Flavors.</span></p>",
               "free_shipping": 0,
               "attachment": null,
               "created_at": "2024-04-04T10:40:41.000000Z",
               "updated_at": "2024-04-08T11:43:55.000000Z",
               "status": 1,
               "featured_status": 1,
               "meta_title": "Pedigree Chicken and Vegetables Adult Dry Dog Food",
               "meta_description": "Pedigree offers dogs complete and balanced dog food for a healthy and active life. Pedigree Adult Dry Dog Food in Chicken and Vegetable Flavor is a wholesome meal packed with essential nutrie",
               "meta_image": "2024-04-04-660e83a9b9dba.png",
               "request_status": 1,
               "denied_note": null,
               "shipping_cost": 0,
               "multiply_qty": 0,
               "temp_shipping_cost": null,
               "is_shipping_cost_updated": null,
               "code": "164357",
               "translations": [],
               "reviews": []
          }
     }
]
```
 
</details>
 
## 13. 200 GET /api/v1/customer/get-restricted-zip-list
 
**Model**
 
Paste you model hear
 
<details>
 
<summary>Example</summary>
 
```json
[
     {
          "id": 2,
          "zipcode": " 700007",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 3,
          "zipcode": " 700008",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 4,
          "zipcode": " 700009",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 5,
          "zipcode": " 700010",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 6,
          "zipcode": " 700011",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 7,
          "zipcode": " 700012",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 8,
          "zipcode": " 700013",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 9,
          "zipcode": " 700014",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 10,
          "zipcode": " 700015",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 11,
          "zipcode": " 700016",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 12,
          "zipcode": " 700017",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 13,
          "zipcode": " 700018",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 14,
          "zipcode": " 700019",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 15,
          "zipcode": " 700020",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 16,
          "zipcode": " 700021",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 17,
          "zipcode": " 700022",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 18,
          "zipcode": " 700023",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 19,
          "zipcode": " 700024",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 20,
          "zipcode": " 700025",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 21,
          "zipcode": " 700026",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 22,
          "zipcode": " 700027",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 23,
          "zipcode": " 700029",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 24,
          "zipcode": " 700031",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 25,
          "zipcode": " 700032",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 26,
          "zipcode": " 700033",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 27,
          "zipcode": " 700034",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 28,
          "zipcode": " 700038",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 29,
          "zipcode": " 700040",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 30,
          "zipcode": " 700041",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 31,
          "zipcode": " 700042",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 32,
          "zipcode": " 700043",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 33,
          "zipcode": " 700044",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 34,
          "zipcode": " 700045",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 35,
          "zipcode": " 700046",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 36,
          "zipcode": " 700047",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 37,
          "zipcode": " 700053",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 38,
          "zipcode": " 700054",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 39,
          "zipcode": " 700060",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 40,
          "zipcode": " 700061",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 41,
          "zipcode": " 700062",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 42,
          "zipcode": " 700063",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 43,
          "zipcode": " 700066",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 44,
          "zipcode": " 700068",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 45,
          "zipcode": " 700069",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 46,
          "zipcode": " 700071",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 47,
          "zipcode": " 700072",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 48,
          "zipcode": " 700073",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 49,
          "zipcode": " 700075",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 50,
          "zipcode": " 700078",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 51,
          "zipcode": " 700082",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 52,
          "zipcode": " 700085",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 53,
          "zipcode": " 700086",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 54,
          "zipcode": " 700087",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 55,
          "zipcode": " 700088",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 56,
          "zipcode": " 700089",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 57,
          "zipcode": " 700091",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 58,
          "zipcode": " 700092",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 59,
          "zipcode": " 700094",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 60,
          "zipcode": " 700095",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 61,
          "zipcode": " 700099",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 62,
          "zipcode": " 700107",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     },
     {
          "id": 1,
          "zipcode": "700001",
          "created_at": "2024-04-04T09:57:51.000000Z",
          "updated_at": "2024-04-04T09:57:51.000000Z"
     }
]
```
 
</details>
 
## 14. 200 GET /api/v1/mapapi/geocode-api?lat=0.0&lng=0.0
 
**Model**
 
Paste you model hear
 
<details>
 
<summary>Example</summary>
 
```json
{
     "error_message": "You must use an API key to authenticate each request to Google Maps Platform APIs. For additional information, please refer to http://g.co/dev/maps-no-account",
     "results": [],
     "status": "REQUEST_DENIED"
}
```
 
</details>
 
## 15. 200 GET /api/v1/customer/address/list?guest_id=16
 
**Model**
 
Paste you model hear
 
<details>
 
<summary>Example</summary>
 
```json
[
     {
          "id": 2,
          "customer_id": "3",
          "is_guest": false,
          "contact_person_name": "demo user1",
          "email": null,
          "address_type": "home",
          "address": "Rabindrapally",
          "city": "Kolkata",
          "zip": "700094",
          "phone": "+91+911234567890",
          "created_at": "2024-04-19T15:11:40.000000Z",
          "updated_at": "2024-04-19T15:11:40.000000Z",
          "state": null,
          "country": "भारत",
          "latitude": "0.0",
          "longitude": "0.0",
          "is_billing": false
     }
]
```
 
</details>
 
## 16. 200 GET /api/v1/customer/order/list?limit=10&offset=1&status=ongoing&type=null
 
**Model**
 
Paste you model hear
 
<details>
 
<summary>Example</summary>
 
```json
{
     "total_size": 1,
     "limit": "10",
     "offset": "1",
     "orders": [
          {
               "id": 100002,
               "customer_id": 3,
               "is_guest": false,
               "customer_type": "customer",
               "payment_status": "unpaid",
               "order_status": "pending",
               "payment_method": "cash_on_delivery",
               "transaction_ref": "",
               "payment_by": null,
               "payment_note": null,
               "order_amount": 342.1,
               "admin_commission": "0.00",
               "is_pause": false,
               "cause": null,
               "shipping_address": "2",
               "created_at": "2024-04-19T15:12:09.000000Z",
               "updated_at": "2024-04-19T15:12:09.000000Z",
               "discount_amount": 0,
               "discount_type": null,
               "coupon_code": "0",
               "coupon_discount_bearer": "inhouse",
               "shipping_responsibility": "inhouse_shipping",
               "shipping_method_id": 2,
               "shipping_cost": 100,
               "is_shipping_free": false,
               "order_group_id": "9588-Vur39-1713539529",
               "verification_code": "306439",
               "verification_status": false,
               "seller_id": 1,
               "seller_is": "admin",
               "shipping_address_data": {
                    "id": 2,
                    "customer_id": "3",
                    "is_guest": false,
                    "contact_person_name": "demo user1",
                    "email": null,
                    "address_type": "home",
                    "address": "Rabindrapally",
                    "city": "Kolkata",
                    "zip": "700094",
                    "phone": "+91+911234567890",
                    "created_at": "2024-04-19T15:11:40.000000Z",
                    "updated_at": "2024-04-19T15:11:40.000000Z",
                    "state": null,
                    "country": "भारत",
                    "latitude": "0.0",
                    "longitude": "0.0",
                    "is_billing": false
               },
               "delivery_man_id": null,
               "deliveryman_charge": 0,
               "expected_delivery_date": null,
               "order_note": null,
               "billing_address": 2,
               "billing_address_data": {
                    "id": 2,
                    "customer_id": "3",
                    "is_guest": false,
                    "contact_person_name": "demo user1",
                    "email": null,
                    "address_type": "home",
                    "address": "Rabindrapally",
                    "city": "Kolkata",
                    "zip": "700094",
                    "phone": "+91+911234567890",
                    "created_at": "2024-04-19T15:11:40.000000Z",
                    "updated_at": "2024-04-19T15:11:40.000000Z",
                    "state": null,
                    "country": "भारत",
                    "latitude": "0.0",
                    "longitude": "0.0",
                    "is_billing": false
               },
               "order_type": "default_type",
               "extra_discount": 0,
               "extra_discount_type": null,
               "free_delivery_bearer": "admin",
               "checked": false,
               "shipping_type": "order_wise",
               "delivery_type": null,
               "delivery_service_name": null,
               "third_party_delivery_tracking_id": null,
               "order_details_count": "1",
               "details": [
                    {
                         "id": 2,
                         "order_id": 100002,
                         "product_id": 1,
                         "seller_id": 1,
                         "digital_file_after_sell": null,
                         "product_details": "{\"id\":1,\"added_by\":\"admin\",\"user_id\":1,\"name\":\"Pedigree Chicken and Vegetables Adult Dry Dog Food\",\"slug\":\"pedigree-chicken-and-vegetables-adult-dry-dog-food-uvJj6q\",\"product_type\":\"physical\",\"category_ids\":\"[{\\\"id\\\":\\\"1\\\",\\\"position\\\":1},{\\\"id\\\":\\\"2\\\",\\\"position\\\":2}]\",\"category_id\":1,\"sub_category_id\":2,\"sub_sub_category_id\":null,\"brand_id\":1,\"unit\":\"kg\",\"min_qty\":1,\"refundable\":1,\"digital_product_type\":null,\"digital_file_ready\":null,\"images\":\"[\\\"2024-04-04-660e83a921e35.webp\\\",\\\"2024-04-04-660e83a93f1f2.webp\\\",\\\"2024-04-04-660e83a9629b4.webp\\\"]\",\"color_image\":\"[]\",\"thumbnail\":\"2024-04-04-660e83a98db91.png\",\"featured\":null,\"flash_deal\":null,\"video_provider\":\"youtube\",\"video_url\":null,\"colors\":\"[]\",\"variant_product\":0,\"attributes\":\"[\\\"1\\\"]\",\"choice_options\":\"[{\\\"name\\\":\\\"choice_1\\\",\\\"title\\\":\\\"Weight\\\",\\\"options\\\":[\\\"1 Kg\\\",\\\"    2.8 Kg\\\",\\\"    5.5 Kg\\\",\\\"    10 Kg\\\",\\\"    15 Kg\\\",\\\"    20 Kg\\\",\\\"    370 gm\\\"]}]\",\"variation\":\"[{\\\"type\\\":\\\"1Kg\\\",\\\"price\\\":269,\\\"sku\\\":\\\"PCAVADDF-1KG\\\",\\\"qty\\\":10},{\\\"type\\\":\\\"2.8Kg\\\",\\\"price\\\":269,\\\"sku\\\":\\\"PCAVADDF-2.8KG\\\",\\\"qty\\\":10},{\\\"type\\\":\\\"5.5Kg\\\",\\\"price\\\":269,\\\"sku\\\":\\\"PCAVADDF-5.5KG\\\",\\\"qty\\\":10},{\\\"type\\\":\\\"10Kg\\\",\\\"price\\\":269,\\\"sku\\\":\\\"PCAVADDF-10KG\\\",\\\"qty\\\":10},{\\\"type\\\":\\\"15Kg\\\",\\\"price\\\":269,\\\"sku\\\":\\\"PCAVADDF-15KG\\\",\\\"qty\\\":10},{\\\"type\\\":\\\"20Kg\\\",\\\"price\\\":269,\\\"sku\\\":\\\"PCAVADDF-20KG\\\",\\\"qty\\\":10},{\\\"type\\\":\\\"370gm\\\",\\\"price\\\":100,\\\"sku\\\":\\\"PCAVADDF-370GM\\\",\\\"qty\\\":10}]\",\"published\":0,\"unit_price\":269,\"purchase_price\":0,\"tax\":18,\"tax_type\":\"percent\",\"tax_model\":\"include\",\"discount\":10,\"discount_type\":\"percent\",\"current_stock\":70,\"minimum_order_qty\":1,\"details\":\"<p data-mce-fragment=\\\"1\\\" style=\\\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\\\">Pedigree offers dogs complete and balanced dog food for a healthy and active life. Pedigree Adult Dry Dog Food in Chicken and Vegetable Flavor is a wholesome meal packed with essential nutrients vital to the overall health of your pet. The goodness of quality ingredients, including chicken and vegetables, blends into a tasty and healthy diet for your furry friend. When fed as per the feeding guidelines (refer to the back of the pack), you will see the 5 Signs of Good Health in your pet. These signs include healthy skin and coat (from a blend of Zinc and Omega Fatty Acids); strong bones and teeth (from Ca:P ratio and levels); healthy digestion (from dietary fiber); strong muscles (from Protein); strong immune system (from Vitamins (Vitamin E) and Minerals). At Pedigree, recipes are developed based on research from the Waltham Centre for Pet Nutrition. Every product from Pedigree meets the requirements laid down by NRC 2006 of the U.S. National Academy of Science. Give your furry companion healthy and lip-smacking mealtimes with Pedigree.<\\/p><p data-mce-fragment=\\\"1\\\" style=\\\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\\\"><span style=\\\"font-weight: 700;\\\">Key Features:<\\/span><\\/p><ul style=\\\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\\\"><li style=\\\"margin-bottom: 0.25em;\\\">COMPLETE AND BALANCED DOG FOOD: Pedigree Wet Dog Food provides complete and balanced nutrition for adult dogs.<\\/li><\\/ul><ul style=\\\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\\\"><li style=\\\"margin-bottom: 0.25em;\\\">DELICIOUS FLAVOR: Pedigree Adult Dry Dog Food in Chicken and Vegetables Flavor is packed with mouth-watering kibbles to delight your dog.<\\/li><\\/ul><ul style=\\\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\\\"><li style=\\\"margin-bottom: 0.25em;\\\">QUALITY\\u00a0INGREDIENTS:\\u00a0This tasty and healthy food is made with high-quality ingredients, including chicken and vegetables for the right nutrition.<\\/li><\\/ul><ul style=\\\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\\\"><li style=\\\"margin-bottom: 0.25em;\\\">NOURISHING FOOD:\\u00a0This dry dog food is specially formulated for adult dogs with essential nutrients and high protein.<\\/li><\\/ul><ul style=\\\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\\\"><li style=\\\"margin-bottom: 0.25em;\\\">5 SIGNS OF GOOD HEALTH: It gives them a shiny coat and keeps their bones and teeth strong. It also helps with healthy digestion, builds strong muscles, and strengthens the immune system.<\\/li><\\/ul><ul style=\\\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\\\"><\\/ul><p style=\\\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\\\"><span style=\\\"font-weight: 700;\\\">Ingredients:<\\/span><\\/p><p style=\\\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\\\"><span data-sheets-root=\\\"1\\\" data-sheets-value=\\\"{\\\"1\\\":2,\\\"2\\\":\\\"Cereals and Cereal by-products, Chicken and Chicken by-products and\\/or Meat and Meat by-products, Soybean Meal, Soybean Oil, Di-calcium phosphate, Iodised Salt, Antioxidants, Distilled Monoglycerides, Choline Chloride, Vitamins and Minerals, Carrot Powder, Peas Powder, Zinc Sulphate Monohydrate, Permitted Preservatives & Flavors.\\\"}\\\" data-sheets-userformat=\\\"{\\\"2\\\":14591,\\\"3\\\":{\\\"1\\\":0,\\\"3\\\":1},\\\"4\\\":{\\\"1\\\":3,\\\"3\\\":2},\\\"5\\\":{\\\"1\\\":[{\\\"1\\\":2,\\\"2\\\":0,\\\"5\\\":{\\\"1\\\":2,\\\"2\\\":0}},{\\\"1\\\":0,\\\"2\\\":0,\\\"3\\\":3},{\\\"1\\\":1,\\\"2\\\":0,\\\"4\\\":1}]},\\\"6\\\":{\\\"1\\\":[{\\\"1\\\":2,\\\"2\\\":0,\\\"5\\\":{\\\"1\\\":2,\\\"2\\\":0}},{\\\"1\\\":0,\\\"2\\\":0,\\\"3\\\":3},{\\\"1\\\":1,\\\"2\\\":0,\\\"4\\\":1}]},\\\"7\\\":{\\\"1\\\":[{\\\"1\\\":2,\\\"2\\\":0,\\\"5\\\":{\\\"1\\\":2,\\\"2\\\":0}},{\\\"1\\\":0,\\\"2\\\":0,\\\"3\\\":3},{\\\"1\\\":1,\\\"2\\\":0,\\\"4\\\":1}]},\\\"8\\\":{\\\"1\\\":[{\\\"1\\\":2,\\\"2\\\":0,\\\"5\\\":{\\\"1\\\":2,\\\"2\\\":0}},{\\\"1\\\":0,\\\"2\\\":0,\\\"3\\\":3},{\\\"1\\\":1,\\\"2\\\":0,\\\"4\\\":1}]},\\\"9\\\":1,\\\"10\\\":1,\\\"14\\\":{\\\"1\\\":3,\\\"3\\\":1},\\\"15\\\":\\\"Calibri\\\",\\\"16\\\":11}\\\">Cereals and Cereal by-products, Chicken and Chicken by-products and\\/or Meat and Meat by-products, Soybean Meal, Soybean Oil, Di-calcium phosphate, Iodised Salt, Antioxidants, Distilled Monoglycerides, Choline Chloride, Vitamins and Minerals, Carrot Powder, Peas Powder, Zinc Sulphate Monohydrate, Permitted Preservatives & Flavors.<\\/span><\\/p>\",\"free_shipping\":0,\"attachment\":null,\"created_at\":\"2024-04-04T10:40:41.000000Z\",\"updated_at\":\"2024-04-08T11:43:55.000000Z\",\"status\":1,\"featured_status\":1,\"meta_title\":\"Pedigree Chicken and Vegetables Adult Dry Dog Food\",\"meta_description\":\"Pedigree offers dogs complete and balanced dog food for a healthy and active life. Pedigree Adult Dry Dog Food in Chicken and Vegetable Flavor is a wholesome meal packed with essential nutrie\",\"meta_image\":\"2024-04-04-660e83a9b9dba.png\",\"request_status\":1,\"denied_note\":null,\"shipping_cost\":0,\"multiply_qty\":0,\"temp_shipping_cost\":null,\"is_shipping_cost_updated\":null,\"code\":\"164357\",\"translations\":[],\"reviews\":[]}",
                         "qty": 1,
                         "price": 220.58,
                         "tax": 48.42,
                         "discount": 26.9,
                         "tax_model": "include",
                         "delivery_status": "pending",
                         "payment_status": "unpaid",
                         "created_at": "2024-04-19T15:12:09.000000Z",
                         "updated_at": "2024-04-19T15:12:09.000000Z",
                         "shipping_method_id": null,
                         "variant": "1Kg",
                         "variation": "{\"Weight\":\"1 Kg\"}",
                         "discount_type": "discount_on_product",
                         "is_stock_decreased": 1,
                         "refund_request": 0,
                         "product": {
                              "id": 1,
                              "added_by": "admin",
                              "user_id": 1,
                              "name": "Pedigree Chicken and Vegetables Adult Dry Dog Food",
                              "slug": "pedigree-chicken-and-vegetables-adult-dry-dog-food-uvJj6q",
                              "product_type": "physical",
                              "category_ids": "[{\"id\":\"1\",\"position\":1},{\"id\":\"2\",\"position\":2}]",
                              "category_id": 1,
                              "sub_category_id": 2,
                              "sub_sub_category_id": null,
                              "brand_id": 1,
                              "unit": "kg",
                              "min_qty": 1,
                              "refundable": 1,
                              "digital_product_type": null,
                              "digital_file_ready": null,
                              "images": "[\"2024-04-04-660e83a921e35.webp\",\"2024-04-04-660e83a93f1f2.webp\",\"2024-04-04-660e83a9629b4.webp\"]",
                              "color_image": "[]",
                              "thumbnail": "2024-04-04-660e83a98db91.png",
                              "featured": null,
                              "flash_deal": null,
                              "video_provider": "youtube",
                              "video_url": null,
                              "colors": "[]",
                              "variant_product": 0,
                              "attributes": "[\"1\"]",
                              "choice_options": "[{\"name\":\"choice_1\",\"title\":\"Weight\",\"options\":[\"1 Kg\",\"    2.8 Kg\",\"    5.5 Kg\",\"    10 Kg\",\"    15 Kg\",\"    20 Kg\",\"    370 gm\"]}]",
                              "variation": "[{\"type\":\"1Kg\",\"price\":269,\"sku\":\"PCAVADDF-1KG\",\"qty\":9},{\"type\":\"2.8Kg\",\"price\":269,\"sku\":\"PCAVADDF-2.8KG\",\"qty\":10},{\"type\":\"5.5Kg\",\"price\":269,\"sku\":\"PCAVADDF-5.5KG\",\"qty\":10},{\"type\":\"10Kg\",\"price\":269,\"sku\":\"PCAVADDF-10KG\",\"qty\":10},{\"type\":\"15Kg\",\"price\":269,\"sku\":\"PCAVADDF-15KG\",\"qty\":10},{\"type\":\"20Kg\",\"price\":269,\"sku\":\"PCAVADDF-20KG\",\"qty\":10},{\"type\":\"370gm\",\"price\":100,\"sku\":\"PCAVADDF-370GM\",\"qty\":10}]",
                              "published": 0,
                              "unit_price": 269,
                              "purchase_price": 0,
                              "tax": 18,
                              "tax_type": "percent",
                              "tax_model": "include",
                              "discount": 10,
                              "discount_type": "percent",
                              "current_stock": 69,
                              "minimum_order_qty": 1,
                              "details": "<p data-mce-fragment=\"1\" style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\">Pedigree offers dogs complete and balanced dog food for a healthy and active life. Pedigree Adult Dry Dog Food in Chicken and Vegetable Flavor is a wholesome meal packed with essential nutrients vital to the overall health of your pet. The goodness of quality ingredients, including chicken and vegetables, blends into a tasty and healthy diet for your furry friend. When fed as per the feeding guidelines (refer to the back of the pack), you will see the 5 Signs of Good Health in your pet. These signs include healthy skin and coat (from a blend of Zinc and Omega Fatty Acids); strong bones and teeth (from Ca:P ratio and levels); healthy digestion (from dietary fiber); strong muscles (from Protein); strong immune system (from Vitamins (Vitamin E) and Minerals). At Pedigree, recipes are developed based on research from the Waltham Centre for Pet Nutrition. Every product from Pedigree meets the requirements laid down by NRC 2006 of the U.S. National Academy of Science. Give your furry companion healthy and lip-smacking mealtimes with Pedigree.</p><p data-mce-fragment=\"1\" style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span style=\"font-weight: 700;\">Key Features:</span></p><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">COMPLETE AND BALANCED DOG FOOD: Pedigree Wet Dog Food provides complete and balanced nutrition for adult dogs.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">DELICIOUS FLAVOR: Pedigree Adult Dry Dog Food in Chicken and Vegetables Flavor is packed with mouth-watering kibbles to delight your dog.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">QUALITY INGREDIENTS: This tasty and healthy food is made with high-quality ingredients, including chicken and vegetables for the right nutrition.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">NOURISHING FOOD: This dry dog food is specially formulated for adult dogs with essential nutrients and high protein.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">5 SIGNS OF GOOD HEALTH: It gives them a shiny coat and keeps their bones and teeth strong. It also helps with healthy digestion, builds strong muscles, and strengthens the immune system.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"></ul><p style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span style=\"font-weight: 700;\">Ingredients:</span></p><p style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span data-sheets-root=\"1\" data-sheets-value=\"{\"1\":2,\"2\":\"Cereals and Cereal by-products, Chicken and Chicken by-products and/or Meat and Meat by-products, Soybean Meal, Soybean Oil, Di-calcium phosphate, Iodised Salt, Antioxidants, Distilled Monoglycerides, Choline Chloride, Vitamins and Minerals, Carrot Powder, Peas Powder, Zinc Sulphate Monohydrate, Permitted Preservatives & Flavors.\"}\" data-sheets-userformat=\"{\"2\":14591,\"3\":{\"1\":0,\"3\":1},\"4\":{\"1\":3,\"3\":2},\"5\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"6\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"7\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"8\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"9\":1,\"10\":1,\"14\":{\"1\":3,\"3\":1},\"15\":\"Calibri\",\"16\":11}\">Cereals and Cereal by-products, Chicken and Chicken by-products and/or Meat and Meat by-products, Soybean Meal, Soybean Oil, Di-calcium phosphate, Iodised Salt, Antioxidants, Distilled Monoglycerides, Choline Chloride, Vitamins and Minerals, Carrot Powder, Peas Powder, Zinc Sulphate Monohydrate, Permitted Preservatives & Flavors.</span></p>",
                              "free_shipping": 0,
                              "attachment": null,
                              "created_at": "2024-04-04T10:40:41.000000Z",
                              "updated_at": "2024-04-19T15:12:09.000000Z",
                              "status": 1,
                              "featured_status": 1,
                              "meta_title": "Pedigree Chicken and Vegetables Adult Dry Dog Food",
                              "meta_description": "Pedigree offers dogs complete and balanced dog food for a healthy and active life. Pedigree Adult Dry Dog Food in Chicken and Vegetable Flavor is a wholesome meal packed with essential nutrie",
                              "meta_image": "2024-04-04-660e83a9b9dba.png",
                              "request_status": 1,
                              "denied_note": null,
                              "shipping_cost": 0,
                              "multiply_qty": 0,
                              "temp_shipping_cost": null,
                              "is_shipping_cost_updated": null,
                              "code": "164357",
                              "translations": [],
                              "reviews": []
                         }
                    }
               ],
               "delivery_man": null,
               "seller": null
          }
     ]
}
```
 
</details>
 
## 17. 200 GET /api/v1/customer/order/details?order_id=100002
 
**Model**
 
Paste you model hear
 
<details>
 
<summary>Example</summary>
 
```json
[
     {
          "id": 2,
          "order_id": 100002,
          "product_id": 1,
          "seller_id": 1,
          "digital_file_after_sell": null,
          "product_details": {
               "id": 1,
               "added_by": "admin",
               "user_id": 1,
               "name": "Pedigree Chicken and Vegetables Adult Dry Dog Food",
               "slug": "pedigree-chicken-and-vegetables-adult-dry-dog-food-uvJj6q",
               "product_type": "physical",
               "category_ids": [
                    {
                         "id": "1",
                         "position": 1
                    },
                    {
                         "id": "2",
                         "position": 2
                    }
               ],
               "category_id": 1,
               "sub_category_id": 2,
               "sub_sub_category_id": null,
               "brand_id": 1,
               "unit": "kg",
               "min_qty": 1,
               "refundable": 1,
               "digital_product_type": null,
               "digital_file_ready": null,
               "images": [
                    "2024-04-04-660e83a921e35.webp",
                    "2024-04-04-660e83a93f1f2.webp",
                    "2024-04-04-660e83a9629b4.webp"
               ],
               "color_image": [],
               "thumbnail": "2024-04-04-660e83a98db91.png",
               "featured": null,
               "flash_deal": null,
               "video_provider": "youtube",
               "video_url": null,
               "colors": [],
               "variant_product": 0,
               "attributes": [
                    1
               ],
               "choice_options": [
                    {
                         "name": "choice_1",
                         "title": "Weight",
                         "options": [
                              "1 Kg",
                              "    2.8 Kg",
                              "    5.5 Kg",
                              "    10 Kg",
                              "    15 Kg",
                              "    20 Kg",
                              "    370 gm"
                         ]
                    }
               ],
               "variation": [
                    {
                         "type": "1Kg",
                         "price": 269,
                         "sku": "PCAVADDF-1KG",
                         "qty": 10
                    },
                    {
                         "type": "2.8Kg",
                         "price": 269,
                         "sku": "PCAVADDF-2.8KG",
                         "qty": 10
                    },
                    {
                         "type": "5.5Kg",
                         "price": 269,
                         "sku": "PCAVADDF-5.5KG",
                         "qty": 10
                    },
                    {
                         "type": "10Kg",
                         "price": 269,
                         "sku": "PCAVADDF-10KG",
                         "qty": 10
                    },
                    {
                         "type": "15Kg",
                         "price": 269,
                         "sku": "PCAVADDF-15KG",
                         "qty": 10
                    },
                    {
                         "type": "20Kg",
                         "price": 269,
                         "sku": "PCAVADDF-20KG",
                         "qty": 10
                    },
                    {
                         "type": "370gm",
                         "price": 100,
                         "sku": "PCAVADDF-370GM",
                         "qty": 10
                    }
               ],
               "published": 0,
               "unit_price": 269,
               "purchase_price": 0,
               "tax": 18,
               "tax_type": "percent",
               "tax_model": "include",
               "discount": 10,
               "discount_type": "percent",
               "current_stock": 70,
               "minimum_order_qty": 1,
               "details": "<p data-mce-fragment=\"1\" style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\">Pedigree offers dogs complete and balanced dog food for a healthy and active life. Pedigree Adult Dry Dog Food in Chicken and Vegetable Flavor is a wholesome meal packed with essential nutrients vital to the overall health of your pet. The goodness of quality ingredients, including chicken and vegetables, blends into a tasty and healthy diet for your furry friend. When fed as per the feeding guidelines (refer to the back of the pack), you will see the 5 Signs of Good Health in your pet. These signs include healthy skin and coat (from a blend of Zinc and Omega Fatty Acids); strong bones and teeth (from Ca:P ratio and levels); healthy digestion (from dietary fiber); strong muscles (from Protein); strong immune system (from Vitamins (Vitamin E) and Minerals). At Pedigree, recipes are developed based on research from the Waltham Centre for Pet Nutrition. Every product from Pedigree meets the requirements laid down by NRC 2006 of the U.S. National Academy of Science. Give your furry companion healthy and lip-smacking mealtimes with Pedigree.</p><p data-mce-fragment=\"1\" style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span style=\"font-weight: 700;\">Key Features:</span></p><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">COMPLETE AND BALANCED DOG FOOD: Pedigree Wet Dog Food provides complete and balanced nutrition for adult dogs.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">DELICIOUS FLAVOR: Pedigree Adult Dry Dog Food in Chicken and Vegetables Flavor is packed with mouth-watering kibbles to delight your dog.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">QUALITY INGREDIENTS: This tasty and healthy food is made with high-quality ingredients, including chicken and vegetables for the right nutrition.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">NOURISHING FOOD: This dry dog food is specially formulated for adult dogs with essential nutrients and high protein.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">5 SIGNS OF GOOD HEALTH: It gives them a shiny coat and keeps their bones and teeth strong. It also helps with healthy digestion, builds strong muscles, and strengthens the immune system.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"></ul><p style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span style=\"font-weight: 700;\">Ingredients:</span></p><p style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span data-sheets-root=\"1\" data-sheets-value=\"{\"1\":2,\"2\":\"Cereals and Cereal by-products, Chicken and Chicken by-products and/or Meat and Meat by-products, Soybean Meal, Soybean Oil, Di-calcium phosphate, Iodised Salt, Antioxidants, Distilled Monoglycerides, Choline Chloride, Vitamins and Minerals, Carrot Powder, Peas Powder, Zinc Sulphate Monohydrate, Permitted Preservatives & Flavors.\"}\" data-sheets-userformat=\"{\"2\":14591,\"3\":{\"1\":0,\"3\":1},\"4\":{\"1\":3,\"3\":2},\"5\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"6\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"7\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"8\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"9\":1,\"10\":1,\"14\":{\"1\":3,\"3\":1},\"15\":\"Calibri\",\"16\":11}\">Cereals and Cereal by-products, Chicken and Chicken by-products and/or Meat and Meat by-products, Soybean Meal, Soybean Oil, Di-calcium phosphate, Iodised Salt, Antioxidants, Distilled Monoglycerides, Choline Chloride, Vitamins and Minerals, Carrot Powder, Peas Powder, Zinc Sulphate Monohydrate, Permitted Preservatives & Flavors.</span></p>",
               "free_shipping": 0,
               "attachment": null,
               "created_at": "2024-04-04T10:40:41.000000Z",
               "updated_at": "2024-04-08T11:43:55.000000Z",
               "status": 1,
               "featured_status": 1,
               "meta_title": "Pedigree Chicken and Vegetables Adult Dry Dog Food",
               "meta_description": "Pedigree offers dogs complete and balanced dog food for a healthy and active life. Pedigree Adult Dry Dog Food in Chicken and Vegetable Flavor is a wholesome meal packed with essential nutrie",
               "meta_image": "2024-04-04-660e83a9b9dba.png",
               "request_status": 1,
               "denied_note": null,
               "shipping_cost": 0,
               "multiply_qty": 0,
               "temp_shipping_cost": null,
               "is_shipping_cost_updated": null,
               "code": "164357",
               "translations": [],
               "reviews": [],
               "colors_formatted": []
          },
          "qty": 1,
          "price": 220.58,
          "tax": 48.42,
          "discount": 26.9,
          "tax_model": "include",
          "delivery_status": "pending",
          "payment_status": "unpaid",
          "created_at": "2024-04-19T15:12:09.000000Z",
          "updated_at": "2024-04-19T15:12:09.000000Z",
          "shipping_method_id": null,
          "variant": "1Kg",
          "variation": {
               "Weight": "1 Kg"
          },
          "discount_type": "discount_on_product",
          "is_stock_decreased": 1,
          "refund_request": 0,
          "product": {
               "id": 1,
               "added_by": "admin",
               "user_id": 1,
               "name": "Pedigree Chicken and Vegetables Adult Dry Dog Food",
               "slug": "pedigree-chicken-and-vegetables-adult-dry-dog-food-uvJj6q",
               "product_type": "physical",
               "category_ids": "[{\"id\":\"1\",\"position\":1},{\"id\":\"2\",\"position\":2}]",
               "category_id": 1,
               "sub_category_id": 2,
               "sub_sub_category_id": null,
               "brand_id": 1,
               "unit": "kg",
               "min_qty": 1,
               "refundable": 1,
               "digital_product_type": null,
               "digital_file_ready": null,
               "images": "[\"2024-04-04-660e83a921e35.webp\",\"2024-04-04-660e83a93f1f2.webp\",\"2024-04-04-660e83a9629b4.webp\"]",
               "color_image": "[]",
               "thumbnail": "2024-04-04-660e83a98db91.png",
               "featured": null,
               "flash_deal": null,
               "video_provider": "youtube",
               "video_url": null,
               "colors": "[]",
               "variant_product": 0,
               "attributes": "[\"1\"]",
               "choice_options": "[{\"name\":\"choice_1\",\"title\":\"Weight\",\"options\":[\"1 Kg\",\"    2.8 Kg\",\"    5.5 Kg\",\"    10 Kg\",\"    15 Kg\",\"    20 Kg\",\"    370 gm\"]}]",
               "variation": "[{\"type\":\"1Kg\",\"price\":269,\"sku\":\"PCAVADDF-1KG\",\"qty\":9},{\"type\":\"2.8Kg\",\"price\":269,\"sku\":\"PCAVADDF-2.8KG\",\"qty\":10},{\"type\":\"5.5Kg\",\"price\":269,\"sku\":\"PCAVADDF-5.5KG\",\"qty\":10},{\"type\":\"10Kg\",\"price\":269,\"sku\":\"PCAVADDF-10KG\",\"qty\":10},{\"type\":\"15Kg\",\"price\":269,\"sku\":\"PCAVADDF-15KG\",\"qty\":10},{\"type\":\"20Kg\",\"price\":269,\"sku\":\"PCAVADDF-20KG\",\"qty\":10},{\"type\":\"370gm\",\"price\":100,\"sku\":\"PCAVADDF-370GM\",\"qty\":10}]",
               "published": 0,
               "unit_price": 269,
               "purchase_price": 0,
               "tax": 18,
               "tax_type": "percent",
               "tax_model": "include",
               "discount": 10,
               "discount_type": "percent",
               "current_stock": 69,
               "minimum_order_qty": 1,
               "details": "<p data-mce-fragment=\"1\" style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\">Pedigree offers dogs complete and balanced dog food for a healthy and active life. Pedigree Adult Dry Dog Food in Chicken and Vegetable Flavor is a wholesome meal packed with essential nutrients vital to the overall health of your pet. The goodness of quality ingredients, including chicken and vegetables, blends into a tasty and healthy diet for your furry friend. When fed as per the feeding guidelines (refer to the back of the pack), you will see the 5 Signs of Good Health in your pet. These signs include healthy skin and coat (from a blend of Zinc and Omega Fatty Acids); strong bones and teeth (from Ca:P ratio and levels); healthy digestion (from dietary fiber); strong muscles (from Protein); strong immune system (from Vitamins (Vitamin E) and Minerals). At Pedigree, recipes are developed based on research from the Waltham Centre for Pet Nutrition. Every product from Pedigree meets the requirements laid down by NRC 2006 of the U.S. National Academy of Science. Give your furry companion healthy and lip-smacking mealtimes with Pedigree.</p><p data-mce-fragment=\"1\" style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span style=\"font-weight: 700;\">Key Features:</span></p><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">COMPLETE AND BALANCED DOG FOOD: Pedigree Wet Dog Food provides complete and balanced nutrition for adult dogs.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">DELICIOUS FLAVOR: Pedigree Adult Dry Dog Food in Chicken and Vegetables Flavor is packed with mouth-watering kibbles to delight your dog.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">QUALITY INGREDIENTS: This tasty and healthy food is made with high-quality ingredients, including chicken and vegetables for the right nutrition.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">NOURISHING FOOD: This dry dog food is specially formulated for adult dogs with essential nutrients and high protein.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><li style=\"margin-bottom: 0.25em;\">5 SIGNS OF GOOD HEALTH: It gives them a shiny coat and keeps their bones and teeth strong. It also helps with healthy digestion, builds strong muscles, and strengthens the immune system.</li></ul><ul style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 30px; padding: 0px; text-rendering: optimizelegibility; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"></ul><p style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span style=\"font-weight: 700;\">Ingredients:</span></p><p style=\"margin-right: 0px; margin-bottom: 15px; margin-left: 0px; color: rgb(0, 0, 0); font-family: Lato, serif; font-size: 16px; letter-spacing: 0.4px;\"><span data-sheets-root=\"1\" data-sheets-value=\"{\"1\":2,\"2\":\"Cereals and Cereal by-products, Chicken and Chicken by-products and/or Meat and Meat by-products, Soybean Meal, Soybean Oil, Di-calcium phosphate, Iodised Salt, Antioxidants, Distilled Monoglycerides, Choline Chloride, Vitamins and Minerals, Carrot Powder, Peas Powder, Zinc Sulphate Monohydrate, Permitted Preservatives & Flavors.\"}\" data-sheets-userformat=\"{\"2\":14591,\"3\":{\"1\":0,\"3\":1},\"4\":{\"1\":3,\"3\":2},\"5\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"6\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"7\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"8\":{\"1\":[{\"1\":2,\"2\":0,\"5\":{\"1\":2,\"2\":0}},{\"1\":0,\"2\":0,\"3\":3},{\"1\":1,\"2\":0,\"4\":1}]},\"9\":1,\"10\":1,\"14\":{\"1\":3,\"3\":1},\"15\":\"Calibri\",\"16\":11}\">Cereals and Cereal by-products, Chicken and Chicken by-products and/or Meat and Meat by-products, Soybean Meal, Soybean Oil, Di-calcium phosphate, Iodised Salt, Antioxidants, Distilled Monoglycerides, Choline Chloride, Vitamins and Minerals, Carrot Powder, Peas Powder, Zinc Sulphate Monohydrate, Permitted Preservatives & Flavors.</span></p>",
               "free_shipping": 0,
               "attachment": null,
               "created_at": "2024-04-04T10:40:41.000000Z",
               "updated_at": "2024-04-19T15:12:09.000000Z",
               "status": 1,
               "featured_status": 1,
               "meta_title": "Pedigree Chicken and Vegetables Adult Dry Dog Food",
               "meta_description": "Pedigree offers dogs complete and balanced dog food for a healthy and active life. Pedigree Adult Dry Dog Food in Chicken and Vegetable Flavor is a wholesome meal packed with essential nutrie",
               "meta_image": "2024-04-04-660e83a9b9dba.png",
               "request_status": 1,
               "denied_note": null,
               "shipping_cost": 0,
               "multiply_qty": 0,
               "temp_shipping_cost": null,
               "is_shipping_cost_updated": null,
               "code": "164357",
               "translations": [],
               "reviews": []
          },
          "order": {
               "id": 100002,
               "customer_id": 3,
               "is_guest": false,
               "customer_type": "customer",
               "payment_status": "unpaid",
               "order_status": "pending",
               "payment_method": "cash_on_delivery",
               "transaction_ref": "",
               "payment_by": null,
               "payment_note": null,
               "order_amount": 342.1,
               "admin_commission": "0.00",
               "is_pause": false,
               "cause": null,
               "shipping_address": "2",
               "created_at": "2024-04-19T15:12:09.000000Z",
               "updated_at": "2024-04-19T15:12:09.000000Z",
               "discount_amount": 0,
               "discount_type": null,
               "coupon_code": "0",
               "coupon_discount_bearer": "inhouse",
               "shipping_responsibility": "inhouse_shipping",
               "shipping_method_id": 2,
               "shipping_cost": 100,
               "is_shipping_free": false,
               "order_group_id": "9588-Vur39-1713539529",
               "verification_code": "306439",
               "verification_status": false,
               "seller_id": 1,
               "seller_is": "admin",
               "shipping_address_data": {
                    "id": 2,
                    "customer_id": "3",
                    "is_guest": false,
                    "contact_person_name": "demo user1",
                    "email": null,
                    "address_type": "home",
                    "address": "Rabindrapally",
                    "city": "Kolkata",
                    "zip": "700094",
                    "phone": "+91+911234567890",
                    "created_at": "2024-04-19T15:11:40.000000Z",
                    "updated_at": "2024-04-19T15:11:40.000000Z",
                    "state": null,
                    "country": "भारत",
                    "latitude": "0.0",
                    "longitude": "0.0",
                    "is_billing": false
               },
               "delivery_man_id": null,
               "deliveryman_charge": 0,
               "expected_delivery_date": null,
               "order_note": null,
               "billing_address": 2,
               "billing_address_data": {
                    "id": 2,
                    "customer_id": "3",
                    "is_guest": false,
                    "contact_person_name": "demo user1",
                    "email": null,
                    "address_type": "home",
                    "address": "Rabindrapally",
                    "city": "Kolkata",
                    "zip": "700094",
                    "phone": "+91+911234567890",
                    "created_at": "2024-04-19T15:11:40.000000Z",
                    "updated_at": "2024-04-19T15:11:40.000000Z",
                    "state": null,
                    "country": "भारत",
                    "latitude": "0.0",
                    "longitude": "0.0",
                    "is_billing": false
               },
               "order_type": "default_type",
               "extra_discount": 0,
               "extra_discount_type": null,
               "free_delivery_bearer": "admin",
               "checked": false,
               "shipping_type": "order_wise",
               "delivery_type": null,
               "delivery_service_name": null,
               "third_party_delivery_tracking_id": null,
               "delivery_man": null
          },
          "verification_images": [],
          "seller": null
     }
]
```
 
</details>
 
## 18. 200 GET /api/v1/order/track?order_id=100002
 
**Model**
 
Paste you model hear
 
<details>
 
<summary>Example</summary>
 
```json
{
     "id": 100002,
     "customer_id": 3,
     "is_guest": false,
     "customer_type": "customer",
     "payment_status": "unpaid",
     "order_status": "pending",
     "payment_method": "cash_on_delivery",
     "transaction_ref": "",
     "payment_by": null,
     "payment_note": null,
     "order_amount": 342.1,
     "admin_commission": "0.00",
     "is_pause": false,
     "cause": null,
     "shipping_address": "2",
     "created_at": "2024-04-19T15:12:09.000000Z",
     "updated_at": "2024-04-19T15:12:09.000000Z",
     "discount_amount": 0,
     "discount_type": null,
     "coupon_code": "0",
     "coupon_discount_bearer": "inhouse",
     "shipping_responsibility": "inhouse_shipping",
     "shipping_method_id": 2,
     "shipping_cost": 100,
     "is_shipping_free": false,
     "order_group_id": "9588-Vur39-1713539529",
     "verification_code": "306439",
     "verification_status": false,
     "seller_id": 1,
     "seller_is": "admin",
     "shipping_address_data": {
          "id": 2,
          "customer_id": "3",
          "is_guest": false,
          "contact_person_name": "demo user1",
          "email": null,
          "address_type": "home",
          "address": "Rabindrapally",
          "city": "Kolkata",
          "zip": "700094",
          "phone": "+91+911234567890",
          "created_at": "2024-04-19T15:11:40.000000Z",
          "updated_at": "2024-04-19T15:11:40.000000Z",
          "state": null,
          "country": "भारत",
          "latitude": "0.0",
          "longitude": "0.0",
          "is_billing": false
     },
     "delivery_man_id": null,
     "deliveryman_charge": 0,
     "expected_delivery_date": null,
     "order_note": null,
     "billing_address": 2,
     "billing_address_data": {
          "id": 2,
          "customer_id": "3",
          "is_guest": false,
          "contact_person_name": "demo user1",
          "email": null,
          "address_type": "home",
          "address": "Rabindrapally",
          "city": "Kolkata",
          "zip": "700094",
          "phone": "+91+911234567890",
          "created_at": "2024-04-19T15:11:40.000000Z",
          "updated_at": "2024-04-19T15:11:40.000000Z",
          "state": null,
          "country": "भारत",
          "latitude": "0.0",
          "longitude": "0.0",
          "is_billing": false
     },
     "order_type": "default_type",
     "extra_discount": 0,
     "extra_discount_type": null,
     "free_delivery_bearer": "admin",
     "checked": false,
     "shipping_type": "order_wise",
     "delivery_type": null,
     "delivery_service_name": null,
     "third_party_delivery_tracking_id": null,
     "delivery_man": null,
     "order_status_history": [
          {
               "id": 9,
               "order_id": 100002,
               "user_id": 3,
               "user_type": "customer",
               "status": "pending",
               "cause": null,
               "created_at": "2024-04-19T15:12:09.000000Z",
               "updated_at": "2024-04-19T15:12:09.000000Z"
          }
     ]
}
```
 
</details>
 
## 19. 200 GET /api/v1/customer/order/get-order-by-id?order_id=100002&guest_id=16
 
**Model**
 
Paste you model hear
 
<details>
 
<summary>Example</summary>
 
```json
{
     "id": 100002,
     "customer_id": 3,
     "is_guest": false,
     "customer_type": "customer",
     "payment_status": "unpaid",
     "order_status": "pending",
     "payment_method": "cash_on_delivery",
     "transaction_ref": "",
     "payment_by": null,
     "payment_note": null,
     "order_amount": 342.1,
     "admin_commission": "0.00",
     "is_pause": false,
     "cause": null,
     "shipping_address": "2",
     "created_at": "2024-04-19T15:12:09.000000Z",
     "updated_at": "2024-04-19T15:12:09.000000Z",
     "discount_amount": 0,
     "discount_type": null,
     "coupon_code": "0",
     "coupon_discount_bearer": "inhouse",
     "shipping_responsibility": "inhouse_shipping",
     "shipping_method_id": 2,
     "shipping_cost": 100,
     "is_shipping_free": false,
     "order_group_id": "9588-Vur39-1713539529",
     "verification_code": "306439",
     "verification_status": false,
     "seller_id": 1,
     "seller_is": "admin",
     "shipping_address_data": {
          "id": 2,
          "customer_id": "3",
          "is_guest": false,
          "contact_person_name": "demo user1",
          "email": null,
          "address_type": "home",
          "address": "Rabindrapally",
          "city": "Kolkata",
          "zip": "700094",
          "phone": "+91+911234567890",
          "created_at": "2024-04-19T15:11:40.000000Z",
          "updated_at": "2024-04-19T15:11:40.000000Z",
          "state": null,
          "country": "भारत",
          "latitude": "0.0",
          "longitude": "0.0",
          "is_billing": false
     },
     "delivery_man_id": null,
     "deliveryman_charge": 0,
     "expected_delivery_date": null,
     "order_note": null,
     "billing_address": 2,
     "billing_address_data": {
          "id": 2,
          "customer_id": "3",
          "is_guest": false,
          "contact_person_name": "demo user1",
          "email": null,
          "address_type": "home",
          "address": "Rabindrapally",
          "city": "Kolkata",
          "zip": "700094",
          "phone": "+91+911234567890",
          "created_at": "2024-04-19T15:11:40.000000Z",
          "updated_at": "2024-04-19T15:11:40.000000Z",
          "state": null,
          "country": "भारत",
          "latitude": "0.0",
          "longitude": "0.0",
          "is_billing": false
     },
     "order_type": "default_type",
     "extra_discount": 0,
     "extra_discount_type": null,
     "free_delivery_bearer": "admin",
     "checked": false,
     "shipping_type": "order_wise",
     "delivery_type": null,
     "delivery_service_name": null,
     "third_party_delivery_tracking_id": null,
     "order_details_count": 1,
     "delivery_man": null,
     "offline_payments": null,
     "verification_images": []
}
```
 
</details>
 
