## sublime text3汉化及markdown插件
### 一、汉化

* 第一步
下载sublie text3汉化包
http://pan.baidu.com/s/1pJqPkcb
* 第二步
打开sublime text 3，打开菜单->preferences->Browse Packages，进入到文件管理器
* 第三步
返回上一层到sublime text 3 文件夹，打开“Installed Packages”文件夹，把汉化包Default.sublime-package放到“Installed Packages”文件夹
这里不用重启sublime text3 已经汉化成功

### 二、markdown插件

#### 1、插件介绍

##### MarkdownEditing

MarkdownEditing是Markdown写作者必备的插件，它可以不仅可以高亮显示Markdown语法还支持很多编程语言的语法高亮显示。

##### OmniMarkupPreviewer

OmniMarkupPreviewer用来预览markdown 编辑的效果，同样支持渲染代码高亮的样式。

#### 2、插件安装

##### 安装"Package Control"

使用快捷键 " ctrl + `" 打开Sublime的控制台 ,或者选择 View > Show Console 。

在控制台的命令行输入框，把下面一段代码粘贴进去，回车 就可以完成Pacakge Control 的安装了。

```
import urllib.request,os,hashlib; h = 'eb2297e1a458f27d836c04bb0cbaf282' + 'd0e7a3098092775ccb37ca9d6b2e4b7d'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```

##### 安装MarkdownEditing

Package Control 安装成功后我们就可以使用它方便的管理插件了，首先使用快捷键 'Ctrl + shift + p ' 进入到Sublime 命令面板，输入 "package install" 从列表中选择 "install Package" 然后回车。这时候Sublime开始请求远程插件仓库的索引，所以第一次使用可能会有一些小的延时。
看到列表的更新之后输入 "markdown ed" 关键字，选择“MarkdownEditing" 回车。 插件安装完毕后需要重新启动Sublime插件才能生效。