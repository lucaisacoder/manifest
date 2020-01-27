download:
  repo init -u git@github.com:lucaisacoder/manifest.git -b master
  repo sync -j32
  repo forall -c git checkout -b dev origin/dev

create new branch:
  repo forall -c git checkout -b [new branch name]
  repo forall -c git push origin [new branch name]
  
 
