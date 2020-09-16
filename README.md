## $CXCHE Explorer

Block explorer for $CXCHE.

#### Installation

- It takes data from daemon `cache-daemon`. 
- It should be accessible from the Internet. 
- Run `cache-daemon` with open port as follows:

```bash
./cache-daemon --enable-cors="*" --enable-blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=30000
```

2) Upload to your website and change 'api' variable in `config.js` to point to your daemon.

### Development, Copyrights and Notes

- Devs: @aivve @taegus @katz @devopsralf @En4orcer

- Copyright: Karbovanets, Conceal Network and Cache
