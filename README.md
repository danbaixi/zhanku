### 站库 - 优质网站收藏库

------

#### 项目介绍

此项目用于收集优质网站，支持查看浏览记录和搜索，目前已收集100+个网站，以后也会不断收集新网站，喜欢的童鞋，请给个star哦。

该项目基于 <a href="https://github.com/WebStackPage/WebStackPage.github.io" target="_blank">WebStackPage</a> 项目修改

#### 修改内容
> 1. 使用art-template.js 渲染模板
> 2. 添加搜索网站功能
> 3. 添加访问历史记录
> 4. 优化一些体验
> 5. 删减一些文件

#### 在线预览
<a href="https://zk.yunxiaozhi.cn" target="_blank">https://zk.yunxiaozhi.cn</a>

#### 预览图
![预览图](/assets/images/screenshot.png)

#### 如何使用


##### 下载代码
``` bash
git clone git@github.com:danbaixi/zhanku.git
```
#####修改 assets/js/source.js
source.js结构如下：

``` js
{
    list:[

        //一级分类的结构
        {
            title: "分类标题"
            icon: "图标，使用awesome font库的图标，不需要带上fa-前缀",
            nav: [
                {
                    title: "网站名称",
                    desc: "网站描述",
                    url: "网站链接",
                    image: "logo图片，可为空"
                }
            ]
        }

        //多级分类的结构
        {
            title: "分类标题"
            icon: "图标，使用awesome font库的图标，不需要带上fa-前缀",
            child: {
                title: "子分类标题",
                nav: [
                    {
                        title: "网站名称",
                        desc: "网站描述",
                        url: "网站链接",
                        image: "logo图片，可为空"
                    }
                ]
            }
        }
    ]
}
```

#### 感谢
<a href="https://github.com/WebStackPage/WebStackPage.github.io" target="_blank">WebStackPage</a>

<a href="https://github.com/aui/art-template" target="_blank">art-template</a>