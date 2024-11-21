---
icon: water
---

# 日志-钱包流水



<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
<mark style="color:orange;">查看时时的动态钱包改变日志,会详细记录用户的投入产出,以及当前状态有以下几个状态分别说明,该日志默认是全平台的可以通过筛选去精准寻找某个游戏的或者某个能过户的或者某个订单,也可以根据3个参数联合查询更精确的结果. 用户Hash获取可以参考</mark> [**用户管理**](yong-hu-guan-li.md)
{% endhint %}

## 状态说明

|                    状态                    |            说明            |
| :--------------------------------------: | :----------------------: |
| <mark style="color:green;">同步钱包成功</mark> |  说明回调地址调用成功已经通知了代理商的服务器  |
|  <mark style="color:red;">同步钱包失败</mark>  | 说明回调地址4次调用失败,需要检查回调服务器接口 |
|    <mark style="color:blue;">成功</mark>   |    暂未调用回调地址,这种情况会很少出现    |
