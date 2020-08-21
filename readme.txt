#### 后端

1. IDEA 或者 Eclipse安装lombok插件

2. 新建MySQL（版本5.7.x）数据库，导入[SQL]文件

3. 导入[backend项目]

4. 修改数据库配置，redis配置，等待Maven下载依赖

5. 启动backend项目

#### 前端

1. 安装node.js

2. 切换到frontend文件夹下

# 安装yarn
npm install -g yarn

# Yarn 淘宝源安装
yarn config set registry https://registry.npm.taobao.org -g 
yarn config set sass_binary_site http://cdn.npm.taobao.org/dist/node-sass -g

# 下载依赖
yarn install

# 启动
yarn start