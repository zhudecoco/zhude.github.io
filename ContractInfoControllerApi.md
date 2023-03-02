
# 
## 获取合约信息

**URL:** `/v1/inner/contract_config`

**Type:** `GET`

**Author:** zyq

**Content-Type:** `application/x-www-form-urlencoded;charset=UTF-8`

**Description:** 获取合约信息





**Request-example:**
```
curl -X GET -i /v1/inner/contract_config
```

**Response-fields:**

| Field | Type | Description | Since |
|-------|------|-------------|-------|
|code|string|No comments found.|-|
|msg|string|No comments found.|-|
|args|array|No comments found.|-|
|└─any object|object|any object.|-|
|data|object|No comments found.|-|
|└─any object|object|any object.|-|

**Response-example:**
```
{
  "code": "78272",
  "msg": "ro9y3t",
  "args": [
    {}
  ],
  "data": {}
}
```

