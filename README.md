# shishang
本项目为大三上学期（即2017年下半年）的PHP实训课程期末作品，我选择了做一个关于食品类的典型企业网站

2020-2-29  重新试运行，无错误，网站可正常运行

1.data文件夹中的shishang.sql文件在localhost/phpmyadmin中可直接导入

2.项目有菜单料理、热销产品、新闻动态、招商加盟以及后台管理等功能

3.菜单料理和热销产品进行了分类管理，分为中式菜品、日式料理、各式甜点以及饮品饮料便于用户进行选择性浏览

4.热销产品根据用户对菜品的点击量进行的排序

5.菜单料理、热销产品、新闻动态没有采用之前做的上下分页操作，而是利用PHP对加载数量进行循环显示在本页面

6.招商加盟拥有邮件的接收以及发送功能，倘若用户希望加盟我们填写信息进行提交后，系统自动发送邮件告知已收到申请将会尽快和您联系

7.后台管理分为加盟列表、动态发布、产品发布以及管理和回收站等功能

8.加盟列表为储存的进行申请的加盟用户信息：用户名、联系电话、加盟地址、邮箱以及申请时间，在此基础上管理员对是否联系以及用户是否确认加盟进行确认，方便进行管理

9.动态发布以及产品发布功能一致，不同在于动态发布漏做了选择图片同时对图片进行显示的功能，另图片进行上传之后将自动更改文件名为数字形式，利于页面进行查找显示

10.管理模块主要对菜品的标题、访问量、最后更新的时间以及产品的状态（新闻动态或产品）进行显示，管理员可以对其进行彻底删除、修改以及放入回收站等操作

11.放入回收站的菜品在删除后其所有信息将会在回收站中保留，可以对其选择恢复，而彻底删除的菜品将不做保留直接删除

12.对菜品进行编辑修改操作过程中，图片的修改对当前图片与选择更改的图片进行了显示，其中的菜品点击次数以及发布时间为不可修改
