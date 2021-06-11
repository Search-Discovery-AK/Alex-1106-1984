# User Visit Started

## Javascript Code
```js
window.appEventData1106 = window.appEventData1106 || [];
appEventData1106.push({
  "event": "User Visit Started",
    "user": {
        "hasPersistedCart": "<hasPersistedCart>",
        "persistedCartValue": "<persistedCartValue>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|hasPersistedCart|boolean|Indicator of the user has a persisted shopping cart|TRUE, FALSE|||||||
|persistedCartValue|string|The total value of all items in the persisted cart|125.05, 432.21, 90.22, 12.05|^[0-9]*(\.[0-9]{1,2})?$||||||
