# RecBole自用指南

## Step1 环境安装

**NOTICE：不要自己单独安装任何一个依赖，不然很容易整个程序都报错，按照下面这个步骤依次进行**

- ```git clone https://github.com/Superluckzwx/RecBole.git```
- ```cd RecBole```
- 选择要使用的环境，强烈推荐使用一个空环境，python>=3.7（我使用的3.11）,然后执行下面
- ```pip install -e . --verbose```
- 等待安装完成，使用下面这个进行测试
- ```python run_recbole.py```

成功后即可进行下面的步骤

## Step2 数据预处理

此部分参考根目录*RecSysDatasets-master*文件夹下的*README*文件

## Step3 程序运行

程序运行部分请参考项目本身的README文档