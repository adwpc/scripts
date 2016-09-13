# scripts
# it will update your packages and software will be installed to '/usr/local/'!
# 脚本会更新一些包，并且默认安装软件到“/usr/local”下！
# ubuntu_install kms need at least 8g memory

# install
sudo bash centos_install {srs|ats|nginx|apprtc|python|ffmpeg|redis|git|docker}  
for example:  
sudo bash centos_install srs

sudo bash ubuntu_install {janus|ffmpeg|kms}  
for example:  
sudo bash ubuntu_install janus


# build lua to luac
sudo bash tools {toluac} dir 
for example:  
sudo bash tools toluac .
