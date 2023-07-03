# tencent-ml-images

## 一、基础环境

 - windows10
 - anaconda3 

## 二、环境搭建

### 2.1 tensorflow2.9(需要使用TF.29分支)

1. 创建环境

```
conda create -n TF2.9 python=3.10
```

2. 进入环境

```
activate  TF2.9
```

3. 安装tensorflow


```
pip install tensorflow
```


### 2.2 tensorflow1.6（原分支）

1. 创建环境

```
conda create -n TF1.6 python=3.6
```

2. 进入环境

```
activate  TF1.6
```

3. 安装tensorflow

 - 查看版本

```
https://gitcode.net/mirrors/fo40225/tensorflow-windows-wheel/-/tree/master/1.6.0

1.6.0\py36\CPU\sse2
VS2017 15.4
No
x86_64
Python 3.6

1.6.0\py36\CPU\avx2
VS2017 15.4
No
AVX2
Python 3.6

1.6.0\py36\GPU\cuda91cudnn71sse2
VS2017 15.4
9.1.85.3/7.1.1
x86_64
Python 3.6/Compute 3.0


1.6.0\py36\GPU\cuda91cudnn71avx2
VS2017 15.4
9.1.85.3/7.1.1
AVX2
Python 3.6/Compute 3.0,3.5,5.0,5.2,6.1,7.0
```

 - 下载
```
https://gitcode.net/mirrors/fo40225/tensorflow-windows-wheel/-/raw/9db727cdb008e689a45e9ae16be8eff9b71a3edb/1.6.0/py36/CPU/sse2/tensorflow-1.6.0-cp36-cp36m-win_amd64.whl
```

 - 安装

```
pip install tensorflow-1.6.0-cp36-cp36m-win_amd64.whl
pip install --upgrade opencv-python=3.4.5.20

```

### 三、运行

```
example\image_classification.bat
```