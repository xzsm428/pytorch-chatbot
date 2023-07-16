# pytorch-chatbot
基于 PyTorch 框架和 Seq2Seq 模型实现的 CHATBOT

## 参考文档
https://pytorch.org/tutorials/beginner/chatbot_tutorial.html  
https://fancyerii.github.io/2019/02/14/chatbot/

## 系统架构
![image](https://github.com/xzsm428/pytorch-chatbot/assets/109144528/add054c9-e995-4e00-aa03-8d213039ab58)

## 训练参数

```py
clip = 50.0
teacher_forcing_ratio = 0.7
learning_rate = 0.0001
decoder_learning_ratio = 5.0
n_iteration = 9000
print_every = 1
save_every = 500
```
## 效果
![image](https://github.com/xzsm428/pytorch-chatbot/assets/109144528/f8b510f5-9811-4bd1-8334-336649893809)

