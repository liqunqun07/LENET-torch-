# LENET-torch-
torch构建LENET
准备数据集（每个有六个类别）

<img width="130" height="151" alt="image" src="https://github.com/user-attachments/assets/bf01a887-4737-4a3a-9742-f61f4bdc6668" />


依赖环境
torch >= 1.10
torchvision
PIL
numpy
matplotlib

需要修改数据集的路径（需要自己准备数据集）和模型输出的路径需要修改
在训练的时候加入用验证集来评估损失（后面的测试用了验证集的某一张图 仅作为展示）正式训练可以再划分一组作为测试集

