# clark-simulation
PMec -Flying-robots in LARC

Para conseguir rodar a simulação, sera necessario arrumar algumas coisas

1. Copiar os arquivos desse github para o seu diretorio de preferencia
```
git clone git@github.com:Flying-Robots-LARC/clark-simulation.git
```
2. Buildar o Dockerfile
```
cd rtabmap_drone_example
docker build -t rtabmap_drone_example -f docker/Dockerfile .
```
3. Rodar a imagem
```
./run.sh 
```
