## ONE页面涉及到的接口

#### 1.获取近十天图文集合ID的数组

GET：/api/onelist/idlist/

示例：http://v3.wufazhuce.com:8000/api/onelist/idlist

返回示例：

```
{
    "res": 0, 
    "data": [
        "4785", 
        "4783", 
        "4780", 
        "4782", 
        "4765", 
        "4781", 
        "4779", 
        "4778", 
        "4775", 
        "4774"
    ]
}
Tips：第一项即为今天的图文集合数组的ID
```
#### 2.获取当天的图文集合信息以及当地天气信息
 
 GET：/api/channel/one/0/{location}
 
 示例：http://v3.wufazhuce.com:8000/api/channel/one/0/上海
 
 返回示例：
 
```
{
    "res": 0, 
    "data": {
        "id": "4785", 
        "weather": {
            "city_name": "上海", 
            "date": "2018-05-28", 
            "temperature": "22", 
            "humidity": "89%", 
            "climate": "阴", 
            "wind_direction": [ ], 
            "hurricane": "西南风", 
            "icons": {
                "day": "weather_icon_overcast", 
                "night": "weather_icon_overcast_night"
            }
        }, 
        "date": "2018-05-28 06:00:00", 
        "content_list": [
            {
                "id": "15406", 
                "category": "0", 
                "display_category": "4", 
                "item_id": "2090", 
                "title": "摄影", 
                "forward": "有时候，一个人善意的动念或者微不足道的一句话，就可以改变另一个人，但所有人都专注自己得到什么，吝啬给予，抱着所有善意不松手，所以他们一辈子都得不到自己想要的。", 
                "img_url": "http://image.wufazhuce.com/FpM8s5kk5nPtNsai4VRwcuUtXyuf", 
                "like_count": 4187, 
                "post_date": "2018-05-28 06:00:00", 
                "last_update_date": "2018-05-25 14:15:33", 
                "author": { }, 
                "video_url": "", 
                "audio_url": "", 
                "audio_platform": 2, 
                "start_video": "", 
                "has_reading": 0, 
                "volume": "VOL.2060", 
                "pic_info": "Felix Russell Saw", 
                "words_info": "《听你的》", 
                "subtitle": "", 
                "number": 0, 
                "serial_id": 0, 
                "serial_list": [ ], 
                "movie_story_id": 0, 
                "ad_id": 0, 
                "ad_type": 0, 
                "ad_pvurl": "", 
                "ad_linkurl": "", 
                "ad_makettime": "", 
                "ad_closetime": "", 
                "ad_share_cnt": "", 
                "ad_pvurl_vendor": "", 
                "content_id": "2090", 
                "content_type": "0", 
                "content_bgcolor": "#FFFFFF", 
                "share_url": "http://m.wufazhuce.com/one/2090", 
                "share_info": {
                    "url": "http://m.wufazhuce.com/one/2090", 
                    "image": "http://image.wufazhuce.com/FpM8s5kk5nPtNsai4VRwcuUtXyuf", 
                    "title": "VOL.2060", 
                    "content": "有时候，一个人善意的动念或者微不足道的一句话，就可以改变另一个人，但所有人都专注自己得到什么，吝啬给予，抱着所有善意不松手，所以他们一辈子都得不到自己想要的。 from 《听你的》"
                }, 
                "share_list": {
                    "wx": {
                        "title": "", 
                        "desc": "", 
                        "link": "http://m.wufazhuce.com/one/2090?channel=singlemessage", 
                        "imgUrl": "", 
                        "audio": ""
                    }, 
                    "wx_timeline": {
                        "title": "", 
                        "desc": "", 
                        "link": "http://m.wufazhuce.com/one/2090?channel=timeline", 
                        "imgUrl": "", 
                        "audio": ""
                    }, 
                    "weibo": {
                        "title": "ONE一个 有时候，一个人善意的动念或者微不足道的一句话，就可以改变另一个人，但所有人都专注自己得到什么，吝啬给予，抱着所有善意不松手，所以他们一辈子都得不到自己想要的。 from 《听你的》——《听你的》 下载ONE一个APP:http://weibo.com/p/100404157874", 
                        "desc": "", 
                        "link": "http://m.wufazhuce.com/one/2090?channel=weibo", 
                        "imgUrl": "", 
                        "audio": ""
                    }, 
                    "qq": {
                        "title": "", 
                        "desc": "", 
                        "link": "http://m.wufazhuce.com/one/2090?channel=qq", 
                        "imgUrl": "", 
                        "audio": ""
                    }
                }, 
                "tag_list": [ ]
            }, 
            {
                "id": "15419", 
                "category": "1", 
                "display_category": "1", 
                "item_id": "3276", 
                "title": "氯", 
                "forward": "想要得到什么，想要亲近什么，都像是羞耻，是一种罪过吗？", 
                "img_url": "http://image.wufazhuce.com/FgoyW02XLB0xbGyyDu-xkwH1yTSB", 
                "like_count": 332, 
                "post_date": "2018-05-28 06:00:00", 
                "last_update_date": "2018-05-28 11:07:22", 
                "author": {
                    "user_id": "6826634", 
                    "user_name": "一君", 
                    "desc": "半驯之马。", 
                    "wb_name": "@一君_妄想少女", 
                    "is_settled": "0", 
                    "settled_type": "0", 
                    "summary": "半驯之马。", 
                    "fans_total": "151", 
                    "web_url": "http://image.wufazhuce.com/FgbEXYuUU8VfYjLJbjzxjlavlVVu"
                }, 
                "video_url": "", 
                "audio_url": "", 
                "audio_platform": 2, 
                "start_video": "", 
                "has_reading": 1, 
                "volume": 0, 
                "pic_info": "", 
                "words_info": "", 
                "subtitle": "", 
                "number": 0, 
                "serial_id": 0, 
                "serial_list": [ ], 
                "movie_story_id": 0, 
                "ad_id": 0, 
                "ad_type": 0, 
                "ad_pvurl": "", 
                "ad_linkurl": "", 
                "ad_makettime": "", 
                "ad_closetime": "", 
                "ad_share_cnt": "", 
                "ad_pvurl_vendor": "", 
                "content_id": "3276", 
                "content_type": "1", 
                "content_bgcolor": "#FFFFFF", 
                "share_url": "http://m.wufazhuce.com/article/3276", 
                "share_info": {
                    "url": "http://m.wufazhuce.com/article/3276", 
                    "image": "http://image.wufazhuce.com/FgoyW02XLB0xbGyyDu-xkwH1yTSB", 
                    "title": "氯 作者/一君", 
                    "content": "想要得到什么，想要亲近什么，都像是羞耻，是一种罪过吗？"
                }, 
                "share_list": {
                    "wx": {
                        "title": "ONE STORY | 氯", 
                        "desc": "文/一君 想要得到什么，想要亲近什么，都像是羞耻，是一种罪过吗？", 
                        "link": "http://m.wufazhuce.com/article/3276?channel=singlemessage", 
                        "imgUrl": "http://image.wufazhuce.com/ONE_logo_120_square.png", 
                        "audio": ""
                    }, 
                    "wx_timeline": {
                        "title": "ONE STORY | 氯", 
                        "desc": "文/一君 想要得到什么，想要亲近什么，都像是羞耻，是一种罪过吗？", 
                        "link": "http://m.wufazhuce.com/article/3276?channel=timeline", 
                        "imgUrl": "http://image.wufazhuce.com/ONE_logo_120_square.png", 
                        "audio": ""
                    }, 
                    "weibo": {
                        "title": "ONE一个《ONE STORY | 氯》 文/一君： 想要得到什么，想要亲近什么，都像是羞耻，是一种罪过吗？ 阅读全文：http://m.wufazhuce.com/article/3276?channel=weibo 下载ONE一个APP:http://weibo.com/p/100404157874", 
                        "desc": "", 
                        "link": "http://m.wufazhuce.com/article/3276?channel=weibo", 
                        "imgUrl": "", 
                        "audio": ""
                    }, 
                    "qq": {
                        "title": "氯", 
                        "desc": "想要得到什么，想要亲近什么，都像是羞耻，是一种罪过吗？", 
                        "link": "http://m.wufazhuce.com/article/3276?channel=qq", 
                        "imgUrl": "http://image.wufazhuce.com/ONE_logo_120_square.png", 
                        "audio": ""
                    }
                }, 
                "tag_list": [
                    {
                        "id": "7", 
                        "title": "ONE STORY"
                    }
                ]
            }, 
            {
                "id": "15417", 
                "category": "3", 
                "display_category": "1", 
                "item_id": "2111", 
                "title": "为什么越来越优秀的我，却越来越难找到男朋友？", 
                "forward": "两个人交往，不需要证明自己多优秀，只需要不以“爱”为借口占对方便宜就行了。", 
                "img_url": "http://image.wufazhuce.com/FiWiDYn2mj9NN-LGsdWdgEFN0KjM", 
                "like_count": 1228, 
                "post_date": "2018-05-28 06:00:00", 
                "last_update_date": "2018-05-27 14:55:30", 
                "author": {
                    "user_id": "7521733", 
                    "user_name": "菠菜 答 Waiway", 
                    "desc": "菠菜，情感问题作者，著有《你不必讨全世界的欢心》。公众号：有点自卑", 
                    "wb_name": "", 
                    "is_settled": "0", 
                    "settled_type": "0", 
                    "summary": "情感问题作者。公众号：有点自卑", 
                    "fans_total": "4993", 
                    "web_url": "http://image.wufazhuce.com/Fqv_ItuVfZPVywvC6Af-Jzz7FZZD"
                }, 
                "video_url": "", 
                "audio_url": "", 
                "audio_platform": 2, 
                "start_video": "", 
                "has_reading": 0, 
                "volume": 0, 
                "pic_info": "", 
                "words_info": "", 
                "subtitle": "", 
                "number": 0, 
                "serial_id": 0, 
                "serial_list": [ ], 
                "movie_story_id": 0, 
                "ad_id": 0, 
                "ad_type": 0, 
                "ad_pvurl": "", 
                "ad_linkurl": "", 
                "ad_makettime": "", 
                "ad_closetime": "", 
                "ad_share_cnt": "", 
                "ad_pvurl_vendor": "", 
                "content_id": "2111", 
                "content_type": "3", 
                "content_bgcolor": "#FFFFFF", 
                "share_url": "http://m.wufazhuce.com/question/2111", 
                "share_info": {
                    "url": "http://m.wufazhuce.com/question/2111", 
                    "image": "http://image.wufazhuce.com/FiWiDYn2mj9NN-LGsdWdgEFN0KjM", 
                    "title": "为什么越来越优秀的我，却越来越难找到男朋友？", 
                    "content": "自己变得越来越优秀，感觉自己应该能配得上更好的人啊。但是很奇怪啊，现在反倒是越来越难找到男朋友，就算有对象，dating了几次也都是不欢而散，是为什么呢？ "
                }, 
                "share_list": {
                    "wx": {
                        "title": "问答 | 为什么越来越优秀的我，却越来越难找到男朋友？", 
                        "desc": "文/菠菜 两个人交往，不需要证明自己多优秀，只需要不以爱为借口占对方便宜就行了。", 
                        "link": "http://m.wufazhuce.com/question/2111?channel=singlemessage", 
                        "imgUrl": "http://image.wufazhuce.com/ONE_logo_120_square.png", 
                        "audio": ""
                    }, 
                    "wx_timeline": {
                        "title": "问答 | 为什么越来越优秀的我，却越来越难找到男朋友？", 
                        "desc": "文/菠菜 两个人交往，不需要证明自己多优秀，只需要不以爱为借口占对方便宜就行了。", 
                        "link": "http://m.wufazhuce.com/question/2111?channel=timeline", 
                        "imgUrl": "http://image.wufazhuce.com/ONE_logo_120_square.png", 
                        "audio": ""
                    }, 
                    "weibo": {
                        "title": "ONE一个《问答 | 为什么越来越优秀的我，却越来越难找到男朋友？》 文/菠菜： 两个人交往，不需要证明自己多优秀，只需要不以爱为借口占对方便宜就行了。 阅读全文：http://m.wufazhuce.com/question/2111?channel=weibo 下载ONE一个APP:http://weibo.com/p/100404157874", 
                        "desc": "", 
                        "link": "http://m.wufazhuce.com/question/2111?channel=weibo", 
                        "imgUrl": "", 
                        "audio": ""
                    }, 
                    "qq": {
                        "title": "为什么越来越优秀的我，却越来越难找到男朋友？", 
                        "desc": "两个人交往，不需要证明自己多优秀，只需要不以爱为借口占对方便宜就行了。", 
                        "link": "http://m.wufazhuce.com/question/2111?channel=qq", 
                        "imgUrl": "http://image.wufazhuce.com/ONE_logo_120_square.png", 
                        "audio": ""
                    }
                }, 
                "tag_list": [ ]
            }, 
            {
                "id": "15418", 
                "category": "2", 
                "display_category": "1", 
                "item_id": "636", 
                "title": "嫉妒 · 第五章 · 1998-2005", 
                "forward": "她还不知道的是，每次她以为的谷底，都还不是她的谷底，折磨还早，一切尚早，她还得与生活、与情感不断地进行困兽之斗。", 
                "img_url": "http://image.wufazhuce.com/FsrzcZMEh7-USAfwPU2p662FWTQR", 
                "like_count": 201, 
                "post_date": "2018-05-28 06:00:00", 
                "last_update_date": "2018-05-27 15:19:52", 
                "author": {
                    "user_id": "8078728", 
                    "user_name": "张玲玲", 
                    "desc": "张玲玲，作家，编剧。", 
                    "wb_name": "", 
                    "is_settled": "0", 
                    "settled_type": "0", 
                    "summary": "作家，编剧。", 
                    "fans_total": "1833", 
                    "web_url": "http://image.wufazhuce.com/FnatLaSj_c7d2mtAZiXoG_COOT5f"
                }, 
                "video_url": "", 
                "audio_url": "", 
                "audio_platform": 2, 
                "start_video": "", 
                "has_reading": 0, 
                "volume": 0, 
                "pic_info": "", 
                "words_info": "", 
                "subtitle": "连载：第6章", 
                "number": "6", 
                "serial_id": "59", 
                "serial_list": [
                    "627", 
                    "631", 
                    "632", 
                    "633", 
                    "634", 
                    "636"
                ], 
                "movie_story_id": 0, 
                "ad_id": 0, 
                "ad_type": 0, 
                "ad_pvurl": "", 
                "ad_linkurl": "", 
                "ad_makettime": "", 
                "ad_closetime": "", 
                "ad_share_cnt": "", 
                "ad_pvurl_vendor": "", 
                "content_id": "636", 
                "content_type": "2", 
                "content_bgcolor": "#FFFFFF", 
                "share_url": "http://m.wufazhuce.com/serial/636", 
                "share_info": {
                    "url": "http://m.wufazhuce.com/serial/636", 
                    "image": "http://image.wufazhuce.com/FsrzcZMEh7-USAfwPU2p662FWTQR", 
                    "title": "嫉妒 · 第五章 · 1998-2005 作者/张玲玲", 
                    "content": "她还得与生活、与情感不断地进行困兽之斗。"
                }, 
                "share_list": {
                    "wx": {
                        "title": "连载 | 嫉妒 · 第五章 · 1998-2005", 
                        "desc": "文/张玲玲 她还得与生活、与情感不断地进行困兽之斗。", 
                        "link": "http://m.wufazhuce.com/serial/636?channel=singlemessage", 
                        "imgUrl": "http://image.wufazhuce.com/ONE_logo_120_square.png", 
                        "audio": ""
                    }, 
                    "wx_timeline": {
                        "title": "连载 | 嫉妒 · 第五章 · 1998-2005", 
                        "desc": "文/张玲玲 她还得与生活、与情感不断地进行困兽之斗。", 
                        "link": "http://m.wufazhuce.com/serial/636?channel=timeline", 
                        "imgUrl": "http://image.wufazhuce.com/ONE_logo_120_square.png", 
                        "audio": ""
                    }, 
                    "weibo": {
                        "title": "ONE一个《连载 | 嫉妒 · 第五章 · 1998-2005》 文/张玲玲： 她还得与生活、与情感不断地进行困兽之斗。 阅读全文：http://m.wufazhuce.com/serial/636?channel=weibo 下载ONE一个APP:http://weibo.com/p/100404157874", 
                        "desc": "", 
                        "link": "http://m.wufazhuce.com/serial/636?channel=weibo", 
                        "imgUrl": "", 
                        "audio": ""
                    }, 
                    "qq": {
                        "title": "嫉妒 · 第五章 · 1998-2005", 
                        "desc": "她还得与生活、与情感不断地进行困兽之斗。", 
                        "link": "http://m.wufazhuce.com/serial/636?channel=qq", 
                        "imgUrl": "http://image.wufazhuce.com/ONE_logo_120_square.png", 
                        "audio": ""
                    }
                }, 
                "tag_list": [ ]
            }, 
            {
                "id": "15415", 
                "category": "5", 
                "display_category": "1", 
                "item_id": "1433", 
                "title": " 有一种情话是，送你一束雏菊", 
                "forward": "爱不是风暴，是一米阳光。", 
                "img_url": "http://image.wufazhuce.com/FuHL8C4jgIcUHFAH3itNuBk6a7b8", 
                "like_count": 0, 
                "post_date": "2018-05-28 06:00:00", 
                "last_update_date": "2018-05-28 11:21:56", 
                "author": {
                    "user_id": "8066600", 
                    "user_name": "不辣", 
                    "desc": "出生农村，留学英国，常居江南。曾经，热血业余边缘传媒人；如今，想专注插秧却恨家中无田，无奈投入自由写作。已出版个人长篇小说《梦》。", 
                    "wb_name": "", 
                    "is_settled": "0", 
                    "settled_type": "0", 
                    "summary": "青年写作者", 
                    "fans_total": "1975", 
                    "web_url": "http://image.wufazhuce.com/FnjumacrXEQE8yHDGVGSSBydNzuA"
                }, 
                "video_url": "", 
                "audio_url": "", 
                "audio_platform": 2, 
                "start_video": "", 
                "has_reading": 0, 
                "volume": 0, 
                "pic_info": "", 
                "words_info": "", 
                "subtitle": "电影:雏菊", 
                "number": 0, 
                "serial_id": 0, 
                "serial_list": [ ], 
                "movie_story_id": "4416", 
                "ad_id": 0, 
                "ad_type": 0, 
                "ad_pvurl": "", 
                "ad_linkurl": "", 
                "ad_makettime": "", 
                "ad_closetime": "", 
                "ad_share_cnt": "", 
                "ad_pvurl_vendor": "", 
                "content_id": "1433", 
                "content_type": "5", 
                "content_bgcolor": "#FFFFFF", 
                "share_url": "http://m.wufazhuce.com/movie/1433", 
                "share_info": {
                    "url": "http://m.wufazhuce.com/movie/1433", 
                    "image": "http://image.wufazhuce.com/FuHL8C4jgIcUHFAH3itNuBk6a7b8", 
                    "title": "「一个」电影: 雏菊", 
                    "content": "
当生在南方的我，第一次吃到北方美食酸甜酥脆的锅包肉时，能给的最高食后感是：太好吃了，初恋的感觉。对于初恋这个主题，日本的影视作品是将此刻画最为细腻而真实、隐秘而温热的。岩井俊二的《四月物语》像是一首关于初恋的散文诗，白描了飘落的樱花间藏匿着的一个少女关于爱情的冲动和克制。初恋，是一场盘旋在心中无人知晓的风暴，不知何时会来，何时会走。
而因《我的野蛮女友》而被熟知的韩国明星全智贤，一改之前辛辣飒爽的表演风格，用《雏菊》这部纯爱片展现了一个别样的对初恋饱含期待和兴奋的少女。

惠瑛澄澈纯真，羞涩迷人，如同一朵金色雏菊，在阿姆斯特丹纯净的天空下，静谧地绽放。作为一名荷兰籍的自由画家，她每天除了画画，就是在爷爷的古董店忙碌。周末的时候，她会带着画板，去城市中央广场给来往的路人作画。

最近，惠瑛每天都会收到一束雏菊，但却从未谋面送花人。她一直在等待那个神秘人的出现，就像期待着还未降临到她身上的初恋。直到某天，一名捧着雏菊的陌生男子出现在惠瑛面前，让她作画。接连几周，这名陌生男子都会带着雏菊，如约而至。惠瑛的心开始澎湃起来，她不知道眼前这个男子是不是那个每天给她送花的神秘人。

一番接触后，惠瑛得知这个男子叫在佑。出于对在佑的好感，惠瑛邀请他去家里做客。在家里，在佑被惠瑛家一副雏菊画作迷住了。惠瑛趁机讲述了关于这幅画的故事：每年夏天，她都会去爷爷的村庄写生，在漫山遍野的雏菊地里自由作画。有一天，走过独木桥的她，不慎落水，写生包都被冲走了。惊喜的是，几天后她回到这里，发现独木桥变成了一座精心搭建的小桥，自己的写生包也挂在了桥边。她不知道这一切哪个好心人做的，只能画一副雏菊放在桥边作为回礼。
此后，她便每天都会收到一束雏菊。

在佑被惠瑛的故事感动，但是他知道自己并不是惠瑛要找的那个人，而是一个利用她的警察。在佑来到荷兰的真实是为了监视犯罪分子，抓捕一个贩毒集团。每天坐在惠瑛画板前，让她作画，不过是将惠瑛当作一枚烟雾弹，雏菊只是巧合。
然而在佑并不想说明真相，只是拥抱了惠瑛。他不想告诉惠瑛自己是警察，也不想澄清自己不是那个神秘人，因为在佑已经情不自禁地爱上了惠瑛。他只能用一个拥抱，许惠瑛一个美梦。
一天，在安静而温暖的城市中央广场发生了一场枪战。这场枪战引起了另一名注视着惠瑛的陌生男子的注意，为了保护惠瑛，他不停放地向广场射击。

这名男子的真实身份是杀手，几个月前，他任务完成后去乡下休息，偶遇作画的惠瑛，对她一见钟情。

但是，杀手的身份让他无法靠近惠瑛，他能做的只能在帮惠瑛修桥，搬到看得见惠瑛作画的房子，默默注视。想见惠瑛的时候，给她送一束雏菊。对杀手而言，一生都只能活在刺鼻而浓重的火药味里。知道泥土的味道可以吸收火药味，朴义开始学着种植雏菊，也看起了印象画派书作。他没有勇气和惠瑛说话，因为一个杀手要尽可能少接触其他人。直到有一天，在佑的出现替代了他的位置，朴义的心彻底崩塌了。

枪战过后，惠瑛声带受损失声，在佑被送回韩国。朴义不愿再看到惠瑛和别的男人在一起，鼓起勇气，像在佑那样，走到惠瑛面前。但是惠瑛每天都在思念在佑，以致于将朴义错画成在佑。在佑装作不在意，依然每周接送惠瑛，对惠瑛照顾体贴。

惠瑛感受到了朴义的心意，在咖啡店里向朴义坦白：自己已经有喜欢的人了。而此刻的朴义只能再一次违背自己心意，骗惠瑛说自己只是她的画感兴趣，想和她做个朋友，仅此而已。

回到荷兰的在佑，无法克服心中的愧疚，第一时间找到惠瑛，和她坦白了真相。其实在佑根本不是惠瑛要寻找的神秘人，而在佑所做的一切只不过是“利用”。惠瑛痛不欲生，但是她已经深深地爱上了在佑。也就是在这里，在佑和朴义有了第一次的正式见面。
为了抓捕犯罪分子，在佑以自己为饵，引诱杀手出来。巧合的是，进入包围圈的竟然是朴义。在佑带着朴义离开包围圈，开往河边。在车上，都爱着惠瑛的两个男人互相坦白自我。作为警察的在佑认为，惠瑛一直在等朴义的出现，该去画展的是朴义。身为杀手的朴义则觉得只有生活在阳光下的在佑才是真正应该去惠瑛画展的人。

因为爱，他们互相成全，也忘记了彼此是对头的身份。直到一记枪声，在佑倒在血泊中。
在佑死后，惠瑛和朴义度过了平静的一年，但是惠瑛一直没有停止过寻找杀死在佑的凶手。直到一盆黑色郁金香再次出现在朴义面前，杀手头目找到朴义，并许诺这是最后一次杀手任务。朴义把所有的任务资料都房子一只黑箱子里，偶然间惠瑛以古典乐为线索，发现了这只黑箱子和朴义的真实身份。举着枪的惠瑛试图逼朴义承认，是他杀了在佑，然而她却因太激动而昏倒。
等惠瑛醒来的时候，发现眼前放了一副雏菊画作和一叠留下的纸条。原来，她一直要寻找，一直在等待的那个神秘人，竟然是近在咫尺的朴义。

发了疯的惠瑛冲到城市中央广场，举着雏菊的画，要求朴义停止杀人任务。朴义来到惠瑛的面前，两人对视相望，慢慢靠近。然而，一个令人失望的杀手是没有存在价值的。当一枚飞向朴义的子弹被惠瑛率先看到，惠瑛第一时间用身体挡下了这颗致命的子弹。

失去挚爱的朴义愤怒地走进杀手大楼，用一场绚烂的枪战，结束了这场浪漫至死的爱的追逐。

在爱的屋檐下，所有人都是一样纯净、美好，不管是伪善之爱的警察还是血腥之爱的杀手。是爱，赐予了他们彼此间最珍贵的情感，无悔的等待、彼此的成全和无畏的牺牲。爱不是风暴，是一米阳光。
"
                }, 
                "share_list": {
                    "wx": {
                        "title": "电影 | 有一种情话是，送你一束雏菊", 
                        "desc": "文/不辣 爱不是风暴，是一米阳光。", 
                        "link": "http://m.wufazhuce.com/movie/1433?channel=singlemessage", 
                        "imgUrl": "http://image.wufazhuce.com/ONE_logo_120_square.png", 
                        "audio": ""
                    }, 
                    "wx_timeline": {
                        "title": "电影 | 有一种情话是，送你一束雏菊", 
                        "desc": "文/不辣 爱不是风暴，是一米阳光。", 
                        "link": "http://m.wufazhuce.com/movie/1433?channel=timeline", 
                        "imgUrl": "http://image.wufazhuce.com/ONE_logo_120_square.png", 
                        "audio": ""
                    }, 
                    "weibo": {
                        "title": "ONE一个《电影 | 有一种情话是，送你一束雏菊》 文/不辣： 爱不是风暴，是一米阳光。 阅读全文：http://m.wufazhuce.com/movie/1433?channel=weibo 下载ONE一个APP:http://weibo.com/p/100404157874", 
                        "desc": "", 
                        "link": "http://m.wufazhuce.com/movie/1433?channel=weibo", 
                        "imgUrl": "", 
                        "audio": ""
                    }, 
                    "qq": {
                        "title": "有一种情话是，送你一束雏菊", 
                        "desc": "爱不是风暴，是一米阳光。", 
                        "link": "http://m.wufazhuce.com/movie/1433?channel=qq", 
                        "imgUrl": "http://image.wufazhuce.com/ONE_logo_120_square.png", 
                        "audio": ""
                    }
                }, 
                "tag_list": [ ]
            }, 
            {
                "id": "15397", 
                "category": "4", 
                "display_category": "1", 
                "item_id": "2656", 
                "title": "也许你要试试一夜友情", 
                "forward": "如果真的建立起能随时相互联系的关系，我们会给对方带去多余的影响，不如就保持着单纯的信任感，总会再见面的。", 
                "img_url": "http://image.wufazhuce.com/FrZguxakNKouNSB1KWTM6rN-RjEF", 
                "like_count": 433, 
                "post_date": "2018-05-28 06:00:00", 
                "last_update_date": "2018-05-27 20:04:56", 
                "author": {
                    "user_id": "5620685", 
                    "user_name": "陈鸿宇", 
                    "desc": "音乐人", 
                    "wb_name": "众乐纪陈鸿宇", 
                    "is_settled": "0", 
                    "settled_type": "0", 
                    "summary": "音乐人", 
                    "fans_total": "2788", 
                    "web_url": "http://image.wufazhuce.com/Fr_Ald2eq6D1uTGEhj2EoHfTbSxd"
                }, 
                "video_url": "", 
                "audio_url": "", 
                "audio_platform": 2, 
                "start_video": "", 
                "has_reading": 0, 
                "volume": 0, 
                "pic_info": "", 
                "words_info": "", 
                "subtitle": "专辑:浓烟下的诗歌电台", 
                "number": 0, 
                "serial_id": 0, 
                "serial_list": [ ], 
                "movie_story_id": 0, 
                "ad_id": 0, 
                "ad_type": 0, 
                "ad_pvurl": "", 
                "ad_linkurl": "", 
                "ad_makettime": "", 
                "ad_closetime": "", 
                "ad_share_cnt": "", 
                "ad_pvurl_vendor": "", 
                "content_id": "2656", 
                "content_type": "4", 
                "content_bgcolor": "#FFFFFF", 
                "share_url": "http://m.wufazhuce.com/music/2656", 
                "share_info": {
                    "url": "http://m.wufazhuce.com/music/2656", 
                    "image": "http://image.wufazhuce.com/FrZguxakNKouNSB1KWTM6rN-RjEF", 
                    "title": "「一个」音乐: 陈鸿宇 你只是经过", 
                    "content": "
周末的晚上，我总会跟朋友到家楼下的小酒馆坐坐。
但最近忙于论文，这次我一人下来。
客人不多，才十二点左右，我已经是最后一个客人了。于是我一口喝完，拿起桌上的口香糖放进嘴里，准备离开。
结完账走出门的时候，身后传来一声怒吼：
“ motherfuxx ！谁吃了我的口香糖？”
说这句话的是一个留着络腮胡的高个子男生，他是这里的老板。
我走回去向他道歉，他见是我吃掉的，摆摆手说：“没事，我以为又被他吃掉了。” 然后指了指身后洗杯子的男生。
他又拿出两只玻璃杯，示意我坐下。
可能是今天客人离开得特别早，他想让我多留会儿。于是我们开始一边喝，一边有一搭没一搭地闲聊。
我说，我试过喝醉了在路上踢到一块砖头，顺势捡起来砸向旁边的墙，结果发现那是中国银行。
他说他因为喝醉打架，被拉进广州过半数的酒吧的黑名单。
我们又聊到喜欢的音乐和常去的酒吧，我发现这个满脸胡子的陌生男子，让我有种莫名其妙的契合感，我讲出的所有艺术家，奇怪的牌子，他都能立刻接上话。
我甚至特地试探性地播了一首巨冷门的歌，结果他熟练地跟着哼了起来。
我们就像一直走着同样的生活轨迹，只是一直没发现彼此，不知不觉，我们就聊到了两点。
他起身收拾店里的杯子，对我说：“不在这里喝了，我带你去个好地方，你绝对没见过，motherfuxx。”
这是我唯一感觉跟他有间隙的地方，在说这句口头禅时，我一定会在 motherfuxx 后加上 er 。
打开的士门的瞬间，我有点失望。
这是市中心非常有名的酒吧街，来这里就像回家一样毫无惊喜。但走了一路，他都没进过任何一家店门，兜兜转转来到一个露天停车场，在一辆大巴前停下了脚步。
“到了。”
他开始解鞋带，“上车吧。”
你能想象吗？在广州的市中心，酒吧街的露天停车场，停着一辆 45 座的大金龙大巴，重点是它是一个人的家。
大金龙的座椅被卸光了，取而代之的是一张两米的双人大床，两侧放着沙发，上面挂着空调，旁边有一壶正呼噜着的阿拉伯水烟。
住这的是个五十多岁的大叔，相貌很像甘地，正坐在沙发上喝伏特加。
招呼我坐下后，他倒给我一杯，没有问我姓名，很自然的开始跟我聊起了天。
他说自己年轻时赚了一点钱，后来跟妻子分开后把资产留给了对方，自己买了一台大金龙，从此在车上四海为家。
络腮胡老板说，自己隔三差五就带着酒上来跟他聊天，随口聊起的都是世界观、多维宇宙、性格气场这样的虚无话题。
不知道是不是酒精的作用，一个错觉是，他们就像古希腊沉迷辩论的学者，抛弃掉所有现代社会的便捷，没有 Wi-Fi 和厕所，却会为了“让悲剧停留在时间线上被吊唁还是加入干涉”而吵得面红耳赤。
此时此刻，旁边酒吧出来的男孩，正把刚认识的女生带上自己的车，两个半醉的中年人则在大金龙的车尾脱裤解手。
而我们，却在大巴车里从流行文化聊到爱情再聊到性。
我没想过，自己会和两个跟自己相差几十岁的人聊这些最贴近生活的问题。
在我的认知中，只要比自己大三岁的人都会有一个通病——强行向你灌输自己的观点，不留下任何反驳的余地。
但他们，却善于聆听和理解，再给予反馈。
最记得的是，“甘地”讲他对爱情的认知，就是两个人的气场会在某种时刻重合，而这种重合随时都在发生。
比如说，那天晚上，他看到自己的女朋友和一个男生在聊天，他们的气场和画面和谐又融洽，特别美好。
于是，他悄悄离开，绝不会插足去打破这个画面。
他觉得，人为地强行去打破或捏合，是会导致许多事情失衡的。
听完他这番话，我突然有某种程度上的释怀感。过去的很多怅然若失和气血方刚，其实就是自己“强求”过后的失衡状态。
倒不如放手让一切自然发展，就像今晚的我们，自然而然地发生了重合。
我努力回忆跟他们相处时的熟悉感来源于哪里，脑海里浮现了多年前的一次旅行。
六年级的我跟着游学团去到东京，在当地一家小学生活一天，被分配到一个叫泽田的男孩身边做同桌。
我们完全无法交流，英文水平还停留在“ How are you ？ ”的阶段，于是他笑的时候我便就跟着笑，他发呆的时候我就跟着发呆。
他拉着我去打躲避球，看见我放在鞋架上的雪地靴，发出了“哦哦哦”的惊叹声，然后偷偷拿了同学的帆布鞋给我。
去食堂吃午饭时，还把自己的肉酱分给了我一些。
那天放学的时候，我把包里的奥运福娃明信片送给他，却发现被雨水淋得又湿又皱。但他还是双手接过了礼物，然后送给我一罐千纸鹤，还有一张写着他名字和电话的纸条。
那时候，我才知道他的名字。
一个无法沟通，连名字都不知道的人，让我有了“朋友”的感觉。
回国之后我迫不及待想打给他，却发现无法见面的我们，看不到对方的表情和肢体之后，就真的完全不可能交流了。
但我却没有伤心难过的感觉，就好像找到了自己在远方生活的一个分身，彼此的生活极其相似，就算没有了联系也有一种信任感，似乎只要自己过得好，他也能过得很好。
看着甘地和络腮胡，我又找到了这种感觉。
我甚至可以预见二十、三十年后的自己，也许就是此时坐在身边的他们这样。
我们实在是太相似了，即使只是相识一晚，过去所有的记忆就都默默重合了。
我们一直聊到了六点，天已经亮了。
甘地喝多了靠在沙发上睡着了。我收拾了几个杯子，准备动身回家。
络腮胡叫我把手臂给他，然后把住我的脉搏，过了几秒后笑了笑，挥挥手说：“回家休息吧。”
我问他把出了什么，他说感觉到了其实我们都是自我内敛的人，所以才会在一台大金龙上畅所欲言。
我觉得他说得太玄乎，穿上鞋下了车。
突然他又探出身说：“还有一点，你的脉搏告诉我，你的肾还能放肆挥霍一下。”
还挺准的，我心里暗想，也许他刚刚说的也没有错。
不过到最后，我既没加他们的微信，他们也没有问。
可能我们的想法都一样：如果真的建立起能随时相互联系的关系，我们会给对方带去多余的影响。
不如就保持着单纯的信任感，总会再见面的。
文/KC
"
                }, 
                "share_list": {
                    "wx": {
                        "title": "音乐 | 也许你要试试一夜友情", 
                        "desc": "文/KC 不如就保持着单纯的信任感，总会再见面的。", 
                        "link": "http://m.wufazhuce.com/music/2656?channel=singlemessage", 
                        "imgUrl": "http://image.wufazhuce.com/ONE_logo_120_square.png", 
                        "audio": ""
                    }, 
                    "wx_timeline": {
                        "title": "音乐 | 也许你要试试一夜友情", 
                        "desc": "文/KC 不如就保持着单纯的信任感，总会再见面的。", 
                        "link": "http://m.wufazhuce.com/music/2656?channel=timeline", 
                        "imgUrl": "http://image.wufazhuce.com/ONE_logo_120_square.png", 
                        "audio": ""
                    }, 
                    "weibo": {
                        "title": "ONE一个《音乐 | 也许你要试试一夜友情》 文/KC： 不如就保持着单纯的信任感，总会再见面的。 阅读全文：http://m.wufazhuce.com/music/2656?channel=weibo 下载ONE一个APP:http://weibo.com/p/100404157874", 
                        "desc": "", 
                        "link": "http://m.wufazhuce.com/music/2656?channel=weibo", 
                        "imgUrl": "", 
                        "audio": ""
                    }, 
                    "qq": {
                        "title": "也许你要试试一夜友情", 
                        "desc": "不如就保持着单纯的信任感，总会再见面的。", 
                        "link": "http://m.wufazhuce.com/music/2656?channel=qq", 
                        "imgUrl": "http://image.wufazhuce.com/ONE_logo_120_square.png", 
                        "audio": ""
                    }
                }, 
                "tag_list": [ ]
            }
        ], 
        "menu": {
            "vol": "2060", 
            "list": [
                {
                    "content_type": "1", 
                    "content_id": "3276", 
                    "title": "氯", 
                    "tag": {
                        "id": "7", 
                        "title": "ONE STORY"
                    }
                }, 
                {
                    "content_type": "3", 
                    "content_id": "2111", 
                    "title": "为什么越来越优秀的我，却越来越难找到男朋友？"
                }, 
                {
                    "content_type": "2", 
                    "content_id": "636", 
                    "serial_list": [
                        "627", 
                        "631", 
                        "632", 
                        "633", 
                        "634", 
                        "636"
                    ], 
                    "title": "嫉妒 · 第五章 · 1998-2005"
                }, 
                {
                    "content_type": "5", 
                    "content_id": "1433", 
                    "title": " 有一种情话是，送你一束雏菊"
                }, 
                {
                    "content_type": "4", 
                    "content_id": "2656", 
                    "title": "也许你要试试一夜友情"
                }
            ]
        }
    }
}

Tips：location位置信息为必传参数
```
#### 3. 获取xx年xx月份的往期列表(首页点击头部ToolBar进入往期列表页面)

GET：/api/feeds/list/{yyyy-mm}?channel=cool

示例：http://v3.wufazhuce.com:8000/api/feeds/list/2018-05?channel=cool

返回示例：

```
{
    "res": 0, 
    "data": [
        {
            "id": 15406, 
            "date": "2018-05-28", 
            "cover": "http://image.wufazhuce.com/FpM8s5kk5nPtNsai4VRwcuUtXyuf"
        }, 
        {
            "id": 15377, 
            "date": "2018-05-27", 
            "cover": "http://image.wufazhuce.com/Fg_dmHn5t7cTe_cEV5YpHy9wq4tQ"
        }, 
        {
            "id": 15376, 
            "date": "2018-05-26", 
            "cover": "http://image.wufazhuce.com/Fu1qjJjsQ_wZ_3BR-utNJwUIGY-P"
        }, 
        {
            "id": 15374, 
            "date": "2018-05-25", 
            "cover": "http://image.wufazhuce.com/Fqe_prpZYRxIjYAp3PnpfC3h-U_t"
        }, 
        {
            "id": 15373, 
            "date": "2018-05-24", 
            "cover": "http://image.wufazhuce.com/FgFBVirpR6bBC95VBAv75JZqOGWx"
        }, 
        {
            "id": 15371, 
            "date": "2018-05-23", 
            "cover": "http://image.wufazhuce.com/Fj68SGk9ikiNWETRjy0Fq6X7fhKe"
        }, 
        {
            "id": 15370, 
            "date": "2018-05-22", 
            "cover": "http://image.wufazhuce.com/FhZIF8999UNT3dHxETXxycdF3fEn"
        }, 
        {
            "id": 15330, 
            "date": "2018-05-21", 
            "cover": "http://image.wufazhuce.com/Fsp_0kSbO9dBqfvfTR8f_5hHi7AN"
        }, 
        {
            "id": 15329, 
            "date": "2018-05-20", 
            "cover": "http://image.wufazhuce.com/Fm3V7KAcLdfe33O9Ie-Cbb_0rcKt"
        }, 
        {
            "id": 15328, 
            "date": "2018-05-19", 
            "cover": "http://image.wufazhuce.com/FgtDy8ym3xzbyAnEg5BujakzsP8s"
        }, 
        {
            "id": 15326, 
            "date": "2018-05-18", 
            "cover": "http://image.wufazhuce.com/FqY1m9k-bOwOj3oPM9TlyqYfYQN_"
        }, 
        {
            "id": 15325, 
            "date": "2018-05-17", 
            "cover": "http://image.wufazhuce.com/Fl5A9GJNO6qgvLX2UwONNPeRnHo1"
        }, 
        {
            "id": 15323, 
            "date": "2018-05-16", 
            "cover": "http://image.wufazhuce.com/FrVMbKMZn6e3XP9LELHHytsOUjQZ"
        }, 
        {
            "id": 15322, 
            "date": "2018-05-15", 
            "cover": "http://image.wufazhuce.com/FmxIIqf2BEBZ-IsmmvXygpRdHXG6"
        }, 
        {
            "id": 15266, 
            "date": "2018-05-14", 
            "cover": "http://image.wufazhuce.com/FoMQToEdCDYIzn5XT2sAJvmhD7LI"
        }, 
        {
            "id": 15256, 
            "date": "2018-05-13", 
            "cover": "http://image.wufazhuce.com/FmjZVIZV_Co4T34d2nyoN0DJzx2U"
        }, 
        {
            "id": 15308, 
            "date": "2018-05-12", 
            "cover": "http://image.wufazhuce.com/Fg8EhqDMIEK-OKkknwTA43giOpSm"
        }, 
        {
            "id": 15264, 
            "date": "2018-05-11", 
            "cover": "http://image.wufazhuce.com/FjCua-t2k4a3Twe1qjbov1FD7Yox"
        }, 
        {
            "id": 15262, 
            "date": "2018-05-10", 
            "cover": "http://image.wufazhuce.com/FkdoXuVvzt8W0LCikgeRa02YGGAZ"
        }, 
        {
            "id": 15261, 
            "date": "2018-05-09", 
            "cover": "http://image.wufazhuce.com/FnZxB2e_izm0TOV7KMW1jjPsEROS"
        }, 
        {
            "id": 15259, 
            "date": "2018-05-08", 
            "cover": "http://image.wufazhuce.com/Fo3bLqi6qTmXPna1USe1ulnDxL93"
        }, 
        {
            "id": 15258, 
            "date": "2018-05-07", 
            "cover": "http://image.wufazhuce.com/FnuBzVt7Yn5ZN3t_gU4sKrkz4vWM"
        }, 
        {
            "id": 15223, 
            "date": "2018-05-06", 
            "cover": "http://image.wufazhuce.com/FkgfPCVGOuzsCpmhKH36oTHd6FPM"
        }, 
        {
            "id": 15221, 
            "date": "2018-05-05", 
            "cover": "http://image.wufazhuce.com/FiFCwrkNsYt_y5NKq3OK3si6pX27"
        }, 
        {
            "id": 15220, 
            "date": "2018-05-04", 
            "cover": "http://image.wufazhuce.com/FpbQixPRlalOZIQFGv0umlTbB7BL"
        }, 
        {
            "id": 15218, 
            "date": "2018-05-03", 
            "cover": "http://image.wufazhuce.com/FvG1nNlR-7GnGh0TuP_Eo24EKb7T"
        }, 
        {
            "id": 15217, 
            "date": "2018-05-02", 
            "cover": "http://image.wufazhuce.com/FvgzVLpzK_rWI-UFafVIEQd3MhmU"
        }, 
        {
            "id": 15172, 
            "date": "2018-05-01", 
            "cover": "http://image.wufazhuce.com/FnN7xlBRjml1BT0uDQcr-PC7Qpgm"
        }
    ]
}
```
