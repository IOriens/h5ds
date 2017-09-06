### **简介** 

H5DS 官方 Git (https://gitee.com/676015863/H5DS) ，简体中文 UTF8 版本，其他版本请自行转码
![img](build/assets/images/demo.png)

### **声明**

您可以下载本站代码，但未经许可 **禁止** 在本产品的整体或任何部分基础上以发展任何派生版本、修改版本或第三方版本用于 **重新分发** ,您可以下载源码进行学习或者在企业内部使用而无需支付任何费用，在未获得成都飞酷网络的书面授权之前，不能将该工具内嵌到其他项目中，也不能将该工具提供给自身客户或者三方客户使用等商业用途，您若有违反规定，成都飞酷网络科技有限公司有权随时中止或终止您对成都飞酷网络产品的使用资格并保留追究相关法律责任的权利

### **相关网站**
 
- h5ds 官方站：http://www.h5ds.com

### **技术交流群**

[QQ群 549856478](https://jq.qq.com/?_wv=1027&k=5I0kPBX)

### **友情提示**

若有BUG，请及时issues我们，会第一时间做修改！

### **安装使用说明**

运行环境 node v6.x mysql v5.6

1. 新建数据库h5ds，导入数据 h5ds.sql，进入目录 /h5ds/build/conf 修改数据库配置
2. 进入目录/h5ds 安装开发库所需依赖 npm i
3. 进入目录/h5ds/build 安装后端所需依赖 npm i
4. 进入目录/h5ds 启动开发环境 npm start
5. 进入目录/h5ds/build 启动后端环境 npm start
6. 浏览器输入：http://localhost:8000 即可访问
7. 进入目录/h5ds 打包 npm run build

### **更新说明**

#### 2017-09-06 更新记录
1. 小动了下架构，新增PageClass 类，用于被其他类继承。
2. 添加了自定义弹窗功能
3. 添加了自定义浮动层功能
4. 添加了显示隐藏的交互
5. 添加了页面自定义ID的功能