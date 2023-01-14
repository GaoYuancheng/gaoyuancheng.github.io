### 使用 hexo 搭建

1. npm i hexo -g
2. hexo init
3. yarn add hexo-deployer-git
4. 修改 \_config.yaml 在最后 deploy 设置自己存放打包后资源的分支; 在项目中的 settings/pages 中配置要部署的分支
5. yarn build && yarn deploy

### 注意

每次更新都要重新 build
