Introduction
============
中国各省/自治区/直辖市、市/自治州/盟/地区、区/县/县级市/旗数据，

包含名称、拼音、拼音首字母、行政代码、区号等数据。


版本说明
============
本数据使用 MySQL 处理，现导出 SQL（基本兼容各主流关系型数据库） 和 CSV 两种数据格式，

以备在使用不同的数据库（包括关系型数据库和非关系数据库）时能正确导入。

|  字段名称  | 字段说明  |
|  -------  | -------  |
| id     | 主键 ID，自增   |
| name     | 行政区划名称   |
| parent_id     | 上级行政区划 ID   |
| initial     | 行政区划名称首拼音字母   |
| initials     | 行政区划名称各个字拼音首字母   |
| pinyin     | 行政区划名称拼音   |
| extra     | 附加信息，如：壮族、蒙古族   |
| suffix     | 行政区类别   |
| code     | 行政区划行政代码   |
| area_code     | 区号   |
| order     | 排序，按行政区划代码从小到大排序   |


特别说明
============
* 最新调整的行政区域，行政代码或区号可能不完善，但不影响常规情况使用
* 由于对台湾行政区划代码来源于通义千问，非官方数据
* CHANGES 中的更新语句，仅适用于未调整过表结构、未增加过数据的情况

数据来源
============
* 中华人民共和国民政部-全国行政区划信息查询平台（ http://xzqh.mca.gov.cn/map ）
* 澳门特别行政区 地图绘制暨地籍局（ https://www.dscc.gov.mo/zh-hans/geographical_location.html ）
* 通义千问（ https://tongyi.aliyun.com/ ）
* 行政区划（ http://www.xzqh.org/ ）
* 中华人民共和国国家统计局《最新县及县以上行政区划代码》（截止2012年10月31日）（ http://www.stats.gov.cn/tjbz/xzqhdm/t20130118_402867249.htm ）
* 中华人民共和国民政部2018年行政区划代码（ http://www.mca.gov.cn/article/sj/xzqh/2018/ ）
* 百度百科（ http://baike.baidu.com/ ）
* 民政部2019年7月中华人民共和国县以上行政区划代码（ http://www.mca.gov.cn/article/sj/xzqh/2019/201908/201908271607.html ）
* 民政部2020年2月中华人民共和国县以上行政区划代码（ http://www.mca.gov.cn/article/sj/xzqh/2020/2020/202003301019.html ）
* 中华人民共和国二〇一六年县级以上行政区划变更情况（ http://xzqh.mca.gov.cn/description?dcpid=2016 ）
* 中华人民共和国二〇一七年县级以上行政区划变更情况（ http://xzqh.mca.gov.cn/description?dcpid=2017 ）
* 中华人民共和国二〇一八年县级以上行政区划变更情况（ http://xzqh.mca.gov.cn/description?dcpid=2018 ）
* 中华人民共和国二〇一九年县级以上行政区划变更情况（ http://xzqh.mca.gov.cn/description?dcpid=2019 ）

错误反馈
============
如果您在使用过程中，发现数据有误、遗漏，或已撤销的行政区域但是本数据库中还存在，请联系本人更新。
* 联系人：腾 勇
* E-mail：webmaster@buession.com
* QQ：251329041

打赏
============
在整理、核对全国（含港澳台）行政区划数据，以及随着时间的推移行政区划发生变更的数据更新，需要耗费大量时间和精力。如果，您觉得该数据对您有所帮助帮助，您的一次打赏，是推动我更新数据的最大动力，一分也是爱❤️


<img src="./alipay-qrcode.jpg" width="50%" />
<img src="./wechat-qrcode.png" width="50%" />