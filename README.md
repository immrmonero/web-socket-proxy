
# web-socket-proxy

Allows you to proxy web socket requests to servers.



## Install

```
npm install -g web-socket-proxy
```

## Usage

#### CLI

You just need to launch a proxy pointing to the desired pool:

```
coin-hive-stratum 8892 --host=proxy.server.com --port=8888
```


#### JS

```
const Proxy = require("web-socket-proxy");
const proxy = new Proxy({
  host: "proxy.server.com",
  port: 8888
});

proxy.listen(8892);
```

