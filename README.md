1.	安装VMOS虚拟机，创建一个root的虚拟机andoid 7.0【进入虚拟机桌面->设置->打开超级用户和Xposed，重启虚拟机】
2.	手机安装支付宝和HttpCanary ，虚拟机Andoid 7.0导入这两个APP【虚拟机桌面添加->导入HttpCanary和 支付宝app】
3.	使用虚拟机中HttpCanary APP，安装HttpCanary根证书至虚拟机系统（Root）【虚拟机桌面HttpCanary设置->HttpCanary根证书>点击里面红色字体，弹出安装根证书，设置PIN码并完成验证安装； 按返回再次点击HttpCanary根证书>添加根证书至系统（Root），点移动按钮-选择永久记住选择-点允许。退出或卸载虚拟机中的HttpCanary APP】
4.	手机启动HttpCanary，安装根证书，设置抓包目标为VMOS ，
5.	虚拟机Andoid 7.0中登录支付宝
6.	手机HttpCanary启动抓包，虚拟机中支付宝进入全民消防学习小程序，点击学习一篇消防新闻
7.	手机HttpCanary 停止抓包，并搜索抓包结果，关键字为Authorization，找到域名中有119的条目，在请求标签页下，点击Authorization的字段，复制后粘贴到刷积分软件Authorization框中，点击增加配置，点击做下角开始执行按钮，每天170分

