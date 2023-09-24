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

3. Para rodar a imagem, apenas execute o arquivo run.sh
   
```
./run.sh 
```

-----

Abra quatro terminais com o `run.sh`, e tente executar oque esta no git https://github.com/matlabbe/rtabmap_drone_example

1. Terminal do Gazebo
   
```
roslaunch rtabmap_drone_example gazebo.launch
```

2. Terminal do SLAM
   
```
roslaunch rtabmap_drone_example slam.launch
```

3. Terminal do RVIZ
   
```
roslaunch rtabmap_drone_example rviz.launch
```

4. Terminal para executar o offboard
   
```
rosrun rtabmap_drone_example offboard
```
