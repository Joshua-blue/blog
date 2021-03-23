# 一、搭建环境

使用以下指令逐一查看开发环境，缺少自行安装：

```sh
ruby -v
gem -v
gcc -v
g++ -v
make -v
git --version
```

![image-20201019105907956](img/image-20201019105907956.png)

![image-20201019110003433](img/image-20201019110003433.png)

# 二、创建仓库

仓库名：equinox-flower

仓库描述：Equinox flower, open on the other side, flowers do not see leaves, leaves no flowers.

![image-20201019080726491](img/image-20201019080726491.png)



![image-20201019081133078](img/image-20201019081133078.png)

![image-20201019081641396](img/image-20201019081641396.png)

搭建Git简易网站：

![image-20201019081913531](img/image-20201019081913531.png)

选择喜欢的模板：

![image-20201019082658457](img/image-20201019082658457.png)

![image-20201019082746334](img/image-20201019082746334.png)

![image-20201019082855274](img/image-20201019082855274.png)

![image-20201019082913050](img/image-20201019082913050.png)



# 三、下载模板

http://jekyllthemes.org/

![image-20201019083053829](img/image-20201019083053829.png)

![image-20201019083202575](img/image-20201019083202575.png)

解压到桌面：

![image-20201019083230852](img/image-20201019083230852.png)

![image-20201019083347210](img/image-20201019083347210.png)

![image-20201019083435833](img/image-20201019083435833.png)



# 四、开始搭建

## 4.1、克隆仓库

把GitHub上的仓库克隆到本地。

复制HTTPS链接：

![image-20201019083758532](img/image-20201019083758532.png)



打开终端进行操作：

![image-20201019083951247](img/image-20201019083951247.png)



## 4.2、修改仓库

修改本地仓库内容。

将模板里所有文件复制到本地仓库中：

![image-20201019084420512](img/image-20201019084420512.png)

![image-20201019084451872](img/image-20201019084451872.png)

![image-20201019084526244](img/image-20201019084526244.png)



## 4.3、上传仓库

将修改后的本地仓库内容上传到远程仓库。

打开终端进入仓库目录操作：

![image-20201019085006492](img/image-20201019085006492.png)

![image-20201019085020630](img/image-20201019085020630.png)

刷新远程仓库：

![image-20201019085135171](img/image-20201019085135171.png)

访问网站地址：![image-20201019085247947](img/image-20201019085247947.png)

![image-20201019085339612](img/image-20201019085339612.png)

可能需要开启网站代理服务：

![image-20201019111530555](img/image-20201019111530555.png)

![image-20201019111548130](img/image-20201019111548130.png)





![image-20201019085404589](img/image-20201019085404589.png)



## 4.4、修改路径

解决网站未加载样式问题。

修改资源路径：

![image-20201019085717174](img/image-20201019085717174.png)

![image-20201019085627052](img/image-20201019085627052.png)

尝试修改路径：

![image-20201019085854605](img/image-20201019085854605.png)

预览修改效果：

![image-20201019085939293](img/image-20201019085939293.png)

修改config.yml文件：

![image-20201019093917163](img/image-20201019093917163.png)

![image-20201019094030423](img/image-20201019094030423.png)

再次提交：

![image-20201019101558624](img/image-20201019101558624.png)



稍作休息后多次刷新页面：

![image-20201019090908756](img/image-20201019090908756.png)

![image-20201019091228466](img/image-20201019091228466.png)



## 4.5、流量统计

使用 [百度统计](https://tongji.baidu.com/web/welcome/login)  进行网站访问流量统计。

![image-20201019091632951](img/image-20201019091632951.png)

![image-20201019091810116](img/image-20201019091810116.png)

复制代码到 head.html 文件头部：

![image-20201019091900061](img/image-20201019091900061.png)

![image-20201019092815646](img/image-20201019092815646.png)

![image-20201019092851397](img/image-20201019092851397.png)

再次提交：

![image-20201019101935259](img/image-20201019101935259.png)

查看效果：

![image-20201019102122380](img/image-20201019102122380.png)

![image-20201019103943267](img/image-20201019103943267.png)



## 4.6、完善网站

根据自身需求，修改配置文件，配置专属网站。

![image-20201025222248759](img/image-20201025222248759.png)



![image-20201025222355075](img/image-20201025222355075.png)

![image-20201025222432322](img/image-20201025222432322.png)

![image-20201025222520388](img/image-20201025222520388.png)



# 五、本地运行

参考：http://jekyllcn.com/

![image-20210320154203030](img/image-20210320154203030.png)

下面以**seacoast**项目为例：

## 5.1、获取jekyll项目

### 5.1.1、选择项目

从GitHub上获取托管的jekyll项目。

登录自己的**git**帐号，选择要在本地运行的项目，点击进入该项目，准备克隆或下载该项目：

![image-20210320154415106](img/image-20210320154415106.png)



### 5.1.2、克隆项目

克隆或下载项目到本地：

![image-20210320154855696](img/image-20210320154855696.png)

方式一：使用指令获取

复制HTTPS地址，在本地打开终端使用git指令克隆远程仓库：

```shell
git clone https://github.com/Joshua-blue/seacoast.git
```



![image-20210320155150315](img/image-20210320155150315.png)

![image-20210320155913460](img/image-20210320155913460.png)



方式二：下载压缩包

![image-20210320160038638](img/image-20210320160038638.png)

![image-20210320160112604](img/image-20210320160112604.png)

![image-20210320162046147](img/image-20210320162046147.png)



## 5.2、本地运行jekyll项目

打开终端，进入**jekyll**项目，使用指令运行。

### 5.2.1、进入项目

```shell
cd seacoast/
```

![image-20210320160424918](img/image-20210320160424918.png)



### 5.2.2、安装运行环境

```shell
bundle install
```

![image-20210320160614244](img/image-20210320160614244.png)

![image-20210320160629441](img/image-20210320160629441.png)



### 5.2.3、运行jekyll项目

```shell
bundle exec jekyll serve
```

![image-20210320160831755](img/image-20210320160831755.png)

报错：

```shell
Please append `--trace` to the `serve` command 
                     for any additional information or backtrace. 
```

原因分析及解决措施：

原因：

1. 可能有相同的服务启动;
2. **_config.yml**配置文件报错;

解决办法：

如果是存在其他类似的服务启动，则只需要关闭其他服务即可;

对于配置文件出错，我们只需要根据提示信息，使用指令跟踪出错的地方做出相应修改即可解决问题。

以下以实际操作为例：

第一类出错情况(存在相同服务启动)：

本地已经运行了一个**jekyll**项目：

![image-20210322125203197](img/image-20210322125203197.png)

现在再尝试运行另一个**jekyll**项目：

![image-20210322125346590](img/image-20210322125346590.png)

启动失败，根据提示信息，即可判断大致原因是由于端口占用的问题：

![image-20210322125552428](img/image-20210322125552428.png)

关闭上一个项目再次运行即可:

![image-20210322125817269](img/image-20210322125817269.png)



第二类出错(配置文件问题)：

从**github**上导出的**jekyll**工程可能在参数的配置上有出入，从而导致在本地失败。

![image-20210322150945721](img/image-20210322150945721.png)

根据**trace**到的信息，打开**_config.xml**配置文件搜索 **jekyll-theme-cayman**：

![image-20210322151202905](img/image-20210322151202905.png)

![image-20210322151257856](img/image-20210322151257856.png)

提示此处配置找不到，将其注释或删除掉，保存、退出，再次运行：

![image-20210322151441528](img/image-20210322151441528.png)

![image-20210322151508783](img/image-20210322151508783.png)



### 5.2.4、绑定主机或端口号

1、查看指令说明：

```shell
jekyll -h
```

指令说明:

```shell
jekyll 4.2.0 -- Jekyll is a blog-aware, static site generator in Ruby

Usage:

  jekyll <subcommand> [options]

Options:
        -s, --source [DIR]  Source directory (defaults to ./)
        -d, --destination [DIR]  Destination directory (defaults to ./_site)
            --safe         Safe mode (defaults to false)
        -p, --plugins PLUGINS_DIR1[,PLUGINS_DIR2[,...]]  Plugins directory (defaults to ./_plugins)
            --layouts DIR  Layouts directory (defaults to ./_layouts)
            --profile      Generate a Liquid rendering profile
        -h, --help         Show this message
        -v, --version      Print the name and version
        -t, --trace        Show the full backtrace when an error occurs

Subcommands:
  compose               
  docs                  
  import                
  build, b              Build your site
  clean                 Clean the site (removes site output and metadata file) without building.
  doctor, hyde          Search site and print specific deprecation warnings
  help                  Show the help message, optionally for a given subcommand.
  new                   Creates a new Jekyll site scaffold in PATH
  new-theme             Creates a new Jekyll theme scaffold
  serve, server, s      Serve your site locally

```

中文解释：

```shell
--config CONFIG_FILE [，CONFIG_FILE2，...]自定义配置文件
        -d，--destination DESTINATION当前文件夹将生成到DESTINATION中
        -s，-source源自定义源目录
            --future发布具有将来日期的帖子
            --limit_posts MAX_POSTS限制要分析和发布的帖子数
        -w，-[no-] watch监视更改和重建
        -b，--baseurl URL从给定的基本URL服务网站
            --force_polling强制监视以使用轮询
            --lsi使用LSI改善相关职位
        -D，--drafts渲染_drafts文件夹中的帖子
            -未发布标记为未发布的渲染帖子
            --disable-disk-cache禁用以非安全模式缓存到磁盘
        -q，--quiet静默输出。
        -V，--verbose打印详细输出。
        -I，--incremental启用增量重建。
            --strict_front_matter如果前端问题存在错误，则失败
            --ssl-cert [CERT] X.509（SSL）证书。
        -H，--host [HOST]要绑定的主机
        -o，--open-url在浏览器中启动网站
        -B，--detach在后台运行服务器
            --ssl-key [KEY] X.509（SSL）私钥。
        -P，--port [PORT]用于侦听的端口
            --show-dir-listing显示目录列表，而不是加载索引文件。
            --skip-initial-build跳过在启动服务器之前发生的初始站点构建。
        -l，-livereload使用LiveReload自动刷新浏览器
            --livereload-ignore忽略GLOB1 [，GLOB2 [，...]]用于LiveReload忽略的文件。请记住用引号引起来，以使您的外壳不会扩展它们
            --livereload-min-delay [SECONDS]最小重载延迟
            --livereload-max-delay [SECONDS]最大重载延迟
            --livereload-port [PORT] LiveReload用来侦听的端口
        -s，--source [DIR]源目录（默认为./）
        -d，--destination [DIR]目标目录（默认为./_site）
            --safe安全模式（默认为false）
        -p，--plugins PLUGINS_DIR1 [，PLUGINS_DIR2 [，...]]插件目录（默认为./_plugins）
            --layouts DIR布局目录（默认为./_layouts）
            --profile生成液体渲染配置文件
        -h，--help显示此消息
        -v，--version打印名称和版本
        -t，--trace发生错误时显示完整的回溯
```

2、给服务绑定端口号

```shell
jekyll serve -P 8090
```

![image-20210322163129402](img/image-20210322163129402.png)

![image-20210322163254126](img/image-20210322163254126.png)
