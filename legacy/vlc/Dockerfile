FROM centos:6
ADD https://github.com/AppImageCommunity/pkg2appimage/raw/master/recipes/vlc/Recipe /Recipe
RUN bash -ex Recipe ; yum clean all ; rm -rf /usr/src ; rm -rf /out ; rm -rf /VLC/VLC.AppDir ; rm -rf /VLC/vlc-*.tar.xz
