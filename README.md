# tessel-soil-moisture-sensor

Tessel + Soil Moisture Sensor (SEN-13322)

## Usage

Check `test.js` for working example.

```
const getSoilMoistureReading = require('./index.js');
getSoilMoistureReading((value) => {
  // value contains calibrated value and normal value
  console.log(value);
});
```
