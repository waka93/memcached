# memcahced

The source code is copied from https://github.com/3rd-Eden/memcached

Two batch operation methods are added
- memcached.sets
- memcached.dels/ memcached.deletes


## Usage
```bash
# install dependencies
npm install
```

```javascript
const Memcached = require("./libs/memcached")
var memcached = new Memcached("{$server}:{$port}")
```
