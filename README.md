# douyin-assistant
抖音获客助手

【独家首发】抖音获客神器，你的业务增长新引擎!&

 亲爱的抖音用户们，你们好!想要快速提升业务，增加潜在客户数量吗?现在，我们有一款专为抖音用户打造的获客神器--抖音获客助手系统，即将改变你的营销方式!
 
 抖音获客助手系统亮点:
 
1.安全部署:本地Windows部署，config.ini配置文件，确保你的信息安全无虞

2.私信智能提取:轻松获取私信中的手机号码、微信号及聊天记录，一键导出为CSV文件。

3.AI智能回复:借助清华智谱AI知识库，自动为你回复私信，展现你的专业与贴心。

4.数据对接:支持Java、PHP、JS代码对接，使用sha256加密的MySQL数据库，保障数据安全。5.实时通知:对接企业微信机器人，微信里实时接收新客户线索，商机不再错过。6.自定义模型:用户可注册清华智谱AI账户，按需支付模型费用，打造专属你的智能客服7.灵活部署:支持VM虚拟机部署和本地部署，让你选择最适合自己的方式。

节 限时优惠:关注抖音号2221281879，发送私信“我需要抖音获客助手”，即可获得软件下载地址和license key。只需简单填写，即可轻松上手，开启你的获客新篇章!

为什么选择我们?

高效:智能提取、自动回复，让你的营销更高效。

安全:本地部署、加密数据库，保障你的信息安全

智能:借助AI知识库，让你的回复更专业、更贴心。

便捷:支持多种代码对接，满足你的不同需求。章
赶快行动吧!让抖音获客助手系统成为你业务增长的新引擎，助你轻松实现客户增长和业务拓展!

windows10 中 安装 mysql 火狐浏览器

config.ini 文件配置说明

[host]

api_sit_url=https://api.bin.com    #暂时不用     实际使用请删除注释

api_uat_url=https://api.bin.com   #暂时不用


[mysql]

host=127.0.0.1    #mysql ip

port=3306

user=              # 用户

password=          #密码

dbname=            #数据库名称



[redis]

host=127.0.0.1

port=6379

password=88888        #暂时不用

db=0



[zhipu]
api_key=              #清华智谱ai的key https://open.bigmodel.cn/login?redirect=%2Fknowledge

knowledge_id=         #知识库id

contents=将有工作人员联系您！  #如果私信里有手机号码 或微信号 时的回复内容

autoreply=True


[dysk]

appkey=asddfggggg      #私信抖音号 2221281879 免费获取key

douyinhao=             # 你的抖音号


[mywebsite]

url=                   #你自己系统的接口地址   没有可以为空



[qywx]

Webhook=            #企业qq的机器人地址

mentioned_list="wangqing","@all"

mentioned_mobile_list="13800001111","@all"

mentioned_content=有新客户，请尽快联系     #提示语



[dy]

dyfocus=抖音获客系统       #暂时不用

dyfocuscount=100

