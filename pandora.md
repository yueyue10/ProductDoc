# 绎景通接口文档

### 接口1：交通路线在地图查看

#### 请求格式
| 请求参数 | 类型 | 意义 |
| --- | --- | --- |
| busId | String | 车辆id |

#### 返回格式
```
{
    "result": 1,
    "message": "success",
    "value": {
        "busInfo": {
            "busNumber": "赣07100-28",
            "startStation": "游客服务中心",
            "endStation": "正一观",
            "stationInfo": [
                {
                    "arriveTime": "13:20",
                    "stationName": "游客服务中心",
                    "stationType": "上"
                },
                {
                    "arriveTime": "13:30",
                    "stationName": "象鼻山",
                    "stationType": ""
                },
                {
                    "arriveTime": "13:40",
                    "stationName": "竹筏码头",
                    "stationType": ""
                },
                {
                    "arriveTime": "13:50",
                    "stationName": "正一观",
                    "stationType": "下"
                }
            ]
        },
        "busRouteInfo": [
            {
                "id": 1,
                "type": 1,
                "codeType": 6,
                "lat": 28.123587,
                "lon": 116.987656,
                "resName": "游客服务中心",
                "stationType": "上",
                "onBusTime": "13:20上车"
            },
            {
                "id": 2,
                "type": 0,
                "codeType": "",
                "lat": 28.123587,
                "lon": 116.987656,
                "resName": "",
                "stationType": "",
                "onBusTime": ""
            },
            {
                "id": 3,
                "type": 1,
                "codeType": 6,
                "lat": 28.123587,
                "lon": 116.987656,
                "resName": "象鼻山",
                "stationType": "",
                "onBusTime": "13:30"
            },
            {
                "id": 4,
                "type": 0,
                "codeType": "",
                "lat": 28.123587,
                "lon": 116.987656,
                "resName": "",
                "stationType": "",
                "onBusTime": ""
            },
            {
                "id": 5,
                "type": 1,
                "codeType": 6,
                "lat": 28.123587,
                "lon": 116.987656,
                "resName": "竹筏码头",
                "stationType": "",
                "onBusTime": "13:40"
            },
            {
                "id": 6,
                "type": 0,
                "codeType": "",
                "lat": 28.123587,
                "lon": 116.987656,
                "resName": "",
                "stationType": "",
                "onBusTime": ""
            },
            {
                "id": 7,
                "type": 1,
                "codeType": 6,
                "lat": 28.123587,
                "lon": 116.987656,
                "resName": "正一观",
                "stationType": "下",
                "onBusTime": "13:50下车"
            }
        ],
        "mStationInfo": {
            "stationName": "游客服务中心",
            "currArriveTime": "本次到站约3分钟",
            "nextArriveTime": "下班车10分钟"
        }
    }
}
```
