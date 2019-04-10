# Apache 配置

设置外网访问

## 权限

在 httpd.conf 中

```html
    AllowOverride none  
    #Require all denied  
    Require all granted  
```

```html
    Require all granted  
```

在 httpd-vhost.conf 中

```html
    Require all granted
```

