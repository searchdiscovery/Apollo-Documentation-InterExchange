# Page Load Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "detailed_event": "Page Load Started",
  "event": "page_load_started",
  "page_data": {
      "category": "<category>",
      "country": "<country>",
      "department": "<department>",
      "language": "<language>",
      "name": "<name>",
      "page_location": "<page_location>",
      "program": "<program>",
      "program_country": "<program_country>",
      "program_type": "<program_type>",
      "type": "<type>"
  },
  "user_data": {
      "type": "<type>",
      "user_id": "<user_id>"
  }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|page_data.category|string|This is the page level category.|Host, Participant|||||||
|page_data.country|string|The country the site is associated with.||||||||
|page_data.department|string|This is the page level dpartment.|Au Pair USA, Camp USA|||||||
|page_data.language|string|The language of the current page, usually pulled from the &lt;html&gt; tag lang attribute.||||||||
|page_data.name|string|Captures the name of the page the user is on|product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|page_data.page_location|string|The url of the page currently being viewed.||||||||
|page_data.program|string|This is the page level program.|Host, Participant|||||||
|page_data.program_country|string|This is the program country at the page level.|US, CA, IT, FR, DE|||||||
|page_data.program_type|string|This is the page level program type.|Au Pair, Camp|||||||
|page_data.type|string|The type of page currently viewed.|home, pdp, article|||||||
|user_data.type|string|This is the user type.|Host, Participant|||||||
|user_data.user_id|string|The id of the user currently logged in to the site, if the site offers authentication and the user is authenticated.|123456, abc123|||||||




