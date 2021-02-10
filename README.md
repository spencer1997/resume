## 使用
1. fork本项目后再clone到本地修改
2. 进入项目目录执行`npm i`安装依赖
3. 执行`npm run dev`开始开发，根据你的情况修改`src/index.html`里的内容
4. 替换webpack-dist.config.js文件里的resume.wuhaolin.cn为你自己的域名（腾讯云）
5. 改完后`npm run build`打包，然后push到master分支（不合并或者版本不一致的话，建议强制上传，后面加-f），Github Action会自动部署
