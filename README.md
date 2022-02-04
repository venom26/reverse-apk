# reverse-apk
```
apt-get install unzip smali apktool dex2jar jadx

export GOPATH=/opt/bbscope
go get -u github.com/sw33tLie/bbscope
ln -s /opt/bbscope/bin/bbscope /usr/local/bin/bbscope

export GOPATH=/opt/anew
go get -u github.com/tomnomnom/anew
ln -s /opt/anew/bin/anew /usr/local/bin/anew

export GOPATH=/opt/nuclei
go get -u -v github.com/projectdiscovery/nuclei/v2/cmd/nuclei
ln -s /opt/nuclei/bin/nuclei /usr/local/bin/nuclei

git clone https://github.com/ko2sec/apkizer.git || git -C /opt/apkizer pull
cd apkizer
pip3 install -r requirements.txt
cd ..
```

#Useful files
```
https://bitbucket.org/JesusFreke/smali/downloads/
https://sourceforge.net/p/dex2jar/wiki/UserGuide/
https://github.com/skylot/jadx/releases/tag/v1.3.2
https://lindevs.com/install-jadx-on-ubuntu/
```
