# Karma Profiles

## Get/Search Karma Profiles

```shell
curl "http://beta.buildtheworld.org/api/v2/karma_profiles"
  -H "Authorization: meowmeowmeow"
```
> The above command returns JSON structured like this:

```json
{
  "karmaProfiles":[
    {
      "id": "0594452a-5d5f-40c8-a0a7-a96f34ba74cc",
      "userId": "3c0c75a4-57c8-45d9-a2fe-e8c0d1d96108",
      "createdAt": "2017-11-11T14:19:31.436Z",
      "updatedAt": "2017-12-15T09:00:35.418Z",
      "phoneNo": null,
      "location": null,
      "birthday": null,
      "karmaStatement": "sdfdsf",
      "occupationType": null,
      "occupationPlace": null,
      "campaignsVolunteeredCount": 2,
      "CampaignsLeadCount": 1,
      "campaignsAttendedCount": 3,
      "karmaHours": 0,
      "upcomingCampaignIds":["a7f6638f-5c54-4f51-9439-eea894be02bd"],
      "pastCampaignIds":["a7f6638f-5c54-4f51-9439-eea894be02bd"],
      "campaignsLeadIds":["a7f6638f-5c54-4f51-9439-eea894be02bd","a7f6638f-5c54-4f51-9439-eea894be02bd"],
      "campaignsVolunteeredIds":["a7f6638f-5c54-4f51-9439-eea894be02bd"]
    }
  ],
  "users":[
    {
      "id": "a7f6638f-5c54-4f51-9439-eea894be02bd",
      "firstName": "Hardik",
      "lastName": "Patel",
      "fullName": "Hardik Patel",
      "rocketChatUserid": "qbPzPZvc2aCbFgHwW",
      "karmaProfileId": "701aabe1-9dee-4ff1-a6e3-8c9d9f5de2f7",
      "avatar": "https://lh5.googleusercontent.com/-VN3O4U71Shc/AAAAAAAAAAI/AAAAAAAAF0g/KjbWlxnDFy8/photo.jpg",
      "avatarRelative": false,
      "coverImage": {
        "id": "01c9fe6d-a4c6-4a2c-aa96-12cbe1ee36e1",
        "name": null,
        "cropHeight": -175,
        "cropWidth": 0,
        "media": {
          "original": "/system/uploads/media/01c/9fe/6d-/original/IMG_3468.JPG?1513599486",
          "big": "/system/uploads/media/01c/9fe/6d-/big/IMG_3468.JPG?1513599486",
          "medium": "/system/uploads/media/01c/9fe/6d-/medium/IMG_3468.JPG?1513599486",
          "small": "/system/uploads/media/01c/9fe/6d-/small/IMG_3468.JPG?1513599486",
          "thumbnail": "/system/uploads/media/01c/9fe/6d-/thumb/IMG_3468.JPG?1513599486"
        }
      }
    }
  ]
}
```

This endpoint retrieves karma_profiles.

### HTTP Request

`GET http://beta.buildtheworld.org/api/v2/karma_profiles`

### Query Parameters

Parameter | Default | Description
--------- | ------- | -----------
userId | true | retrieves karma profile of given user.