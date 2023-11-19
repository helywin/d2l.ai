# README

practice of <https://zh.d2l.ai>

## 安装环境

```shell
# 安装torch cuda
conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia
```

导入导出

```shell
# 导出
conda list -e > requirements.txt
# 创建
$ conda create --name <env> --file requirements.txt
# 导入
conda install --yes --file requirements.txt
```
