# 一键生成古诗词数据库文件

## 使用方法

> 为了保证数据能及时更新，请自行先将官方项目克隆到本地，然后将里面的 **ci**、**json** 、**lunyu**、**shijing**、**sishuwujing**、**wudai**、**youmengying** 全都复制到本项目的 **Data** 目录中。

### SQLite 数据库

- 运行 python 脚本

```python
# 创建默认数据库文件
python3 manage.py

# 自定义数据库文件名称
python3 manage.py -n default.db
```

# 支持的数据库类型

- ~~sqlite~~
- mysql

## 注意事项

由于数据量过大，所以运行时间较长，还请耐心等待！

## 相关参考

- [chinese-poetry](https://github.com/chinese-poetry/chinese-poetry)
- [chinese-poetry-mysql](https://github.com/KomaBeyond/chinese-poetry-mysql)
