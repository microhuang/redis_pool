# redis_pool

```
#设置密码
requirepass foobared
#禁止切换键空间，配合proxy限定db访问。cluster模式只有database 0
rename-command SELECT ""
```
