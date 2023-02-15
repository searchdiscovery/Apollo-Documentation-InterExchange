# User Signed In

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "login",
  "detailed_event": "User Signed In",
    "user_data": {
        "user_city": "<user_city>",
        "user_country": "<user_country>",
        "user_type": "<user_type>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|user_data.user_city|string|Captures the city associated with the user.||||||||
|user_data.user_country|string|Captures the country associated with the user.|USA, Canada|||||||
|user_data.user_type|string|Captures the type associated with the user \(i.e. guest, registered, prime, etc\).|employee, guest, agent, customer|||||||




