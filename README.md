# twstockjs

台股資料library

## Install

```bash
npm i twstockjs
```

## Usage

```javascript
const twstockjs = require('twstockjs');
```

## API

### isTradingDay('yyyy-mm-dd')

return promise\<boolean\>

### checkTradingDay('yyyy-mm-dd')

return promise\<TradingDay\>

#### TradingDay

```javascript
{
  isTradingDay: boolean,
  // The description of the date which isTradingDay is false
  des: string
}
```

## TODO

- [ ] 上市櫃清單

- [ ] 公司基本資料
