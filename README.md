# chartjs-adapter-dayjs-4

## Overview

This adapter allows the use of day.js with Chart.js time scale.

Requires Chart.js **4.0.1** or later and dayjs **1.9.7** or later.

**NOTE:** This adapter was designed for Chart.js v4 (which requires a separate date adapter for time scales to work properly), using this adapter in any version prior to 4 will override the default date-adapter

## Installation

### npm

```bash
npm install dayjs chartjs-adapter-dayjs-4 --save
```

```javascript
import Chart from 'chart.js';
import 'chartjs-adapter-dayjs-4/dist/chartjs-adapter-dayjs-4.esm';
```

## Configuration

### v4 [Chart.js documention](https://www.chartjs.org/docs/latest)

Read the Chart.js documention [v4](https://www.chartjs.org/docs/latest) for possible date/time related options. For example, the time scale `time.*` options [v4](https://www.chartjs.org/docs/latest/axes/cartesian/time.html#configuration-options) can be overridden using the [Day.js formats](https://day.js.org/docs/en/display/format).

## Development

You first need to install node dependencies (requires [Node.js](https://nodejs.org/)):

**_NPM_**

```bash
> npm install
```

**_Yarn_**

```bash
> yarn add
```

## License

`chartjs-adapter-dayjs-4` is available under the [MIT license](LICENSE.md).

## Credits

---

Moment Adapter source && README template

[Ben McCann](https://github.com/benmccann)

[Evert Timberg](https://github.com/etimberg)

[stockiNail](https://github.com/stockiNail)

---
