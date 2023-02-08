# text_classification
Chinese text_classification
主要用于中文文本分类任务。包含主流的一些文本分类模型，模型大的分类主要包括:深度神经网络模型（FastText, TextCNN,TextRNN,TextBiRNN, TextRCNN等）还有部分预训练模型（BERT,ERNIE,ALBERT），
还可以通过参数设置来决定是通过字级别或者是词级别来进行分类任务，并且在以词级别分类时，还可以设置加入词性向量。
但是，也存在一些不足或有待完善的地方：
1. 这些模型分别位于不同的项目中，还没有完全融合在一起;
2.预训练模型部分的词和字分类任务是分开的，并不能通过参数配置来切换。
