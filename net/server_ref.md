<!-- YAML
added: v0.9.1
-->

与`unref`相反, 在一个原先是`unref`的服务器上调用 `ref` 将*不会*允许程序退出 
即使它是唯一剩下的服务器（默认行为）。如果服务器已经是`ref`的了，再次调用`ref`将
不会产生效果。

返回`server`.

