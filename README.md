# traaittCASH pool list

The goal of this repository is to have a central list of pools for traaittCASH (https://traaittCASH.com) mining. If you run a pool, please submit a Pull Request against *traaittCASH-pools.json* to get added.

This list can be consumed in your application so you'll always have an up-to-date list of pools. To consume the list, just use the following URL: https://raw.githubusercontent.com/trrxitte/traaittcash-pools/master/traaittcash-pools.json

## Contributing

Please add your pool to the list in **alphabetical order**, and **include trailing slashes** for the `url` and `api` values.

**e.g.**
```
    {
        "name" : "MyPool.com",
        "url" : "https://trtl.mypool.com/",
        "api" : "https://trtl.mypool.com/api/",
        "type" : "forknote"
    },
```

### Possible values for 'type'
 - forknote
 - forknote-alt
 - node.js
 - other
