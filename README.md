# qth-locator

Operations with [Maidenhead locator system](https://en.wikipedia.org/wiki/Maidenhead_Locator_System)

## Usage

```javascript
const { locatorToLatLng, distance } = require('qth-locator');

locatorToLatLng('IO91wm'); // [51.521, -0.125]
distance('IO91wm', 'KP20le'); // 1821.5 km
azimuth('LO97xw', 'KP20le'); // 292
```

## License

MIT
