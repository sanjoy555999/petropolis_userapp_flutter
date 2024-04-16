## UserApp API Manual Fetch from Code

 1. api url
 2. api url

## 1. 200 GET /api/v1/notifications?limit=10&guest_id=1&offset=1

**Model**
paste you model hear
**Example**

```json
{
     "total_size": 2,
     "limit": 10,
     "offset": 1,
     "new_notification": 2,
     "notification": [
          {
               "id": 3,
               "sent_by": "system",
               "sent_to": "customer",
               "title": "Coupon",
               "description": "From Now on, Use Code \"pcuw655ytg\" to get 65% discount.",
               "notification_count": 1,
               "image": "2023-10-16-652d1af9b5345.png",
               "status": 1,
               "created_at": "2022-04-19T23:40:23.000000Z",
               "updated_at": "2023-10-16T05:14:01.000000Z",
               "notification_seen_by": null
          },
          {
               "id": 2,
               "sent_by": "system",
               "sent_to": "customer",
               "title": "Buy 2 get 1",
               "description": "Buy any 2 products then get any product.",
               "notification_count": 2,
               "image": "2023-10-16-652d1b070e73c.png",
               "status": 1,
               "created_at": "2022-04-16T00:37:58.000000Z",
               "updated_at": "2023-10-16T05:14:15.000000Z",
               "notification_seen_by": null
          }
     ]
}
```

## 2. 200 GET /api/v1/flash-deals

**Model**
paste you model hear
**Example**

```json
{
     "id": 4,
     "title": "Flash Deal",
     "start_date": "2022-04-11T18:00:00.000000Z",
     "end_date": "2030-12-25T18:00:00.000000Z",
     "status": true,
     "featured": false,
     "background_color": null,
     "text_color": null,
     "banner": "2023-10-15-652bd104efe02.png",
     "slug": "flash-deal",
     "created_at": "2022-04-13T01:03:56.000000Z",
     "updated_at": "2023-10-16T04:18:33.000000Z",
     "product_id": null,
     "deal_type": "flash_deal",
     "translations": []
}
```



## 3. 200 GET /api/v1/brands?guest_id=1
**Model**
paste you model hear
**Example**
```json 
[
     {
          "id": 17,
          "name": "Digital Product",
          "image": "2023-10-15-652b6b25358c2.png",
          "status": 1,
          "created_at": "2022-10-11T22:46:41.000000Z",
          "updated_at": "2023-10-14T22:31:33.000000Z",
          "brand_products_count": 0,
          "translations": []
     },
     {
          "id": 14,
          "name": "Estha dot",
          "image": "2023-10-15-652b6b32edd08.png",
          "status": 1,
          "created_at": "2022-04-11T03:22:59.000000Z",
          "updated_at": "2023-10-14T22:31:46.000000Z",
          "brand_products_count": 2,
          "translations": []
     },
     {
          "id": 13,
          "name": "S.Cube",
          "image": "2023-10-15-652b6b417fc7e.png",
          "status": 1,
          "created_at": "2022-04-11T03:22:08.000000Z",
          "updated_at": "2023-10-14T22:32:01.000000Z",
          "brand_products_count": 4,
          "translations": []
     },
     {
          "id": 12,
          "name": "Fashion",
          "image": "2023-10-15-652b6b5125306.png",
          "status": 1,
          "created_at": "2022-04-11T03:21:33.000000Z",
          "updated_at": "2023-10-14T22:32:17.000000Z",
          "brand_products_count": 4,
          "translations": []
     },
     {
          "id": 9,
          "name": "JK",
          "image": "2023-10-15-652b6b82b1cfd.png",
          "status": 1,
          "created_at": "2022-04-11T03:17:25.000000Z",
          "updated_at": "2023-10-14T22:33:06.000000Z",
          "brand_products_count": 3,
          "translations": []
     },
     {
          "id": 8,
          "name": "Waltro",
          "image": "2023-10-15-652b6bac580d4.png",
          "status": 1,
          "created_at": "2022-04-11T03:16:52.000000Z",
          "updated_at": "2023-10-14T22:33:48.000000Z",
          "brand_products_count": 2,
          "translations": []
     },
     {
          "id": 7,
          "name": "Ohoenix",
          "image": "2023-10-15-652b6c27520e8.png",
          "status": 1,
          "created_at": "2022-04-10T05:22:10.000000Z",
          "updated_at": "2023-10-14T22:35:51.000000Z",
          "brand_products_count": 4,
          "translations": []
     },
     {
          "id": 6,
          "name": "Estro",
          "image": "2023-10-15-652b6c4dd3015.png",
          "status": 1,
          "created_at": "2022-04-10T05:20:35.000000Z",
          "updated_at": "2023-10-14T22:36:29.000000Z",
          "brand_products_count": 2,
          "translations": []
     },
     {
          "id": 5,
          "name": "Triangle",
          "image": "2023-10-15-652b6c9ae4f96.png",
          "status": 1,
          "created_at": "2022-04-10T05:20:04.000000Z",
          "updated_at": "2023-10-14T22:37:46.000000Z",
          "brand_products_count": 8,
          "translations": []
     },
     {
          "id": 1,
          "name": "i Bird",
          "image": "2023-10-15-652b6ca949d38.png",
          "status": 1,
          "created_at": "2022-03-16T09:35:55.000000Z",
          "updated_at": "2023-10-14T22:38:01.000000Z",
          "brand_products_count": 6,
          "translations": []
     }
]
```






## 2. API URL 2
**Model**
paste you model hear
**Example**
paste your post data hear
