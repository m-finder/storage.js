# <center>storage.js</center>

localStorage modules for laravel

#### use
require in app.js

```vue
window.storage = require('./storage');
```

```vue
// save
storage.set({ id: 1, name: 'm-finder' })

// get
storage.get('id')

// remove key
storage.remove('id')

// remove all
storage.remove()
```
