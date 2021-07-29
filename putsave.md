phigros putsave API
API ：https://phigros.pigeon-games.com/api/save/phigros/data

方式：PUT

请求格式：

authorization: Bearer\n[access_token]  
x-phigros-uuid: 你phi账号的uuid  
user-agent: BestHTTP/2 v2.3.2  
body: 你的存档JSON

响应格式：
```json
{
  "status": true
}
```

​