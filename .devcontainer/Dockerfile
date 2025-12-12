# jazzy_dev:latest base on allision docker with nvidia cuda 13.0.0
FROM jazzy_dev:latest

RUN apt-get update && apt-get install -y --no-install-recommends \
  ros-jazzy-joint-state-publisher-gui \
  ros-jazzy-rqt-tf-tree \
  && rm -rf /var/lib/apt/lists/*

RUN apt-get update && apt-get install -y --no-install-recommends \
  python3-venv \
  python3-pip \
  && rm -rf /var/lib/apt/lists/*




ENV DEBIAN_FRONTEND=

