---
lastUpdated: 2019-01-09
---

# Data Source Schema  {#Data Source Schema}

All datasource data must contain a `ts` key with a Unix Timestamp value as shown below.
InfoMotion uses the `ts` for daterange picker, timeline and querying historical data.
This data is also used with in the InfoType (graph/chart).

```javascript
{
  ts: Unix Timestamp milliseconds since Jan 01 1970. (UTC), // timestamp for daterange, timeline and querying.
  // All data in this object is passed to the infotype
}
```

#InfoType sample data {#InfoType sample data}

Each InfoType may require specific keys and values.
The type of data required for each InfoType can be seen on the right hand side
in preview of the InfoType.

![sampleBarChart](./../../img/InfoMotion/DataSource/infotype-highlights.png)

For an enebular sample barchart the folowing data is required.

## Sample Data{#Sample Data}

```javascript
{
  ts: Unix Timestamp milliseconds since Jan 01 1970. (UTC),
  category: String,
  value: Number
}
```

## JSON Data Schema {#JSON Data Schema}

```json
{
  "type": "object",
  "required": ["ts"],
  "properties": {
    "ts": {
      "$id": "#/properties/ts",
      "type": "integer",
      "title": "The ts Schema",
      "examples": [1542352981750]
    }
  }
}
```
