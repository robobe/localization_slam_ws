# jazzy_dev:latest base on allision docker with nvidia cuda 13.0.0
FROM jazzy_dev:latest

RUN apt-get update && apt-get install -y --no-install-recommends \
  ros-jazzy-joint-state-publisher-gui \
  && rm -rf /var/lib/apt/lists/*
ENV DEBIAN_FRONTEND=

