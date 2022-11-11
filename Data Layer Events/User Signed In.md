# User Signed In

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "login",
  "detailed_event": "User Signed In",
    "event_data": {
        "method": "<method>"
    },
    "page_data": {
        "user_login_state": "<user_login_state>"
    },
    "user_data": {
        "user_city": "<user_city>",
        "user_country": "<user_country>",
        "user_lifetime_logins": <user_lifetime_logins>,
        "user_type": "<user_type>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.method|string|Captures the website method \(i.e. search, top nav\) used to find each product.|email, facebook, twitter|||||||
|page_data.user_login_state|string|Captures the current sign in status for the user \(i.e. signed\_out, signed\_in, unknown\).|logged in, logged out, guest|||||||
|user_data.user_city|string|Captures the city associated with the user.||||||||
|user_data.user_country|string|Captures the country associated with the user.|USA, Canada|||||||
|user_data.user_lifetime_logins|integer|Captures the count of times the user has authenticated in the past. Typically imported from back-end database.||||||||
|user_data.user_type|string|Captures the type associated with the user \(i.e. guest, registered, prime, etc\).|employee, guest, agent, customer|||||||



