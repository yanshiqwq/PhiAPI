phigros token API
API： https://identity.pigeon-games.com/connect/token

方式：POST

请求格式：

authorization: Basic\n[BASE64 GameClient:[客户端UUID]]
body:
```json
{
    "grant_type": "password",
    "device": "[STRING] 设备名",
    "username": "[STRING] 用户名",
    "password": "[STRING] 密码",
    "scope": "offline_access openid user_api"
}
```

响应格式：
```json
{
    "access_token": "[STRING] access-token值",
    "expires_in": "[INT] token有效期（秒，默认3600）",
    "token_type": "[STRING] token类型（默认Bearer）",
    "refresh_token": "[STRING] refresh-token值",
    "scope": "offline_access openid user_api"
}
```

​