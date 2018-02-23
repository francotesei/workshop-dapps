
1. docker build -t workshop_dapps .
2. docker run -it -v $(REPOSITORY_ROUTE)*/projects:/projects --net=host --name workshop workshop-dapps

*REPOSITORY_ROUTE: Ruta absoluta del repositorio.
