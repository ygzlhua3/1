# 1

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>接口说明</title>
</head>
<body>
<p> api接口仅供提供数据，可以直接在苹果CMS后台联盟采集中加入-并提供给他人采集。</p>
<p>联盟资源分配唯一标识ID，用来区别绑定分类，这个ID一般由苹果CMS官方提供，不可随意修改设置，否则造成入库分类错乱。</p>
<p>1,视频列表地址https://api.jisubt.com/videos?ac=list<br>
  2,视频详情地址https://api.jisubt.com/videos?ac=detail<br>
</p>


<p>列表接收参数：<br>
  ac=list<br>
  t=类别ID<br>
  pg=页码<br>
  wd=搜索关键字<br>
  h=几小时内的数据<br>
  例如：https://api.jisubt.com/videos?ac=list&amp;t=1&amp;pg=5   分类ID为1的列表数据第5页<br>
</p>

<p>内容接收参数：<br>
  参数 ids=数据ID，多个ID逗号分割。<br>
  t=类型ID<br>
  pg=页码<br>
  h=几小时内的数据</p>
<p>例如:   https://api.jisubt.com/videos?ac=detail&amp;ids=123,567     获取ID为123和567的数据信息<br>
  https://api.jisubt.com/videos?ac=detail&amp;h=24     获取24小时内更新数据信息</p>
<p></p>

</body>
</html>
