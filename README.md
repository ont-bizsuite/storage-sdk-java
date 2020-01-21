# storage-sdk-java

## storage方法说明

### 获取对象实例并设置storage-midware服务地址
```
getInstance(String restfulUrl)
```

### 初始化设置app域名和签名私钥
```
init(String domain, String wif)
```

### 设置storage-midware服务地址
```
setRestfulUrl(String restfulUrl)
```

### 上传文件并生成注册Data ID二维码参数
```
uploadAndRegisterDataId(String ontid, MultipartFile file)
```

### 生成凭借token获取下载地址二维码参数
```
getDownloadUrl(Integer tokenId)
```

### 刷新未使用的下载token(jwt)
```
renewToken(String accessToken)
```

### 查询二维码扫码结果
```
invokeResult(String id)
```