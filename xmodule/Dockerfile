FROM hugodby/fedora32
MAINTAINER Johnny Chang
RUN yum -y install @development-tools
RUN yum -y install xorg-x11-server-Xorg
RUN yum -y install libX11-devel.i686
RUN yum -y install xorg-x11-util-macros xorg-x11-server-devel libXext-devel libXi-devel libXrandr-devel libXinerama-devel libudev-devel
#can congfigure correctly
COPY /home/johnny/Downloads/xf86-input-evdev-2.5.0/inputstr.h /
