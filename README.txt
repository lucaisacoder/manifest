download:
  repo init -u git@github.com:lucaisacoder/manifest.git -b master
  repo sync -j32
  repo forall -c git checkout dev
