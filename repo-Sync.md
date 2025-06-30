git remote add upstream git@github.com:yudaocode/yudao-cloud-mini.git

git fetch upstream

git checkout master

git merge upstream/master

git add .

git commit -m "remark"

git push origin master