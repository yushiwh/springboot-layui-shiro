# SpringBoot+Layui后台管理系统
## 后端：
SpringBoot  2.1.0  
tk.mybatis  2.0.2  
Shiro  1.3.1  
Lombok 1.18.4  
## 前端：
Layui  2.4.5  
JQuery  3.3.1

## 渲染模板
Thymeleaf

## 密码
- 用了MD5的两次加密，并且用用户名进行加盐处理
- 通过修改密码的接口已经重置密码，都是123456

## 说明
- 主要是设置权限，不同用户进入看到不同的菜单权限