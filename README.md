# nodertc-example
Example using nodertc

# Install 

```bash
git clone https://github.com/felixdrp/nodertc-example.git
cd nodertc-example

npm install

# Run
node example-express.js
```

Open browser at address [localhost:7007](http://localhost:7007)

# Debug

```bash
DEBUG=dtls,dtls:*,sctp,sctp:* DEBUG_DEPTH=10 node example-express.js
```