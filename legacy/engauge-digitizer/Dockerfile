FROM centos:6
ADD https://github.com/AppImageCommunity/pkg2appimage/raw/master/recipes/engauge-digitizer/Recipe /Recipe
RUN sed -i -e 's|sudo ||g' Recipe && bash -ex Recipe && yum clean all && rm -rf /Engauge-Digitizer/Engauge-Digitizer* && rm -rf /out
