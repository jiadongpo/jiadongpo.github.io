# jiadongpo.github.io
**hexo源文件分支**

##Hexo主题使用

###添加图片
http://www.tuicool.com/articles/umEBVfI  
1.首先确认_config.yml 中有 post_asset_folder:true。  
Hexo 提供了一种更方便管理 Asset 的设定：post_asset_folder,当您设置post_asset_folder为true参数后，在建立文件时，Hexo
会自动建立一个与文章同名的文件夹，您可以把与该文章相关的所有资源都放到那个文件夹，如此一来，您便可以更方便的使用资源。  
2.在hexo的目录下执行npm install https://github.com/CodeFalling/hexo-asset-image --save（需要等待一段时间）。  
3.完成安装后用hexo新建文章的时候会发现_posts目录下面会多出一个和文章名字一样的文件夹。 只要使用 ![logo](本地图片测试/logo.jpg) 就可以插入图片。其中[]里面不写文字则没有图片标题。  

!["分布式排序"](/images/meizhuang.png)

###表格实现方式
<table>
    <tr>
        <th>属性项</th>
        <th>属性说明</th>
    </tr>
    <tr>
        <td>组件名称</td>
        <td>步骤的名字，这个名字在一个转换中必须是唯一的。</td>
    </tr>
    <tr>
        <td>字段</td>
        <td>指定字段名和排序方向(升序/降序);点击获取字段检索列表字段从输入流。</td>
    </tr>
    <tr>
        <td>字段</td>
        <td>指定排序的字段名。</td>
    </tr>
    <tr>
        <td>升序</td>
        <td>排序原则：升序或降序。如果选择升序，    
        排序顺序将是：数字->英文->汉字，汉字是按照拼音排序的，    
        也同样会按照声调排序。如果是多音字，只会取一个读音，    
        无法根据语境判断其的读音。</td>
    </tr>
</table>

##注释
[comment]: <> (This is a comment, it will not be included)
[comment]: <> (in  the output file unless you use it in)
[comment]: <> (a reference style link.)
[//]: <> (This is also a comment.)
[//]: # (This may be the most platform independent comment)


test
