Use OpenCV feature2d module to locate ground targets from Quadcopter video.

# Installing

# virtualenv

# opencv 3.2

cmake \
      -D MAKE_BUILD_TYPE=RELEASE \
      -D CMAKE_INSTALL_PREFIX=$VIRTUAL_ENV/local/ \
      -D PYTHON_EXECUTABLE=$VIRTUAL_ENV/bin/python \
      -D PYTHON_PACKAGES_PATH=$VIRTUAL_ENV/lib/python2.7/site-packages \
      -D INSTALL_PYTHON_EXAMPLES=ON \
      ..


make -j7
make install
