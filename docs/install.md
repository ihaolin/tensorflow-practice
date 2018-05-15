# 安装文档

### On Mac

#### 使用 Virtualenv 进行安装

+ 安装`pip`：

```bash
sudo easy_install pip
```

+ 安装`virtualenv`：

```bash
sudo pip install --upgrade virtualenv
```

+ 在指定目录，建立一个虚拟环境(如`TARGET_DIR=~/Envir/tf`)：

```bash
virtualenv --system-site-packages $TARGET_DIR
```

+ 激活`virtualenv`环境（<font color="red">请注意，每次在新的 shell 中使用 TensorFlow 时，您都必须激活 Virtualenv 环境</font>）：

```bash
cd $TARGET_DIR
source ./bin/activate
```

+ 确保`pip`版本>=8.1：

```bash
easy_install -U pip
```

+ 在`virtualenv`环境中，安装`tensorflow`：

```bash
pip install --upgrade tensorflow
```

