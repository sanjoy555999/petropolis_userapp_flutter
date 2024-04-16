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
## 2. API URL 2
**Model**
paste you model hear
**Example**
paste your post data hear
