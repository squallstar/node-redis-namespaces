# node-redis-namespaces

**Originally forked from https://github.com/arschles/node-redis-namespace**

Pretty much a clone of [redis-namespace](https://github.com/defunkt/redis-namespace) for node.

# Install
	npm install redis-namespaces

# Use
Use this library just as you would [node_redis](https://github.com/mranney/node_redis)

```
var redis_namespaces = require('redis-namespaces');

var client = redis_namespaces.createClient(prefix, port, host, opts);

// Carry on as normal
```