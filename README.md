crxmake
=======

make crx by bash

A mirror of https://code.google.com/p/chromium/issues/attachmentText?id=15059&aid=-2305436989939443553&name=crxmake.sh posted by jaysoffian

----------------------

### Usage

```
crxmake.sh <extension dir> <pem path>
```

### 这是啥

这个仓库只是 jaysoffian 所写的编译crx 的bash脚本的一个镜像.

另外从[这里](https://curetheitch.com/projects/buildcrx/other-building-utilities/)找到另外一些 crx build 的方案.

* Ruby : [crxmake.rb](http://github.com/Constellation/crxmake) by Constellation
* Python : [crxmake.py](http://github.com/bellbind/crxmake-python) by bellbind
* Python : [packer.py](http://grack.com/blog/2009/11/09/packing-chrome-extensions-in-python/) by Matt Mastracci
* C : [buildcrx](https://curetheitch.com/projects/buildcrx) by Kyle L. Huff (me)

#### Windows 上怎么用?

如果你是用 `cygwin` 应该没有任何问题, 如果你只有 `Git Bash`, 可能会缺少 `xxd` 和 `zip` 命令, 你可以从[这里](https://github.com/darkfe/crxmake/tree/master/bin)下载到这两个`exe`.

[origin](http://www.stahlworks.com/dev/index.php?tool=zipunzip)
