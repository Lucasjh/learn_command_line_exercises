`pushd some/file/etc` will set a bookmark at the directory you started from and pushd'd to. 
(In this case from above some/ and into etc/). 

calling `pushd` again (in Unix systems only) will bring you back to your original starting point. Calling `pushd` once more will bring you to your second book mark. This can be done ad infinitum back and forth between the two.

`pushd some/file/etc` will set the said bookmarks from before, but if you would like to 'stack' more bookmarks you can. from above etc/ you can continue to `pushd`
forward. `pushd etc/1/2/3/4` sets yet another bookmark in directory 4/. `pushd` still allows you to move back and forth between your last two bookmarks.

to remove bookmarks from your stack, you can call `popd` and it will delete the current bookmark and bring you back to the previous `pushd`.

While practicing `pushd` and `popd`, we started in /temp, push'd to /icecream, pop'd back to /temp
push'd to /i/like, then push'd to /icecream, pop'd back to /like, then back to /temp, then push'd to /icecream, then push' back to /temp, then push'd forward to /icecream, and a `pwd` revealed that we were currently in /icecream.

