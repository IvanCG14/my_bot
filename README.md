## Proyecto Robots Moviles y Articulados

Comandos de ejecuciòn(4 terminales distintas):

```bash
  ros2 launch my_bot launch_sim.launch.py world:=./src/my_bot/worlds/obstacles.world
  rviz2
  ros2 launch nav2_bringup localization_launch.py map:=./src/my_bot/maps/map1_save.yaml use_sim_time:=true
  ros2 launch nav2_bringup navigation_launch.py use_sim_time:=true map_subscribe_transient_local:=true
```

En rviz incluir 2 Map, uno para el topic map y otro para el topic global costmap.
Añadir el panel de nav2, y agregar la opciòn de Nav2 goal en la barra superior con el signo +.
