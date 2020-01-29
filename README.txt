< master >
download:
  repo init -u https://github.com/lucaisacoder/manifest.git -b defaul -m default
  repo sync -j32
  repo forall -c git checkout -b dev origin/dev

create new branch:
  repo forall -c git checkout -b [new branch name]
  repo forall -c git push origin [new branch name]
  
< cmake_modules >
download:
  repo init -u https://github.com/lucaisacoder/manifest.git -b default -m cmake_modules
  repo sync -j32
  repo forall -c git checkout -b cmake_modules origin/cmake_modules
