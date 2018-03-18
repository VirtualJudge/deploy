# VirtualJudgeDeploy
Virtual Judge - Deploy

### 接口测试部署
#### 国内方案
```
docker-compose up -d
```

#### 其他地区
```
cd others/
docker-compose up -d
```

#### 备注
第一次使用需要`/api/config_remote`用post方法提供爬虫账号密码
