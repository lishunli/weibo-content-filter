**【注意】**本文内容仅适用于插件v1.0及以上版本。

出于简洁性和易用性的考虑，“版面模块”中的预设屏蔽模块并未包括所有模块。您可以使用“改造版面”->“自定义CSS”来屏蔽这些模块，或按照您的需求改造微博版面。

本文中列出部分屏蔽模块和版面改造的CSS代码（鸣谢 [@兔子白色的兔子](http://weibo.com/k441)）。需要进行某项改造（屏蔽）时，将对应的CSS代码粘贴进插件“自定义CSS”中即可，每条一行。

如果您要进行的改造（屏蔽）不在本文中，可以自行编写CSS代码。如果您完全不了解 HTML 和 CSS，建议您阅读 [相关教程](http://www.w3school.com.cn/h.asp)。

# 【新版微博】我的首页 #

将左边栏变为双栏（分组较多时便于浮动）
```
.lev { width: 115px; float: left} .lev2 { clear: left } .levdot { width: 20px !important; height: 20px !important } .W_new { margin-top: -18px !important }
```

所有表情
```
img[type="face"] { display: none !important }
```

顶栏底端的红线
```
.WB_global_nav .gn_bg { background: none !important }
```

顶栏“应用”标签
```
.gn_title[node-type="app"] { display: none }
```

顶栏“游戏”标签
```
.gn_title[node-type="game"] { display: none }
```

顶栏“微吧”标签
```
.gn_title[node-type="weiba"] { display: none }
```

顶栏工具栏“会员”图标
```
.gn_setting[node-type="member"] { display: none }
```

微博排序
```
div[node-type="smartSortSelect"] { display: none }
```

分组
```
#pl_leftnav_group { display: none }
```

左边栏“密友圈”
```
.level_1_Box + .level_1_Box { display: none }
```

左边栏“赞”
```
.lev[node-type="guide_like"] { display: none }
```

左边栏“发给我的”
```
.lev > a[href^="/direct/tome"] { display: none }
```

“悄悄关注”分组
```
.lev > a[whisper] { display: none }
```

去掉微博用户头像
```
.WB_feed .WB_face { display : none !important } .WB_feed .WB_detail { margin-left: auto }
```

“赞”图标
```
a[action-type="feed_list_like"], a[action-type="feed_list_like"]+i { display:none }
```

“被不想看到的微博刷屏了？”
```
div[node-type="feed_list_shieldKeyword"] { display:none }
```

# 【新版微博】个人主页 #

隐藏关注动态（也可以通过点击“他/她的主页”下面的“微博”实现）
```
.WB_feed_type[act_id] { display: none }
```

# 【旧版微博】我的首页 #

去掉微博用户头像
```
dd.content { margin: 0 !important } dt.face { display: none !important }
```

“我的微群”标签
```
div.nfTagB_group li[action-type="order_by_weiqun"] { display: none }
```

“热门微博”（“猜你喜欢”）标签
```
div.nfTagB_group li[action-type="order_by_hot"] { display: none }
```

微博排序
```
div.interOder { display: none }
```

工具栏：“广场”标签
```
div.header li[node-type="plaza"] { display: none }
```

工具栏：“微吧”标签
```
div.header li[node-type="group"] { display: none }
```

工具栏：“应用”标签
```
div.header li[node-type="app"] { display: none }
```

工具栏：“游戏”标签
```
div.header li[node-type="game"] { display: none }
```

# 【旧版微博】其他用户（非企业用户）的主页 #

个人照片
```
#pl_content_album { display: none }
```

右边栏：新浪认证信息（个人/机构认证，微博达人等）
```
div.W_sina_vip { display: none }
```

右边栏：关注他/她的人同时关注了
```
#pl_relation_recommendAttUsers { display: none }
```

右边栏：这些人也关注他/她
```
#pl_content_chainFollowers, #pl_leftNav_chainFollowers { display: none }
```

右边栏：我和他/她都关注了
```
#pl_content_sameFriends { display: none }
```

右边栏：个人资料
```
#pl_content_userInfo { display: none }
```

右边栏：他/她的公开分组
```
#pl_content_publcigroup { display: none }
```
_（是的，你没看错！可不是publicgroup，这是新浪的错字XD）_

右边栏：他/她的标签
```
#pl_content_hisTags { display: none }
```

右边栏：他/她的微群
```
#pl_common_thirdmodule_1003 { display: none }
```

右边栏：关注的话题
```
#pl_content_topic { display: none }
```

右边栏：他/她的粉丝
```
#pl_content_hisFans { display: none }
```

右边栏：新浪微博意见反馈
```
#pl_common_feedback { display: none }
```

右边栏（体验版）：他/她的关注
```
#pl_relation_hisFollowingsNav { display: none }
```