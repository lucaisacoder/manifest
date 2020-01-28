download:
  repo init -u https://github.com/lucaisacoder/manifest.git -b master
  repo sync -j32
  repo forall -c git checkout -b dev origin/dev
  repo forall -c git push
  
usage:
  cd ./tools/cmake/
  mkdir build
  cd build
  cmake ..
  make
