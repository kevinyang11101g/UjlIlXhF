## 前言

欢迎来到我们的基于SSM的家政服务系统项目！在这个项目中，我们致力于打造一个高效、便捷、可靠的家政服务平台，为用户提供优质的家政服务。以下是关于本项目的详细介绍。

## 内容介绍

本项目是一个基于SSM（Spring、SpringMVC、MyBatis）框架的家政服务系统。系统主要包括用户模块、服务模块、订单模块、支付模块等功能。用户可以在平台上轻松预约家政服务，包括保洁、月嫂、育儿嫂等。通过本系统，我们希望提高家政服务行业的效率，为用户提供更好的服务体验。

## 技术介绍

- 语言：Java
- 使用框架：Spring、SpringMVC，MyBatis
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是本项目中的一个核心代码片段，展示了如何使用MyBatis实现服务列表的查询：

```java
// ServiceMapper.xml
<select id="queryServiceList" resultType="Service">
    SELECT * FROM service WHERE status = #{status}
</select>

// ServiceMapper.java
public interface ServiceMapper {
    List<Service> queryServiceList(@Param("status") int status);
}

// ServiceService.java
public List<Service> queryServiceList(int status) {
    return serviceMapper.queryServiceList(status);
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图

![封面图片](https://img12.360buyimg.com/ddimg/jfs/t1/339318/20/1663/84232/68ac8cfaF507f5be9/9f4d49ff58c3b8f5.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/333534/36/4111/15392/68ac8cd3Fe6f76aa4/44738d5b2aa6d9b8.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/340587/39/1636/34008/68ac8cd4F5337abff/7002505e866f2a9f.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/334019/39/4097/24329/68ac8cd6Fc110307f/bcb39d1c103ccfab.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/338315/26/1656/19931/68ac8cd6F7c828c4c/298321c3873069ef.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/329565/36/4027/8733/68ac8cdaFcbee224d/eaae8e28fa7e0080.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/338996/16/1526/65357/68ac8cdbFae6028a0/06caf4d2cfbbff24.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/330630/28/4084/43630/68ac8cdbF7f9d1273/d5428bb3efcfc7df.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/332238/40/4151/39895/68ac8cdcF23d3c3ed/f2b63e3d907ca807.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/336265/19/1673/15209/68ac8cdcF37aa7ade/96d0ca91f551a9bf.jpg)

