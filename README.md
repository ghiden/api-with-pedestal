# Playing with Pedestal

[Your First API](http://pedestal.io/guides/your-first-api)

```bash
boot repl
```

```clojure
(require 'main)
(main/start-dev)
(main/test-request :post "/todo?name=A-List")
```

Edit code and reload
```
(require :reload 'main)
(main/restart)
```
