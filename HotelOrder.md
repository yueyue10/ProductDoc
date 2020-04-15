# BigScreen

大峡谷大屏

### http://10.38.64.126:8555/ayue2019/bigscreen.git

### 方案一(下单界面参数全传)：酒店下单界面的参数去重去非必要：
```
stayInfo.hotelId
stayInfo.hotelName
stayInfo.inTime
stayInfo.outTime

roomInfo.id
roomInfo.stock
roomInfo.roomName
roomInfo.hotelDes
roomInfo.salePrice
roomInfo.yudingMsg
```
### 方案二(下单界面参数部分传，首页再请求酒店房型列表接口再根据房型id匹配获取到对应的房型详细信息)：
### 酒店下单界面的参数传必要的，自己再请求一部分：
```
stayInfo.hotelId
stayInfo.hotelName
stayInfo.inTime
stayInfo.outTime

roomInfo.id
```

### 酒店下单界面的参数都列出来：
```
界面上使用的参数：
stayInfo.hotelName
stayInfo.stayTime
stayInfo.leaveTime
stayInfo.stopDays

roomInfo.roomName
roomInfo.hotelDes
roomInfo.salePrice
roomInfo.yudingMsg

提交订单使用参数：
stayInfo.hotelId
stayInfo.inTime
stayInfo.outTime
stayInfo.hotelName

roomInfo.id
roomInfo.roomName
roomInfo.stock
roomInfo.salePrice
```

