# 【亲测】开源USDT地址生成源码/0U攻击源码/USDT地址匹配源码/监控公链转账地址/TRX尾数模拟转账数据生成/带安装说明

本套程序已经过悟空源码技术人员测试，如需搭建请直接联系客服：[@wukongymw](http://t.me/wukongymw)
**解压密码：timibbs.net**

源码说明

这个代码也是比较简单
原理大概就是百万里面筛选几个 前后大致相同的钱包
一种新型合约 监控公链转账地址 然后在钱包里生成尾数相同的转账数据 如果习惯了复制地址转账的币圈客户很容易中招！有人叫这个0 U攻击。
东西完整，带安装说明。
教程：
终端
btpython
btpip install tronapi
btpip install tronapi
btpip install request
btpip install redis
btpip install pymysql
btpip install base58
然后接下来把全部东西上传到www/wwwroot
导入数据库
然后把网站搭建起来
web指定后台api
新增一个数据库
进入到脚本里面mysqli mysql ，数据库信息改成生成的第二个数据库 ，和Db脚本换成管理后台数据库

测试反馈

测试了一下，不是很会玩。
需要准备两条域名，web/component/common.js 修改第一行为自己的api域名
admin为后台的api，web是后台的管理界面，Python就是生成地址的
过段时间给终身会员免费发一套PHP接口生成地址的程序，虽然效率不是很高，但很方便

截图展示

[![](https://wukongymw.com/wp-content/uploads/2023/07/1689323009-88756b55f62ac95.jpg)](https://wukongymw.com/wp-content/uploads/2023/07/1689323009-88756b55f62ac95.jpg)
[![](https://wukongymw.com/wp-content/uploads/2023/07/1689323009-813858baa920e00.jpg)](https://wukongymw.com/wp-content/uploads/2023/07/1689323009-813858baa920e00.jpg)
[![](https://wukongymw.com/wp-content/uploads/2023/07/1689323009-46868a55094138e.jpg)](https://wukongymw.com/wp-content/uploads/2023/07/1689323009-46868a55094138e.jpg)