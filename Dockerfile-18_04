FROM nvidia/opengl:base-ubuntu18.04

RUN apt update; \
    apt install -y \
    libsdl1.2debian \
    libsdl-mixer1.2 \
    libglfw3 \
    libgcrypt20 \
    gstreamer1.0-plugins-good \
    gstreamer1.0-libav \
    libopengl0 \
    mesa-utils \
    alsa-utils \
    gdb \
    libdwarf1

WORKDIR /opt
