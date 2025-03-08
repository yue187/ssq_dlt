ssq 双色球开奖历史记录
dlt 大乐透开奖历史记录
qlc 七乐彩开奖历史记录
===============
## 接口地址
* https://www.xietian.xyz/api/fcapi/list&token=tokences&type=dlt&page=1&limit=1
* 请求方式 POST GET 都可以
* 请勿频繁请求
* 测试token 每天100次，每次返回一条数据 limit不可更改 每天次数限制先到先得

## 接口参数说明
* token 必填 string  申请的token 或者测试使用
* type  必填 string  彩票分类 dlt  ssq  qlc
* page  必填 int     页码
* limit 选填 int     每页数量 为空则默认

## 返回数据结构
{
"Code": 200,
"Msg": "success",
"data": {
"list": [
{
"lottery_no": "24140",
"lottery_id": "dlt",
"lottery_res": "03,06,15,23,31,01,12",
"lottery_date": "2024-12-02 00:00:00",
"lottery_exdate": "2025-02-01 00:00:00",
"lottery_sale_amount": "",
"lottery_pool_amount": ""
}
],
"total": 2651,
"total_page": 2651,
"page": 1
}
}

## 返回数据说明
* Code 200 状态码 成功
* Msg 说明
* data 数据包
* data total 总数
* data page 当前页码
* data total_page 总页码
* data list lottery_no 期号
* data list lottery_id 分类id
* data list lottery_res 开奖号码
* data list lottery_date 开奖日期
* data list lottery_exdate 兑奖截止日期
* data list lottery_sale_amount 本期销售额（可能为空）
* data list lottery_pool_amount 奖池滚存（可能为空）
*

## 接口升级
* 现在有三种方式
* 测试token 每天 50次 每次10条数据
* 续费token 每天 1000次 每次100条数据(可定制)
* 永久token 无限制 每次返回1000条数据(可定制)

## 出售数据包
* 数据包截止日期为最新一期
* 数据包打包发送

## 联系方式 备注 数据
* v Yueye9404101226
* qq 1204723220
* email 1204723220@qq.com
* 

## 后期将推送更多相关接口
## 多谢关注 Star
## 感谢分享

## 收集整理不易！感谢您的支持和赞赏
![Image text](https://www.xietian.xyz/uploads/pay/www.jpg)
![Image text](https://www.xietian.xyz/uploads/pay/zzz.jpg)
