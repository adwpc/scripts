# scripts
# test in centos6.x,it will update your packages and software will be installed to '/usr/local/'!
# 在centos6上测试过，脚本会更新一些包，并且默认安装软件到“/usr/local”下！

# install
./install {srs|ats|nginx|apprtc|python|ffmpeg|redis|git|docker}
for example:
./inst srs
./inst ats
./inst ...

# build lua to luac
./tools {toluac}
for example:
./tools toluac .
