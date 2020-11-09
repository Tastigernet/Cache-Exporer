## Cache $CXCHE Explorer

Block explorer for Cache $CXCHE.

#### Installation

- It takes data from daemon `cache-daemon`. 
- It should be accessible from the Internet. 
- Run `cache-daemon` with open port as follows:

```bash
./cache-daemon --enable-blockchain-indexes --rpc-bind-ip=0.0.0.0 --rpc-bind-port=40000 --node-id yourid
```

- For advanced configuration, e.g. NAT port forwarding, see:

```bash
./cache-daemon --help
```

2) Upload to your website and change 'api' variable in `config.js` to point to your daemon.

#### Development, Copyrights and Notes

- Devs: @aivve @taegus @katz @devopsralf @En4orcer @tastiger

- Copyright: Karbovanets, Conceal Network and Cache
