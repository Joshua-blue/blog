# Deeping 安装jekyll

参考官网地址：https://jekyllrb.com/docs/  或 http://jekyllcn.com/

参考 https://jekyllrb.com/docs/  进行安装：

![image-20201016162001086](img/image-20201016162001086.png)

备注：安装好`Ruby`后根据上述图片提示，逐次使用版本查看指令查看。



# 一、安装Ruby

## 1.1、安装指令

```sh
sudo apt-get install ruby-full
```

## 1.2、查看指令

```sh
ruby -v
```

## 1.3、操作截图

![image-20201016155121915](img/image-20201016155121915.png)



## 1.4、参考指南

https://www.ruby-lang.org/zh_cn/documentation/installation/#apt

![image-20201016155445134](img/image-20201016155445134.png)



# 二、安装g++

安装好`Ruby`后，根据官网的提示，逐一使用下列指令查看：

![image-20201016162001086](img/image-20201016162001086.png)

![image-20201016163341106](img/image-20201016163341106.png)

根据提示信息，需要安装g++。

## 2.1、安装指令

```sh
sudo apt-get install g++ 
```

## 2.2、查看指令

```sh
g++ -v
```

## 2.3、操作截图

![image-20201016164251272](img/image-20201016164251272.png)

# 二、安装jekyll

## 3.1、安装

安装指令：

```sh
sudo gem install jekyll bundler
```

操作截图：

![image-20201016165246165](img/image-20201016165246165.png)

## 3.2、创建

安装指令：

```sh
jekyll new myblog
```

操作截图：

![image-20201016170048856](img/image-20201016170048856.png)

## 3.3、启动服务

进入myblog：

```sh
cd myblog
```

启动服务：

```sh
bundle exec jekyll serve
```

访问端口：

![image-20201016170658288](img/image-20201016170658288.png)

操作截图：

![image-20201016170444807](img/image-20201016170444807.png)