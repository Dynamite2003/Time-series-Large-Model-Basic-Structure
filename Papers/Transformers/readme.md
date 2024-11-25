# 这个板块下是一些Transformer的架构变体和之前的时序领域论文
1. ALiu等-2024 - iTransformer: Inverted Transformers Are Effective for Time Series Forecasting

该论文提出了iTransformer模型，通过将传统Transformer的输入维度进行倒置处理，以更有效地捕获多变量时间序列中的相关性。具体而言，模型将每个变量的整个时间序列嵌入为一个token，利用自注意力机制捕获变量间的关系，从而提升预测性能。 
知乎专栏

2. Liu等 - Non-stationary Transformers: Exploring the Stationarity in Time Series Forecasting

作者探讨了时间序列预测中的平稳性问题，提出了Non-stationary Transformers框架。该框架包含序列平稳化和去平稳化注意力模块，旨在提高模型对非平稳时间序列的预测能力。实验结果显示，该方法在多个数据集上取得了优异的性能。 
知乎专栏

3. Nie等-2023 - A Time Series is Worth 64 Words: Long-term Forecasting with Transformers

本研究提出了一种将时间序列数据表示为固定长度词嵌入的方法，利用Transformer模型进行长期预测。通过将时间序列划分为等长片段，并将每个片段编码为一个词嵌入，模型能够有效捕获长期依赖关系，提高预测精度。

4. Pei等-2021 - Towards Generating Real-World Time Series Data

该论文探讨了生成真实世界时间序列数据的方法，提出了一种基于生成对抗网络（GAN）的框架。通过引入时间依赖性和多变量相关性，模型能够生成具有真实特征的时间序列数据，为下游任务提供高质量的合成数据支持。

5. Rasul等-2024 - Lag-Llama: Towards Foundation Models for Probabilistic Time Series Forecasting

作者提出了Lag-Llama模型，旨在构建用于概率时间序列预测的基础模型。该模型结合了自回归和深度学习方法，能够捕获时间序列中的复杂模式和不确定性，为概率预测提供了新的思路。

6. Vaswani等-2023 - Attention Is All You Need

这篇经典论文引入了Transformer模型，彻底改变了自然语言处理领域。通过自注意力机制，模型能够并行处理序列数据，捕获长距离依赖关系，显著提升了机器翻译等任务的性能。

7. Wu等-2022 - Autoformer: Decomposition Transformers with Auto-Correlation for Long-Term Series Forecasting

该研究提出了Autoformer模型，结合了时间序列分解和自相关机制，旨在进行长期时间序列预测。通过将时间序列分解为趋势和季节性成分，模型能够更好地捕获长期依赖，提高预测准确性。

8. Zeng等-2022 - Are Transformers Effective for Time Series Forecasting?

该论文评估了Transformer模型在时间序列预测任务中的有效性。通过实验分析，作者发现Transformer在捕获长距离依赖方面具有优势，但在处理短期模式时可能存在不足。研究为未来改进提供了方向。

9. Zhang和Yan - 2023 - Crossformer: Transformer Utilizing Cross-Dimension Dependency for Multivariate Time Series Forecasting

本研究提出了Crossformer模型，旨在利用跨维度依赖性进行多变量时间序列预测。通过设计跨维度的自注意力机制，模型能够捕获变量之间的复杂关系，提高预测性能。