# swan
#learn swan from compile

#1.downlosd and compile 安装和编译


[官网下载压缩包](http://swanmodel.sourceforge.net/)（这个是需要编译的，windows下可以直接下载exe，[串行](http://swanmodel.sourceforge.net/download/zip/setup-SWAN-41.31.exe)版本和[并行](http://swanmodel.sourceforge.net/download/zip/setup-SWAN-41.31-omp.exe)版本），上传到服务器，解压


![ad](https://github.com/abby-1225/swan/blob/master/images/download.png)


或者在直接linux下：

wget http://swanmodel.sourceforge.net/download/zip/swan4131.tar.gz

tar -xzvf swan4131.tar.gz

cd  swan4131

make config

make mpi  #需要提前装mpich，详情见wrf里的安装，若无需串行，则改为（make ser）
![ad](https://github.com/abby-1225/swan/blob/master/images/swan-compile.png)


chmod +x swan.exe（若绿色，表示已经为可执行文件，则可省略这一步）

![ad](https://github.com/abby-1225/swan/blob/master/images/chmod.png)
