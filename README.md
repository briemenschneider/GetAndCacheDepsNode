# GetAndCacheDepsNode
Action to cache and build a Node project with yarn or npm

use as follows:
```
jobs:
  lint:
    runs-on: ubuntu-latest
    steps:
      - name: Get and Cache dependencies
        uses: briemenschneider/getandcachedepsnode@v1.1
        with:
          use-yarn: 'true' #Optional, defaults to 'false'
          node-modules-path: 'node_modules' #Optional, defaults to './node_modules'
```
