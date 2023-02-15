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
        "user_application_status": "<user_application_status>",
        "user_city": "<user_city>",
        "user_country": "<user_country>",
        "user_type": "<user_type>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|page_data.user_login_state|string|Captures the current sign in status for the user \(i.e. signed\_out, signed\_in, unknown\).|logged in, logged out, guest|||||||
|user_data.user_application_status|string|This is the user's appliation status||||||||
|user_data.user_city|string|Captures the city associated with the user.||||||||
|user_data.user_country|string|This is the applicant's country of origin||||||||
|user_data.user_type|string|Captures the type associated with the user \(i.e. guest, registered, prime, etc\).|employee, guest, agent, customer|||||||




