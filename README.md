```bash
echo "deb [trusted=yes] https://github.com/ArendJan/mirte-ros-prebuilt-packages/raw/ros_mirte_humble_jammy_amd64_develop/ ./" | sudo tee /etc/apt/sources.list.d/ArendJan_mirte-ros-prebuilt-packages.list
echo "yaml https://github.com/ArendJan/mirte-ros-prebuilt-packages/raw/ros_mirte_humble_jammy_amd64_develop/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-ArendJan_mirte-ros-prebuilt-packages.list
```
