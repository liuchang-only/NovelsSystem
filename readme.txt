json数据请求 code==-1,服务错误，code==0,重名，code==1,成功返回

技术栈，element+vue+mongo+node(express)

serve启动。nodemon（自动更新） node index(不跟新）
vue启动。npm run  serve


数据库为NS（NovelSystem）。管理员需要插入后进入密码判断
use NS
db.admin.insert({"admin" : "admin", "pw" : "admin"})
即用户名、密码都是admin。
先操作后台插入小说信息再看前台功能


新增小说章节功能，到笔趣阁copy小说章节，其他网站的格式不晓得能不能通用。

主页排行榜数据显示不出来，是数据跟新后多余。
打开MongoDB，执行
use NS

