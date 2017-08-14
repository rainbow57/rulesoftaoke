## 《淘宝客软件工具权限管理规范》

2017-07-28

各位亲爱的淘宝客软件工具开发者：

为了规范淘宝客软件工具市场环境，通过把API权限分级对应不同的软件工具能力，确保为淘宝客筛选出优质的软件工具。目前阿里妈妈主要提供了初级API和高级API服务， 现公布淘宝客软件工具权限管理规范。

一、淘宝客软件工具API权限包说明：

| **API包名称** | **API分类** | **权限包** | **API说明（附API地址）** | **开发进度** | **权限等级** | **分值要求** |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 淘宝客-工具-上行门槛包 | 备案及黑名单 | 淘宝客推广保护 | 作为淘宝客在官方推广备案补充以及申诉材料 | 完成 | 初级 | 必接 |
| 淘宝客-工具-登陆包 | 登陆 | 登录授权功能 | [淘宝客授权工具登录账号](http://open.taobao.com/docs/doc.htm?docType=1&articleId=102635&treeId=1) | 完成 | 初级 | / |
| 淘宝客-工具-单品券转链包 |  | 其他转链 | 单品券二合一转链 | 完成 | 初级 | / |
|  |  |  | [2合1长链接转s.click短链接](http://open.taobao.com/docs/api.htm?spm=a219a.7395905.0.0.K3nbGj&scopeId=11655&apiId=27832) | 完成 | 初级 | / |
| 淘宝客-工具-物料基础包 | 查优惠券 | 优惠券排行榜  （日常推广库） | [单品券热销TOP10000榜（单品维度）](http://open.taobao.com/docs/api.htm?apiId=28110) | 完成 | 初级 | / |
|  |  |  | [单品券热销TOP100（关键词查询、类目查询）](http://open.taobao.com/docs/api.htm?apiId=28110) | 完成 | 初级 | / |
|  | 淘宝客-工具-物料高级包 | 好券直播；品牌券 | [通过类目查券](http://open.taobao.com/doc2/apiList.htm?scopeId=12331) | 完成 | 高级 | 70分 |
| 淘宝客-工具-推广位 | 推广位 | 推广位获取和生成 | 推广位获取和生成 | 敬请期待 | 高级 | 70分 |
| 淘宝客-工具-佣金计划包 | 佣金计划 | 获取最高佣金 | 包含查询和申请最高佣金计划 | 完成 | 高级 | 80分或达到成长体系准入规则 |
| 淘宝客-工具-淘宝客淘口令 | 淘口令 | 高额免费生成淘口令 | 敬请期待 | 敬请期待 | 高级 | 单项合作能力45分 |


二、淘宝客软件工具权限开放规则：

淘宝客软件工具权限为邀请制，暂未全面开放，除阿里妈妈另有明确要求外，需要满足以下条件：

（一）淘宝客软件工具初级API权限

1、注册成为阿里妈妈会员，并绑定符合阿里妈妈要求的支付宝账户。

2、淘宝客软件工具开发者有义务配合向阿里妈妈提供所需要的相关信息，或推广官方系统输出的物料等。

3、目前禁止开发、使用、推广第三方无线淘宝客软件工具。

4、阿里妈妈账户内生效中的累计扣分不得大于等于18分。

（二）淘宝客软件工具高级API权限

除需要符合淘宝客软件工具初级API权限的准入要求之外，还需满足API对应分值要求：

1、 淘宝客工具分数表详情。

<div>
	<table cellspacing="0" cellpadding="0" border="0">
		<tbody>
			<tr>
				<td colspan="15" style="border-color:windowtext; height:16.5pt">
				<p style="text-align:center"><span>淘宝客工具分数表</span></p>
				</td>
			</tr>
			<tr>
				<td rowspan="2" style="height:16.5pt">
				<p style="text-align:center"><span>分类及权重</span></p>
				</td>
				<td rowspan="2" style="height:16.5pt">
				<p style="text-align:center"><span>名称</span></p>
				</td>
				<td rowspan="2" style="height:16.5pt">
				<p style="text-align:center"><span>考核描述</span></p>
				</td>
				<td rowspan="2" style="height:16.5pt">
				<p style="text-align:center"><span>分值</span></p>
				</td>
				<td colspan="11" style="height:16.5pt">
				<p style="text-align:center"><span>比例</span></p>
				</td>
			</tr>
			<tr>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>100%</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>90%</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>80%</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>70%</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>60%</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>50%</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>40%</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>30%</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>20%</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>10%</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>0%</span></p>
				</td>
			</tr>
			<tr>
				<td rowspan="5" style="height:16.5pt">
				<p style="text-align:center"><span>销货能力<br>
				<span>40</span>分</span></p>
				</td>
				<td rowspan="3" style="height:16.5pt">
				<p style="text-align:center"><span>流量<br>
				<span>30</span>分</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>使用工具且有推广点击的淘宝客数量（<span>PUB_ID</span>）</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>5</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>10000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>8000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>6000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>3000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>1000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>500</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>250</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>50</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>25</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>10</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>&lt;10</span></p>
				</td>
			</tr>
			<tr>
				<td style="height:16.5pt">
				<p><span>淘宝客点击数合计</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>10</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>1400000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>1120000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>840000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>420000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>140000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>70000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>35000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>7000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>3500</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>1400</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>&lt;1400</span></p>
				</td>
			</tr>
			<tr>
				<td style="height:16.5pt">
				<p><span>淘宝客推广<span>UV</span>数合计</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>15</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>500000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>400000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>300000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>150000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>50000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>25000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>12500</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>2500</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>1250</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>500</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>&lt;500</span></p>
				</td>
			</tr>
			<tr>
				<td rowspan="2" style="height:16.5pt">
				<p style="text-align:center"><span>成交<br>
				<span>10</span>分</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>alipay</span><span>笔数</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>5</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>180000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>144000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>108000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>54000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>18000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>9000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>4500</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>900</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>450</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>180</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>&lt;180</span></p>
				</td>
			</tr>
			<tr>
				<td style="height:16.5pt">
				<p><span>alipay</span><span>金额</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>5</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>4500000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>3600000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>2700000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>1350000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>450000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>225000</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>112500</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>22500</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>11250</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>4500</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>&lt;4500</span></p>
				</td>
			</tr>
			<tr>
				<td rowspan="6" style="height:16.5pt">
				<p style="text-align:center"><span>合作能力<br>
				<span>60</span>分</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>官方通知下行<br>
				<span>5</span>分</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>淘宝客通知信息触达</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>5</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>100%</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>　</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>　</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>　</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>　</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>　</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>　</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>　</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>　</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>　</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>&lt;100%</span></p>
				</td>
			</tr>
			<tr>
				<td rowspan="5" style="height:16.5pt">
				<p style="text-align:center"><span>合作物料下行<br>
				<span>55</span>分<br>
				（合作物料指：优惠券排行榜、实时爆款；好券直播、品牌券等物料<span>API</span>）</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>参与合作物料推广淘宝客数以及占工具整体淘宝客数比例</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>5</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>90%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>80%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>70%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>60%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>50%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>40%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>30%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>20%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>10%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>&gt;0</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>=0</span></p>
				</td>
			</tr>
			<tr>
				<td style="height:16.5pt">
				<p><span>推广合作物料商品数以及占工具整体推广商品数比例</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>5</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>90%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>80%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>70%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>60%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>50%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>40%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>30%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>20%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>10%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>&gt;0</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>=0</span></p>
				</td>
			</tr>
			<tr>
				<td style="height:16.5pt">
				<p><span>推广合作物料淘宝客点击数以及占工具整体淘宝客点击数比例</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>15</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>90%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>80%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>70%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>60%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>50%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>40%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>30%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>20%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>10%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>&gt;0</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>=0</span></p>
				</td>
			</tr>
			<tr>
				<td style="height:16.5pt">
				<p><span>推广合作物料<span>alipay</span>笔数以及占工具整体推广<span>alipay</span>笔数比例</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>15</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>90%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>80%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>70%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>60%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>50%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>40%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>30%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>20%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>10%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>&gt;0</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>=0</span></p>
				</td>
			</tr>
			<tr>
				<td style="height:16.5pt">
				<p><span>推广合作物料<span>alipay</span>金额以及占工具整体推广<span>alipay</span>金额比例</span></p>
				</td>
				<td style="height:16.5pt">
				<p style="text-align:center"><span>15</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>90%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>80%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>70%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>60%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>50%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>40%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>30%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>20%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>≥<span>10%</span></span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>&gt;0</span></p>
				</td>
				<td style="height:16.5pt">
				<p><span>=0</span></p>
				</td>
			</tr>
		</tbody>
	</table>
</div>

具体以阿里妈妈统计为准。

2、 淘宝客软件工具高级API权限（淘宝客-工具-佣金计划包）有两种获取途径：

1）工具分值达到80分进入发展体系获取长期权限。

2）通过工具成长体系获取临时权限（有时效性）。

3、成长体系获取的高级API权限（淘宝客-工具-佣金计划包）规则：[**解读**](http://rule.alimama.com/?spm=a2320.7388781.a214tr8.21.69ad0d21wrEeIT#%21/announce/business/detail?id=8307063&knowledgeid=20495054)

<div>
	<table style="width:340.95pt" cellspacing="0" cellpadding="0" border="0">
	<tbody>
		<tr>
			<td colspan="6" style="border-color:windowtext; height:16.5pt; width:340.95pt">
			<p style="text-align:center"><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span><span>成长期</span></p>
			</td>
		</tr>
		<tr>
			<td style="height:16.5pt; width:98.9pt">
			<p style="text-align:center"><span>工具分值段</span></p>
			</td>
			<td style="height:16.5pt; width:46.05pt">
			<p style="text-align:center"><span>60~65</span></p>
			</td>
			<td style="height:16.5pt; width:46.05pt">
			<p style="text-align:center"><span>65~70</span></p>
			</td>
			<td style="height:16.5pt; width:46.05pt">
			<p style="text-align:center"><span>70~75</span></p>
			</td>
			<td style="height:16.5pt; width:46.05pt">
			<p style="text-align:center"><span>75~80</span></p>
			</td>
			<td style="height:16.5pt; width:57.85pt">
			<p style="text-align:center"><span>合计</span></p>
			</td>
		</tr>
		<tr>
			<td style="height:16.5pt; width:98.9pt">
			<p style="text-align:center"><span>权限期限（天）</span></p>
			</td>
			<td style="height:16.5pt; width:46.05pt">
			<p style="text-align:center"><span>30</span></p>
			</td>
			<td style="height:16.5pt; width:46.05pt">
			<p style="text-align:center"><span>45</span></p>
			</td>
			<td style="height:16.5pt; width:46.05pt">
			<p style="text-align:center"><span>60</span></p>
			</td>
			<td style="height:16.5pt; width:46.05pt">
			<p style="text-align:center"><span>75</span></p>
			</td>
			<td style="height:16.5pt; width:57.85pt">
			<p style="text-align:center"><span>210</span><span>天</span></p>
			</td>
		</tr>
	</tbody>
	</table>
</div>

4、成长体系获取的高级API权限（淘宝客-工具-佣金计划包）清出规则：

1） 在有效期内未达到晋级分数要求；

2） 未对淘宝客工具团队下所有工具进行最新源码备案；

3） 源码备案工具与市场上工具使用不同源码，即AB工具；

4） 不参与阿里妈妈官方营销推广活动或其他合作配合。

三、获得淘宝客软件工具推广权限的淘宝客，在推广期间，需同时符合如下：

1、遵守《淘宝平台服务协议》、[《阿里妈妈推广者规范》](http://rule.alimama.com/?spm=a2320.7388781.a214tr8.22.0gMeF7#%21/announce/business/detail?id=8307063&knowledgeid=5704248)和《淘宝客软件工具合作规范》。

2、符合准入要求。

若未达到上述任一要求，或软件工具推广使用过程中有任何淘宝客违规行为的，阿里妈妈将同时按如下方式进行处理：

1、未达到准入要求或违反《淘宝客软件工具合作规范》和《阿里妈妈推广者规范》的规范，将关闭使用淘宝客软件工具权限使用功能。

2、关闭权限后2个月内不再接受申请或不予重新开通；也不得通过变更开发代码，在权限关闭后2个月内重复申请权限。

3、同时违规其他规范的，将按相应规范规定给予处理。



**FAQ**

1、淘宝客软件工具高级API权限应该如何申请：

答：1）完成源代码托管备案。第三方淘宝客工具通过阿里云代码托管服务授权给官方账号进行源码审核

操作说明文档详见：http://rule.alimama.com/?spm=a2320.7388781.a214tr8.21.69ad0d21wrEeIT\#!/announce/business/detail?id=8307063&knowledgeid=20495060

2）3个工作日进行安全审核并邮件反馈结果。

3）审核通过后每周四开通权限。

4）有效期截止前3个工作日进行升段分值复盘。

2、这个规则主要影响对象是谁？

答：主要是针对淘宝客软件工具商。



3、怎样通过成长体系获取高级权限？怎样申请？多久可以审核通过？

答：您是一个淘宝客软件工具商，且符合以下情况：  
 1）非插件  
 2）非无线端工具  
 3）非网页工具  
 4）已开发完成并在线运行，  
 如符合以上情况，按照以下步骤操作：  
 1、填写淘宝客工具基础备案表格并邮件至 zeao.lj@taobao.com ，5个工作日后关注下审核结果，邮件回复。  
 2、通过后完成源代码托管备案（参考第三方淘宝客工具通过阿里云代码托管服务授权给官方账号进行源码审核操作说明文档.docx）  
 3、完成淘宝客-工具-上行门槛包接入。  
 每周四审核并开权限。



4、我在哪里可以看到工具分值？

答：目前无法直接查看到分值，您可以通过软件工具后台的数据可做为参考，按淘宝客工具分数表分值进行计算预估，如有疑问可旺旺联系“泽奥”



5、淘宝客工具分数表多久统计一次？

答：每月统计一次，每月月结日。



6、如在使用权限期间不符合要求是否会收回权限？权限被关闭后是否会影响到之前权限获取的数据推广。

答：会收回权限，不影响 。



7、关闭权限后多久可以重新申请？

答：2个月后，即3月8日被收回权限后，需6月1日后才可重新申请。



8、目前禁止开发、使用、推广第三方无线淘宝客软件工具？后面有计划么？

答：目前是不可以的，后续会考虑与优质淘宝客工具团队进行无线端合作，请大家关注阿里妈妈的公告通知。



