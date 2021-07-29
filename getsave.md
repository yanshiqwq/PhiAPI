phigros getsave API
API ：https://phigros.pigeon-games.com/api/save/phigros/data

方式：GET

请求格式：

authorization: Bearer\n[access_token]  
x-phigros-uuid: 你phi账号的uuid  
user-agent: BestHTTP/2 v2.3.2  

响应格式：
```json
{
  "status": true,
  "data": "[STRING] 你的存档JSON"
}
```

