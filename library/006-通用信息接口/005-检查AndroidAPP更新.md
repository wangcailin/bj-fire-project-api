# 检查AndroidAPP更新接口

> 维护人员：王彩霖

> 创建时间：2017年12月21日

## 接口详情

### 请求地址
```
/api/allthedata/updateAndroidApp
```

### 请求类型
GET POST

### 请求参数
无

### 正确响应
```javascript
{
    "success": true,
    "code": 0,
    "msg": "ok",
    "data": {
        "version": "1001",
        "desc": "请输入更新描述",
        "url": ""
    }
}
```

### 错误响应
```javascript
无
```
