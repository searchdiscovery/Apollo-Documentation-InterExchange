# Page Load Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "page_load_started",
  "detailed_event": "Page Load Started",
    "page_data": {
        "category": "<category>",
        "cohort": "<cohort>",
        "country": "<country>",
        "department": "<department>",
        "language": "<language>",
        "marketing_site": "<marketing_site>",
        "name": "<name>",
        "page_location": "<page_location>",
        "program": "<program>",
        "program_country": "<program_country>",
        "program_type": "<program_type>",
        "type": "<type>",
        "utm_campaign": "<utm_campaign>",
        "utm_content": "<utm_content>",
        "utm_medium": "<utm_medium>",
        "utm_source": "<utm_source>",
        "utm_term": "<utm_term>"
    },
    "user_data": {
        "user_identifier": "<user_identifier>",
        "user_type": "<user_type>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|page_data.category|string|This is the page level category|Host, Participant|||||||
|page_data.cohort|string|This is the page level name of the Cohort if present|"2023 Au Pair USA", "2022 Camp USA", "2021 Work Travel USA - Winter"|||||||
|page_data.country|string|The country associated with the current page.|US, CA, FR, UK|||||||
|page_data.department|string|This is the page level department|Au Pair USA, Camp USA|||||||
|page_data.language|string|The language of the current page, usually pulled from the &lt;html&gt; tag lang attribute.|en-us, en-gb, ch-cn, fr-ca, fr-fr|||||||
|page_data.marketing_site|string|This refers to the micro sites that marketing has deployed, allowing us to track whether they came from interexchange.org, aupairusa.org, or campusa.org|interexchange.org, aupairusa.org, or campusa.org|||||||
|page_data.name|string|Captures the name of the page the user is on|product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|page_data.page_location|string|The url of the page currently being viewed.||||||||
|page_data.program|string|This is the page level program|Au Pair USA, Camp USA|||||||
|page_data.program_country|string|This is the program country at the page level|US, CA, IT, FR, DE|||||||
|page_data.program_type|string|This is the page level program type|Au Pair, Camp|||||||
|page_data.type|string|The type of page currently viewed.|home, pdp, article|||||||
|page_data.utm_campaign|string|This is the utm campaign attribute|Facebook Ad, email, etc|||||||
|page_data.utm_content|string|This is the UTM Content attribute||||||||
|page_data.utm_medium|string|This is the UTM Medium attribute|Social, Organic, Paid, Email, Affiliates, etc|||||||
|page_data.utm_source|string|This is the UTM Source attribute|Facebook, Twitter, LinkedIn, YouTube, etc.|||||||
|page_data.utm_term|string|This is the UTM Term attribute||||||||
|user_data.user_id|string|The id of the user currently logged in to the site, if the site offers authentication and the user is authenticated.|123456, abc123|||||||
|user_data.user_type|string|This is the user type|Host, Participant|||||||




