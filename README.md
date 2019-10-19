# <center>storage.js</center>

storage for laravel

#### use
require in app.js

```javascrip
import storage from './storage'
```

#### use localStorage 
```javascrip
// save
storage.set({ id: 1, name: 'm-finder' })

// get
storage.get('id')

// remove key
storage.remove('id')

// remove all
storage.remove()
```


#### use sessionStorage
```javascrip
// save
storage.sessionSet({ id: 1, name: 'm-finder' })

// get
storage.sessionGet('id')

// remove key
storage.sessionRemove('id')

// remove all
storage.sessionRemove()
```
