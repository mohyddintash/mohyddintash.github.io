# mohyddintash.github.io

if you delete public folder locally and deploy.sh fails, then first from

the main project root folder,

run 

`git add.`

`git commit -m 'commit message` 

`git push origin master` 

Then run

`./deploy.sh "commit message"` and it shoud work again.
