# test
本项目旨在开发一个基于深度学习的文本生成系统，通过训练长短时记忆网络（LSTM）模型，生成具有连贯性和语义一致性的文本内容。项目实现了从语料预处理、模型搭建、训练优化到文本生成的全流程，并支持多样性控制（如温度调节），以生成风格多变且自然的文本。

核心功能
数据处理

支持多种文本数据的导入（如诗歌、小说、对话）。
数据归一化、字符序列转化、语料切分等预处理步骤。
模型架构

使用双层 LSTM 模型，捕捉上下文语义。
加入 Dropout 层以防止过拟合。
使用 Softmax 激活函数输出字符概率分布。
文本生成

支持用户指定文本种子，生成基于种子的连续文本。
可调节生成温度参数，控制文本多样性与随机性。
评估与优化

使用损失曲线监控模型训练过程。
可扩展其他模型（如 Transformer、GPT 等）以比较性能。
技术栈
编程语言：Python
深度学习框架：TensorFlow / Keras
数据处理：NumPy、Pandas
可视化：Matplotlib
