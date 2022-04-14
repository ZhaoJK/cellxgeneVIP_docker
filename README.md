# cellxgeneVIP_docker
install cellxgeneVIP in docker


### To build the image:
`docker build -t cellxgene https://gitlab.gwdg.de/loosolab/container/cellxgene_VIP.git#main`
or git from here https://github.com/ZhaoJK/cellxgeneVIP_docker/


### To run the container:
`docker run --name=cellxgeneVIP -v "path/to/dataset:/data/" -p 5005:5005 cellxgene launch --host 0.0.0.0 /data/dataset.h5ad`

Reference  
[docker run](https://docs.docker.com/engine/reference/run/) 

