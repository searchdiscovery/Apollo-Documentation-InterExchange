# CTA Link Clicked

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "click",
  "detailed_event": "CTA Link Clicked",
    "event_data": {
        "category": "<category>",
        "identifier": "<identifier>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.category|string|Count of times that visitors click on a Call to Action \(CTA\) link.||||||||
|event_data.identifier|string|Captures the ID associated with CTA links used.|act now, cancel, ok, 3456, 8765|||||||




