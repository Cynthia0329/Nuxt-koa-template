# Nuxt-koa-template
>  KoaJS + Nuxt.js官方模板优化版 
>
> [官方模板源码地址](https://github.com/nuxt-community/koa-template)



起因：

官方的模板中构建成功后运行项目会报错，在相关的issues中也有反映。

但是官方并没有及时更新，自己提交一个优化版做备用



修改的部分：

- 修改 `package.json` 部分出现问题的库的版本号（官方的没有及时更新，导致出现报错）

- 在 `nuxt.config.js` 文件中对eslint检查关闭，防止运行报错 
   （这个有部分原因是因为我用的vscode已经安装了eslint的插件进行代码规范，不需要再次检查，出现多余的报错）



该项目文件使用方式：

- 下载该项目
- 安装包（注意：直接用npm，不要用cnpm！）
- 运行该项目即可







