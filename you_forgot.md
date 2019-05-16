You need to clone the repo first, after that do this.

## this pulls any changes from the master branch

$ git pull origin master  
From https://github.com/SEDoug/web_template
 * branch            master     -> FETCH_HEAD
Already up to date.

$ git add .    '//this will add any new or edited files on local

$ git commit -m "upload images"   '//this will commit your new changes to the master branch
[master da23c23] upload images
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 img/library-la-trobe-study-students-159775.jpeg
 create mode 100644 img/pexels-photo-373076.jpeg
 create mode 100644 img/pexels-photo.jpg
 
 $ git push origin master   '//this will push new, edited changes to the master branch
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 591.07 KiB | 15.16 MiB/s, done.
Total 6 (delta 0), reused 0 (delta 0)
To https://github.com/SEDoug/web_template.git
   7112e33..da23c23  master -> master
