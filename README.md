# dockerGUIfirefox
Firefox running as GUI inside docker container
```docker build -t image:tag .``` after building image from dockerfile run ```docker container run --net=host --env="DISPLAY" --volume="$HOME/.Xauthority:/root/.Xauthority:rw" imagename```
