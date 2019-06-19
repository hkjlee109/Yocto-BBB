# Yocto-BBB

```
git submodule add -b rocko https://git.yoctoproject.org/git/poky ./sources/poky-rocko
git submodule add -b rocko https://github.com/meta-qt5/meta-qt5 ./sources/meta-qt5
git submodule add -b rocko https://github.com/openembedded/meta-openembedded ./sources/meta-openembedded
git submodule add -b rocko https://git.yoctoproject.org/git/meta-ti ./sources/meta-ti
```

And add your own meta layer.
eg. 
```
git submodule add https://github.com/jumpnow/meta-bbb ./source/meta-bbb
```
