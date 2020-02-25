### 1. Qt 运行报错

```
  error: undefined reference to `QXlsx::Document::Document(QObject*)'
```

解决方法:

Qt项目中.pro文件中加入如下行

```c++
QT += xlsx
```



