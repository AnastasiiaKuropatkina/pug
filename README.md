"# pug"
------
Use pug
=======
    [comment]: <> (our directories)
    $ cd jade/ 
    $ pug --help
    [//]: # (render all files in 'jade' (and other '') directories to '/html')
    $ pug jade/ --out html 
    $ pug {index, case}.pug //create {index,case}.html
    $ pug -P index.pug //complite pretty HTML output
    $ pug -P -w index.pug //complite pretty HTML output auto
    

Installation
=============
    $ npm install jade --global