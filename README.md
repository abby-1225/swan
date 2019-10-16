# swan
#learn swan from compile

#1.官网下载（需要编译的，windows可以直接用exe），上传到服务器，解压
或者直接linux下：

wget http://swanmodel.sourceforge.net/

tar -xzvf swan4131.tar.gz

cd  swan4131

make config

make mpi  #需要提前装mpich，详情见wrf里的安装，若无需串行，则改为（make ser）


chmod +x swan.exe（若绿色，表示已经为可执行文件，则可省略这一步）

