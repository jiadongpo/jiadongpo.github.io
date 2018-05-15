# jiadongpo.github.io

* 安装服务：
npm install hexo-cli -g
npm install hexo-server —save 

* 初始化项目
hexo init HexoJiadongpo
cd HexoJiadongpo

* 下载主题：
git clone https://github.com/theme-next/hexo-theme-next themes/next

npm install
hexo server



问题：
ERROR Deployer not found: git
npm install --save hexo-deployer-git


##系统设置 _config.yml文件

### 修改语言
根据主要所使用的主题对应的,如theme: next，/themes/next/languages下对应的中文
language: zh-CN


## Next主题设置
next/_config.yml配置相关修改

###默认是居中的，修改为scheme: Mist。

### 显示对应的标题
menu下，打开注释即可。

去见面尾部的脚本
footer.swig


## 标题图标
favicon:
#  small: /images/favicon-16x16-next.png
#  medium: /images/favicon-32x32-next.png


侧边头像
sidebar-author.styl
avatar.gif