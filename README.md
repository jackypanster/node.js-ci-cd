+ Download the node.js dist

```bash
wget https://nodejs.org/dist/v7.7.4/node-v7.7.4-linux-x64.tar.gz
```

+ Install the node.js binary

```bash
cd /usr/local
sudo tar --strip-components 1 -xzf /home/ubuntu/node-v7.7.4-linux-x64.tar.gz
```

+ Verify

```bash
node -v
npm -v
```

+ Configure registry

```bash
npm install --registry http://registry.cnpmjs.org
# or
npm --registry=https://registry.npm.taobao.org install
```
