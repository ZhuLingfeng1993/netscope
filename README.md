# Netscope CNN Analyzer

available here: http://cwlacewe.github.io/netscope 

This is a CNN Analyzer tool, based on the Netscope fork by [dgschwend](https://github.com/dgschwend) which was originally by [ethereon](https://github.com/ethereon).
Netscope is a web-based tool for visualizing neural network topologies. It currently supports UC Berkeley's [Caffe framework](https://github.com/bvlc/caffe).

### Documentation
- Netscope [Quick Start Guide](http://cwlacewe.github.io/netscope/quickstart.html)

### Installation
- Install npm
- Install http-server
-- npm install http-server -g

- start server 
-- cd netscope
-- http-server

- open in the browser
-- http://localhost:8080

### Demo
- [Visualization of ResNet-50](http://cwlacewe.github.io/netscope/#/preset/resnet-50)

### Usage

注意在网页100%的时候显示

有些参数是程序预设的,比如RFCN

修改css文件可以改变网页布局, 颜色等

netscope设置层的颜色, ,似乎修改本地的css文件不起作用, 直接在网页inspect上改有作用 , 还能方便地设置颜色; 

可以添加preset, 方便查看网络结构

DAG错误: 似乎top名和别的层的name名一样会引起错误, 修改名字即可

如果网络中某层的phase=TEST，则该层不会可视化，把phase改成TRAIN或者去掉phase参数即可可视化。

### License

Released under the MIT license.
All included network models provided under their respective licenses.
