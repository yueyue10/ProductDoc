# 绎景通 行程导引接口文档（v1.0）

## 行程导引
### 行程导引模拟数据接口

#### 请求地址

http://www.wanandroid.com/tools/mockapi/5708/getRoute1_TigerJsonStr

#### 返回格式
```
{
  "result": 1,
  "message": "success",
  "value": [
    {
      "id": "51_52",
      "name": null,
      "lat": 28.10905,
      "lon": 116.986114,
      "aid": 602,
      "rid": 0,
      "isChoosed": 0,
      "tiger_data": {
        "message": "到达高空栈道，栈道像一条游龙蜿蜒缠绕在悬崖峭壁之上，沿线景点众多，设有多个观景平台。",
        "delay_time": 200
      }
    },
    {
      "id": "57_58",
      "name": null,
      "lat": 28.102279,
      "lon": 116.982624,
      "aid": 640,
      "rid": 0,
      "isChoosed": 0,
      "tiger_data": {
        "message": "前方200米就到象鼻山的最佳拍照点啦，现在排队人数不多，快去跟大象鼻子合影吧。",
        "result": 1,
        "value": {
          "msg_remind": {
            "text": "最佳拍照点推荐！\n前方200米就到象鼻山的最佳拍照点啦，现在排队人数不多，快去跟大象鼻子合影吧。"
          }
        }
      }
    },
    {
      "id": "62_74",
      "name": null,
      "lat": 28.09822,
      "lon": 116.978447,
      "aid": 727,
      "rid": 0,
      "isChoosed": 0,
      "tiger_data": {
        "message": "升棺表演两小时候就要开始了",
        "result": 1,
        "value": {
          "msg_remind": {
            "text": "升棺表演两小时候就要开始了"
          }
        }
      }
    },
    {
      "id": "118_119",
      "name": null,
      "lat": 28.074315,
      "lon": 116.980049,
      "aid": 876,
      "rid": 0,
      "isChoosed": 0,
      "tafficeType": "竹筏",
      "tiger_data": {
        "message": "行程已结束,与好朋友分享一下美好回忆吧！",
        "result": 1,
        "end_delay_time": 13000,
        "value": {
          "msg_remind": {
            "jump": 1,
            "text": "行程结束！\n行程已结束,与好朋友分享一下美好回忆吧！"
          }
        }
      }
    },
    {
      "id": "180_181",
      "name": null,
      "lat": 28.047494,
      "lon": 117.052318,
      "aid": 975,
      "rid": 0,
      "isChoosed": 0,
      "tiger_data": {
        "result": 1,
        "delay_time": 20,
        "message": "到达天师府。升棺表演两小时候就要开始了，您还可以在天师府游玩半小时，之后可乘坐观光车前往竹筏码头。",
        "value": {
          "msg_remind": {
            "text": "表演提醒！\n升棺表演2小时候就要开始了，您还可以在天师府游玩半小时，之后可乘坐观光车前往竹筏码头。",
            "jump": 0,
            "traffic": {
              "stroke": 27,
              "roadId": "172_101",
              "traffic": "竹筏",
              "canmodify": false
            }
          }
        }
      }
    },
    {
      "id": "56_83",
      "name": null,
      "lat": 28.107314,
      "lon": 116.985004,
      "aid": 620,
      "rid": 0,
      "isChoosed": 0,
      "tiger_data": {
        "message": "您所处位置的右前方，陡峭的崖壁上生长着大名鼎鼎的九大仙草之首就是铁皮石斛。是我们根据您的情况特意推荐的养生佳品，相信您一定会喜欢。",
        "result": 2,
        "value": {
          "specialty_recomd": {
            "lat": 28.104824,
            "lon": 116.983548,
            "name": "铁皮石斛",
            "content": "药中黄金",
            "res_url": "http://mp.weixin.qq.com/s?__biz=MzI1NTc0ODIzMw==&mid=100000052&idx=1&sn=b2ffa2b42fb91e8b2b78521da76c8462&chksm=6a3070d25d47f9c408b68414c4f08d9455f19e78d31b2a53091929988fa81df1687cbc4189a0#rd"
          }
        }
      }
    },
    {
      "id": "109",
      "name": "无蚊村观光车站",
      "lat": 28.086804,
      "lon": 116.976433,
      "aid": 280,
      "rid": 0,
      "isChoosed": 0,
      "tiger_data": {
        "message": "到达无蚊村，相传，有一次张天师和母亲从兜率宫回天师府途中在许家村借宿，夜晚蚊虫众多，扰得张母坐卧不安。天师是孝子，拿起法扇挥手一扇，蚊子顿时逃遁一空。从此以后，许家村再也没有蚊子。",
        "result": 3,
        "value": {
          "spot_recomd": {
            "lat": 28.08627,
            "lon": 116.97452,
            "codeType": 1,
            "type": 3,
            "id": 30
          }
        }
      }
    },
    {
      "id": "155_156",
      "name": null,
      "lat": 28.055516,
      "lon": 117.02659,
      "aid": 940,
      "rid": 0,
      "isChoosed": 0,
      "tiger_data": {
        "message": "午餐时间到，龙虎山特色美食八卦宴不容错过，快去广缘斋瞧瞧吧，现在预订还能享受九折优惠哦",
        "delay_time": 100,
        "result": 5,
        "value": {
          "spot_recomd": {
            "name": "广缘斋",
            "comment": "简介",
            "scode": 5,
            "picUrl": "http://travel.enn.cn/group1/M00/00/19/CiaAUlqhCMmACi8kAAGBR8_Gq30604.jpg",
            "id": 61,
            "codeType": 3
          }
        }
      }
    }
  ]
}
```
#### 返回参数说明

| 响应参数       | 类型        | 说明                                                                     |
| ---------------| ------------| -------------------------------------------------------------------------|
| __tiger_data__ | JsonElement | 小老虎需要使用的信息                                                     |
| message        | String      | 语音播放内容                                                             |
| delay_time     | int         | 移动过程中的延迟时间                                                     |
| end_delay_time | int         | 等待结束命令的延迟时间                                                   |
| result         | int         | 功能类型：1.消息提示 2：特产推荐  3.景点推荐 4.小老虎停止移动 5.餐馆推荐 |
| value          | JsonObject  | 功能内容                                                                 |
|                |             |                                                                          |
>|__msg_remind__ | JsonObject | 消息提示 |
>| --- | --- | --- |
>| text | String | 提示内容 |
>| jump | int | 跳转标识：0：跳转交通页面 1：跳转我的游记列表 |

>>| __traffic__ | JsonObject | 交通信息 |
| --- | --- | --- |
| stroke | String | -- |
| roadId | String | -- |
| traffic | String | -- |
| canmodify | boolean | -- |

>| __spot_recomd__ | JsonObject | 景点推荐 |
| --- | --- | --- |
| lat | double | -- |
| lon | double | -- |
| codeType | int | -- |
| type | int | -- |
| id | int | -- |
| name | String | 广缘斋 |
| comment | String | 简介 |
| scode | int | 5 |
| picUrl | String | http://travel.enn.cn/group1/M00/00/19/CiaAUlqhCMmACi8kAAGBR8_Gq30604.jpg |
| id | int | 61 |
| codeType | int | 3 |

>| __specialty_recomd__ | JsonObject | 特产推荐 |
| --- | --- | --- |
| lat | double | 28.104824 |
| lon | double | 116.983548 |
| name | String | 铁皮石斛 |
| content | String | 药中黄金 |
| picUrl | String | http://travel.enn.cn/group1/M00/00/19/CiaAUlqhCMmACi8kAAGBR8_Gq30604.jpg |


