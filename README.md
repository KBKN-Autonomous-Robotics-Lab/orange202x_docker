# orange2025_docker

orange2025: https://github.com/KBKN-Autonomous-Robotics-Lab/orange2025

Distribution: `ROS2 Humble Hawksbill`

イメージ作成前に以下でGPUやCUDAの設定確認をしてください
https://github.com/takamooori/manual_for_myself/blob/main/docker-nvidia-setup.md

## Build from Dockerfile (recommendation)🔧
```
$ git clone https://github.com/KBKN-Autonomous-Robotics-Lab/orange2025_docker.git
$ cd orange2025_docker
$ bash build.sh
$ bash livox_runLite.sh
```
> [!IMPORTANT]
> Execute `bash build.sh` to build the docker image, which may take several hours.
> Create a docker container by running `bash livox_runLite.sh`. Now you can access http://{IP_ADDRESS_OF_YOUR_PC}:6080/ in your browser.

## Tips👻
- If you are running the Gazebo first time, it could take for a long time.
- Gazebo could show empty or even blank screen after launch. In that case, you need to re-launch orange_gazebo.
