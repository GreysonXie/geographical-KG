## 在运行代码前用户需要新建配置文件

！！！如果需要使用**融合版2.0**系统可以忽略这一步
- 为保障用户的秘钥安全，大模型的api_key没有直接嵌入代码，而是需要存储在一个名为config.ini的文件中
格式要求：

```ini
[your_model]
api_key = your_key
```
- 在用户完成配置文件后，需要根据选择的模型相应的更改模型的名称与url，参考各个模型的官方api接口文档
