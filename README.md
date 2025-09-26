# podman-v5.7
v5.7.0
wget https://github.com/phaip88/podman-v5.7/releases/download/v5.7.0/podman_5.7.0-1_all.deb
sudo apt update
sudo apt install -y ./podman_5.7.0-1_all.deb
podman version          # 应显示 5.7.0
podman run --rm hello-world
