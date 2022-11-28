# PYMC Jupyterlab Docker Environment

1. 使用清华conda镜像下载
2. 使用pymc官方提供的pymc-env
3. 基础镜像使用jupyter/tensorflow-notebook


### 构建镜像
```bash
docker build -t somemc-notebook .
```
然后起来容器，找个端口