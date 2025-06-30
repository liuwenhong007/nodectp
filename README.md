# windows
```
#初始化c++编译环境
npm install --global --production windows-build-tools
cp binding-windows32.gyp  binding.gy (cp binding-windows64.gyp  binding.gy)
node-gyp rebuild
#代码里面或者系统PATH中设置ctp的dll的路径
node ./test/mduser.js
#node ./test/tduser.js
```
# linux
```
cp binding-linux.gyp  binding.gy
node-gyp rebuild
node ./test/mduser.js
#node ./test/tduser.js
```
# 安装环境 linux
node -v  v10.24.1
node-gyp -v v7.1.2
python -v v3.10