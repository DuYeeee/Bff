# Bff
基于大语言模型RWKV-7B的实时多模态输入和文本生成的的大模型
技术方案：
一、构建多模态token
1.1 图像token：SEED2
1.2 文本token：Autotoken
1.3 语音token：SpeechTokenizer
1.4 音乐token：Encodec
注意：构建多模态token使用anything2token的方法。
二、构建多模态数据集
三、扩展语言模型RWKV-7b词汇表
四、多模态预训练
五、评估模型性能
六、构建端到端系统
七、优化模型与数据
八、应用部署
