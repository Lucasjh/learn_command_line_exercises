Make 20 directories and remove them all

`mkdir -p 1/2/3/4/5/6/7/8/9/10/11/12/13/14/15/16/17/18/19/20`

`rmdir -p 1/2/3/4/5/6/7/8/9/10/11/12/13/14/15/16/17/18/19/20`

Make a single path of directories that is 10 deep and remove them one at a time like i did above.

`mkdir -p 1/2/3/4/5/6/7/8/9/0`

`cd 1/2/3/4/5/6/7/8/9`

`rmdir 0`

`cd ..`

`rmdir 9`

...

`cd ..`

`rmdir 1`


