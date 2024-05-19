# 数据预处理自用指南

## Step.1 原始数据下载
- 文件夹dataset_info存储了部分常用数据集的信息。
- 数据集下载地址以及使用方式，具体参考conversion_tools文件夹下面的usage中的各数据集MD文档。
## Step.2 原始数据转换
- 我已经用Amazon_Video_Games这个数据集做了例子，大家可以参考我的路径写法
- 在程序运行部分，建议使用以下input_path 和 output_path，将数据集名字替换即可
- 生成的inter和item两个文件需要手动复制到根目录的dataset文件夹下
```
python run.py --dataset amazon_video_games \
--input_path dataset_origin/Amazon_Video_Games \
--output_path dataset_origin/Amazon_Video_Games/output_data/ \
--convert_inter --convert_item
```


