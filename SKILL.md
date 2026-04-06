---
name: sql-helper
description: "SQL助手。编写、优化、调试SQL查询。使用场景：(1) 编写复杂查询，(2) 优化查询性能，(3) 调试SQL错误，(4) 数据库设计建议。"
metadata: {"openclaw": {"emoji": "🗃️"}}
---

# SQL Helper — SQL助手

## 功能说明

辅助SQL查询编写和优化。

## 使用方法

### 1. 查询编写

```
用户: 写一个SQL查询，统计每个用户的订单数量和总金额
```

### 2. 查询优化

```
用户: 这个查询很慢，帮我优化：
SELECT * FROM orders WHERE user_id IN (SELECT id FROM users WHERE status = 1)
```

### 3. 错误调试

```
用户: 这个SQL报错了，帮我看看：
SELECT name FORM users
```

### 4. 表设计

```
用户: 设计一个电商订单表的结构
```

## 支持数据库

- MySQL
- PostgreSQL
- SQLite
- SQL Server
