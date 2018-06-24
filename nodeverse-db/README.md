# nodeverse-db

## Usage

```js
const setupDatabase = require('nodeverse-db')

const db = setupDatabase(config).then(db => {
  const { Agent, Metric} = db
})
.catch(error => console.error(error))
```