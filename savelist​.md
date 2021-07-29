phigros savelist API​
API： https://phigros.pigeon-games.com/api/save/phigros
  
方式：GET  
  
请求格式：  
  
authorization: Bearer\n[access_token]  
x-phigros-uuid: 你phi账号的uuid  
user-agent: BestHTTP/2 v2.3.2  
  
响应格式：  
  
```json
{
  "status": true,
  "data": {
    "user": "[STRING] 你的userid",
    "gameVersion": "[STRING] 游戏版本",
    "device": "[STRING] 设备名",
    "uuid": "[STRING] 存档UUID",
    "createdAt": "[STRING] 创建时间",
    "updatedAt": "[STRING] 更新时间"
  }
}
```

