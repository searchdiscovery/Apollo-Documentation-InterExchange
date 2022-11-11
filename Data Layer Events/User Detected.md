# User Detected

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "detect_user",
  "detailed_event": "User Detected",
    "page_data": {
        "user_login_state": "<user_login_state>"
    },
    "user_data": {
        "user_city": "<user_city>",
        "user_lifetime_logins": <user_lifetime_logins>,
        "user_registration_status": "<user_registration_status>",
        "user_state_or_province": "<user_state_or_province>",
        "user_type": "<user_type>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|page_data.user_login_state|string|Captures the current sign in status for the user \(i.e. signed\_out, signed\_in, unknown\).|logged in, logged out, guest|||||||
|user_data.user_city|string|Captures the city associated with the user.||||||||
|user_data.user_lifetime_logins|integer|Captures the count of times the user has authenticated in the past. Typically imported from back-end database.||||||||
|user_data.user_registration_status|string|Captures the current registration status of the user.|registered|||||||
|user_data.user_state_or_province|string|Captures the state or province associated with a tranaction or significant user action.||||||||
|user_data.user_type|string|Captures the type associated with the user \(i.e. guest, registered, prime, etc\).|employee, guest, agent, customer|||||||




