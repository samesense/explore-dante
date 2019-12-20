### Alignment stats
* bam.iobio.io/

#### bam.iobio container for local runs
* https://hub.docker.com/repository/docker/samesense/bam-iobio (update w/ dockerfile when going public and delete works tag

```
docker run -it -p 4027:4027 samesense:bam-iobio:works bash
git clone https://github.com/chmille4/bam.iobio.io/
cd bam.iobio.io/
npm install
npm run build
node www.js 
# localhost:4027/
```
