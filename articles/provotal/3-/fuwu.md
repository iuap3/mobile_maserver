# 移动应用服务器端管理相关功能

移动应用服务器端管理功能包括设备信息管理、MA日志、MA Package、应用平台服务配置、许可管理和许可显示。

![](/articles/provotal/3-/images/image3.png)

MA Server提供了对移动应用服务器端业务逻辑的支撑。因此，企业部署了某个移动应用的服务器包后，需要管理员使用上述功能进行应用设置，确保移动应用服务器端的业务逻辑正常执行。移动应用的设置内容由移动应用的供应商提供。管理员按照供应商提供的移动应用设置文档使用上述功能完成设置。

## MA日志

MA日志主要包含查询日志、刷新日志、删除日志和导出日志，使管理员能够实时了解各iuap移动应用产品的使用详细情况日志。

![](/articles/provotal/3-/images/image4.png)

MA日志支持查询，点击“查询”按钮，在弹出的查询条件页面，输入要查询的日期段，根据填写的日期段进行精准查询。如下图：

![](/articles/provotal/3-/images/image5.png)

同时MA日志还支持导出日志功能，如果需要导出日志，则点击“导出日志”按钮，在弹出的条件页面，输入导出日志数据截止日期，精准导出日志数据。如下图：

![](/articles/provotal/3-/images/image6.png)

## MA Package

MA Package 对iuap studio 开发的应用包进行导入和管理。如下图：

![](/articles/provotal/3-/images/image7.png)

点击页面的新增按钮在弹出的的界面中点击导入按钮，选择需要装载的应用进行“装载”。

![](/articles/provotal/3-/images/image8.png)

在MA Package 界面能够对应用进行“启用”和“停用”操作。

## 设备信息管理

设备信息管理是对用户使用的移动设备进行注册，登记用户的设备关键信息，并可以控制设备的关闭与启用功能。

![](/articles/provotal/3-/images/image9.png)

点击“新增”按钮进入服务新增页面，输入服务ID、接口、业务类、数据源等信息，然后点击“保存”按钮，保存新增数据。

![](/articles/provotal/3-/images/image10.png)

如果要修改指定设备信息，先勾选指定设备，然后点击“修改”按钮进入修改页。

![](/articles/provotal/3-/images/image11.png)

输入修改设备信息后点击“保存”按钮，完成修改操作。

![](/articles/provotal/3-/images/image12.png)

如果要删除指定服务信息，先勾选该设备，然后点击“删除”按钮，在弹出的确认窗口上，点击“确定”按钮，即可完成设备信息的删除操作。

![](/articles/provotal/3-/images/image13.png)

如果要关闭指定的设备移动业务功能，首先选中设备登记的信息后点击关闭这个设备，这个移动设备就不能再使用移动业务功能。

如果要启用已关闭设备，首先点击启用这个设备，移动设备恢复使用移动业务的功能。

## 应用平台服务配置

【应用平台服务配置】主要支持配置MA Server应用平台与运营平台关联，方便企业用户管理APP应用。应用平台服务配置主要功能有“登录运营平台”、“授权文件导入”、“连接测试”和“保存”。

![](/articles/provotal/3-/images/image14.png)

MA Server应用平台与运营平台关联，首先需要获取从运营平台导出的企业的配置文件，应用平台服务配置提供登录运营平台的快捷方式，如果需要登录运营平台，则直接点击“登录运营平台”按钮。

![](/articles/provotal/3-/images/image15.png)


然后点击“授权文件导入”按钮，将从运营平台导出企业的配置文件导入到应用平台服务配置中。如下图：

![](/articles/provotal/3-/images/image16.png)

接着输入正确的企业管理员账号和密码，连接测试是否配置成功，验证成功后系统会进行标注验证成功，如下图：

![](/articles/provotal/3-/images/image17.png)

当验证成功后，点击“保存”按钮，完成保存应用平台的服务配置。

如果勾选了“启用来自运营平台的MA Server许可”，则后台系统会自动申请并安装授权许可。

## 许可管理

许可管理通过查询APP的唯一标识符，管理其许可方式。其中，运营平台许可表示用友惠商云的计费方式，即按人按月收费；文件许可表示按用户收费。

查询到APP ID后，选择license方式即可，如下图：

![](/articles/provotal/3-/images/image18.png)

选择了一个license方式后，点击“更新”按钮进行保存，如下图：

![](/articles/provotal/3-/images/image19.png)

## 许可占用

许可占用支持文件许可方式。进入页面，即可显示总的许可数和已用许可数。如下图：

![](/articles/provotal/3-/images/image20.png)

选择已经占用的许可进行删除，可以释放占用的许可。

![](/articles/provotal/3-/images/image21.png)

刷新页面后能够正常显示现在的许可占用。




































