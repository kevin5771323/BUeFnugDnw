# 前言

欢迎来到展柜设计公司平面布置小程序！这是一个基于Spring Boot框架开发的便捷工具，旨在为展柜设计公司提供高效的平面布置解决方案。本项目的目的是将传统的展柜设计过程数字化、便捷化，通过微信小程序实现与用户的互动。以下将为您详细介绍本项目的相关内容。

# 内容介绍

本项目主要包括以下功能模块：展柜设计、平面布置、方案管理、用户管理等。用户可以通过微信小程序端轻松创建、修改和查看展柜设计方案，同时支持多用户协作。后端采用Spring Boot技术栈，确保系统的高效稳定运行。

# 技术介绍

## 语言：Java

## 使用框架：Spring Springmvc，mybatis，微信小程序

## 前端技术：JS、Vue、css3，Uniapp

## 开发工具：IDEA/Eclipse，Uniapp

## 数据库：MySQL 5.7/8.0

## 数据库管理工具：phpstudy/Navicat

## JDK版本：jdk1.8

## Maven: apache-maven 3.8.1-bin

## 前端环境：Node.Js 12\14\16

# 核心代码

以下为项目中的一个核心代码示例，展示如何通过MyBatis实现展柜设计方案的数据持久化：

```java
// 展柜设计方案实体类
public class CabinetDesign {
    private int id;
    private String name;
    private String layout;
    // 省略 getter 和 setter 方法
}

// MyBatis Mapper 接口
public interface CabinetDesignMapper {
    // 添加展柜设计方案
    void addCabinetDesign(CabinetDesign cabinetDesign);
    // 更新展柜设计方案
    void updateCabinetDesign(CabinetDesign cabinetDesign);
    // 删除展柜设计方案
    void deleteCabinetDesign(int id);
    // 查询展柜设计方案列表
    List<CabinetDesign> listCabinetDesigns();
}

// Mapper XML配置
<mapper namespace="com.example.mapper.CabinetDesignMapper">
    <insert id="addCabinetDesign">
        INSERT INTO cabinet_design (name, layout) VALUES (#{name}, #{layout})
    </insert>
    <!-- 其他 SQL 语句 -->
</mapper>
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图
![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/343981/14/3063/133618/68c57ba0F051c8b4d/64c6e4b79edcddc8.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/324078/7/18930/24992/68c57b77Fc407dc1d/229be44fe114f164.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/335967/4/10234/22163/68c57b77Fa70b2967/8f0e9ced33c4d380.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/332674/8/12729/48730/68c57b77Ffe6ab847/1ec570ea58fe9173.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/349790/25/3044/20964/68c57b78F92b4ffae/209ec5abd5e88fbc.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/328916/9/19757/18322/68c57b78F82e901de/55ade5b54df2ed18.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/346054/31/3061/72343/68c57b78F1c1b5a47/eb420cd0f74a3847.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/347577/23/3104/20914/68c57b78F7882c06c/4d978022e2a7b486.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/337363/40/10419/53006/68c57b78F98d9b121/1a4ad00343124ae1.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/331605/3/13062/64062/68c57b79Fb40baa4b/3a4bc27f9b8b57ee.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
