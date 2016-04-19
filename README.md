# scripts
# it will update your packages and software will be installed to '/usr/local/'!
# 脚本会更新一些包，并且默认安装软件到“/usr/local”下！

# install
./centos_install {srs|ats|nginx|apprtc|python|ffmpeg|redis|git|docker}
for example:
./centos_install srs

./ubuntu_install {janus}
for example:
./centos_install janus


# build lua to luac
./tools {toluac}
for example:
./tools toluac .
