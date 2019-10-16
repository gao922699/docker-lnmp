**lnmp开发环境**

- nginx：官方源
- php：自用7.2，适配laravel，安装了composer和redis扩展
- mysql：5.7

**使用：**

- 拷贝一份docker-compose.override.yml.sample到根目录，文件名去掉.sample，修改绑定端口为自己需要的值
- docker-compose up -d