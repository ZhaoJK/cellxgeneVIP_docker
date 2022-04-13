# cellxgeneVIP_docker
install cellxgeneVIP in docker

### To build the image:
`docker build -t cellxgene https://gitlab.gwdg.de/loosolab/container/cellxgene_VIP.git#main`

### To run the container:
`docker run --rm -v "path/to/dataset:/data/" -p 5005:5005 cellxgene launch --host 0.0.0.0 /data/dataset.h5ad`
