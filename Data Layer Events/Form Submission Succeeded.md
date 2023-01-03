# Form Submission Succeeded

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "form_complete",
  "detailed_event": "Form Submission Succeeded",
    "event_data": {
        "identifier": "<identifier>",
        "name": "<name>",
        "type": "<type>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.identifier|string|Captures the unique ID of the form.|ParticipantApplicationBiography\#1234, ApParticipantApplicationHealth\#1234, HFAppWizardChildren\#1234, EmployerApplicationHousingForm\#1234|||||||
|event_data.name|string|Captures the human-friendly name of the form.|ParticipantApplicationBiography, ApParticipantApplicationHealth, HFAppWizardChildren, EmployerApplicationHousingForm|||||||
|event_data.type|string|Captures the type of form \(i.e. demo, free trial, contact us\).|ParticipantApplicationForm, HFAppForm, EmployerApplicationForm|||||||

