# event.json

The data provided represents all Startup Weekend events that have happened or are planned to happen, as of 3/28/2013.  Each event contains the following information:

```
{
  "id":1,                   // (integer) - The id of the event.
  "city":"West Michigan",   // (string) - The name of the city where the event takes place.
  "state":"MI",             // (string) - The state/province where the event takes place.
  "country":"USA",          // (string) - The country where the event takes place.
  "vertical":null,          // (string, nullable) - The industry vertical, if this event has one (UNI, Health, Mobile, etc).
  "start_date":"2010-02-26T00:00:00.000Z", // (ISO Date) - The date at which the event starts.
  "website":"wmi.startupweekend.org",      // (string) - The website for the event.
  "location":{                  // (object) - The location of the event.  May be empty.
    "lat":51.5073346,           // (float) - The latitude
    "lng":-0.12768310000001293  // (float) - The longitude
  },
  "twitter_hashtag":null,       // (string, nullable) - The twitter hashtag for an event.
  "facilitators":[              // (object[])- The event facilitators.  May be empty.
    {
      "_id":"5011b56e91ac880200000977", // (bson) - A unique ID for the facilitator.
      "first_name":"Marc", // (string) - The facilitator's first name.
      "last_name":"Nager", // (string) - The facilitator's last name.
      "name":"Marc Nager"  // (string) - The facilitator's full name
    }
  ]
}
```