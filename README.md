#Workshop_dapps

1. docker build -t workshop_dapps .
2. docker run -it -v $(REPOSITORY_ROUTE)*/projects:/project --net=host --name workshop workshop-dapps

*REPOSITORY_ROUTE: Ruta absoluta del repositorio.
