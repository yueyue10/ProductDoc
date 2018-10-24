# 蓬莱停车场接口文档

## 模块列表
| 模块名称 | 模块包含接口 |
| :-- | :-: |
|  [登录模块](#登录模块)| [1获取验证码接口](#一获取验证码接口)和[2登录接口](#二登录接口) |
|  [首页模块](#首页模块)| [3获取停车场信息接口](#三获取停车场信息接口) |
|  [车位余量管理模块](#车位余量管理模块) | [4修改停车场状态接口](#四修改停车场状态接口) |
|  [停车场资料管理模块](#停车场资料管理模块)| [5修改停车场资料接口](#五修改停车场资料接口) |

## 登录模块

#### 一获取验证码接口

#### 请求格式
| 请求参数 | 类型 | 意义 |
| --- | --- | --- |
| phoneNum | String | 管理员手机号 |

#### 返回格式
```
{
    "result": 1,
    "message": "success",
    "value": {
        "code": 502126
    }
}
```
#### 二登录接口

#### 请求格式
| 请求参数 | 类型 | 意义 |
| --- | --- | --- |
| phoneNum | String | 管理员手机号 |
| yzmCode | String | 验证码 |

#### 返回格式
```
{
    "result": 1,
    "message": "success",
    "value": {
        "userId": "1435",
        "parkId": 162534
    }
}
```
## 首页模块
[回到模块列表](#模块列表)

#### 三获取停车场信息接口

#### 请求格式
| 请求参数 | 类型 | 意义 |
| --- | --- | --- |
| parkId | String | 停车场Id |
| userId | String | 管理员Id |

#### 返回格式
```
{
    "result": 1,
    "message": "success",
    "value": {
        "parkName": "北分停车场",
        "parkStatus": "1",
        "parkId": 1,
        "parkType": "地上",
        "telNumber": 215464564,
        "toDockDistance": "230米",
        "managerName": "张三丰",
        "introduction": "北风停车场简介",
        "parkCharge": 12
    }
}
```
## 车位余量管理模块
[回到模块列表](#模块列表)

#### 四修改停车场状态接口

#### 请求格式
| 请求参数 | 类型 | 意义 |
| --- | --- | --- |
| userId | String | 管理员Id |
| parkId | String | 停车场Id |
| parkStatus | int | 1 |

#### 返回格式
```
{
    "result": 1,
    "message": "success",
    "value": null
}
```
## 停车场资料管理模块
[回到模块列表](#模块列表)

#### 五修改停车场资料接口

#### 请求格式
| 请求参数 | 类型 | 意义 |
| --- | --- | --- |
| userId | String | 管理员Id |
| parkId | String | 停车场Id |
| parkDoc | String | 停车场简介 |
| parkCharge | String | 停车场收费 |

#### 返回格式
```
{
    "result": 1,
    "message": "success",
    "value": null
}
```
