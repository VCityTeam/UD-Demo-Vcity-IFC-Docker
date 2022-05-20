# Demo Ifc

Create a docker of the [Demo Ifc](https://github.com/VCityTeam/UD-Demo-Vcity-Ifc).  
_See the [online version](https://chaufferie.vcityliris.data.alpha.grandlyon.com/)_.

The demo uses a [SimpleServer](https://github.com/VCityTeam/UD-SimpleServer), based on [ExpressJS](https://en.wikipedia.org/wiki/Express.js) web-server.

Clone the repo

```bash
git clone https://github.com/VCityTeam/UD-Demo-vcity-py3dtilers-lyon-docker.git
cd UD-Demo-vcity-Ifc-Docker
```

Build the docker image with

```bash
docker build -t vcity/demo-ifc .
```

and run the container with

```bash
docker run -p 8080:80/tcp -t vcity/demo-ifc
```

and open a web browser on URL `http://localhost:8080/`
