Docker Extend NodeJS with Specified Version Demo
================================================

我们需要让自己的Dockerfile使用指定版本的nodejs，比如`10.9.0`。

可以在`Dockerfile`中指定：

```
FROM docker run node:10.9.0
```

Build：

```
docker build .
```

运行:

```

```