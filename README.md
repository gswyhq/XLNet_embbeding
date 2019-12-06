## XLNet Embedding

利用 Xlnet 预训练模型实现中文文本分类，keras 版

## 用法(训练/评估/测试)：
python3 demo.py

[docker镜像](https://hub.docker.com/r/gswyhq/keras-xlnet-chinese-text-classification)

## 预训练中文xlnet模型来源
chinese_xlnet_base_L-12_H-768_A-12.zip  
https://drive.google.com/open?id=1m9t-a4gKimbkP5rqGXXsEAEPhJSZ8tvx  

## 项目目录结构
```shell
~$ tree
.
├── chinese_xlnet_base_L-12_H-768_A-12
│   ├── spiece.model
│   ├── xlnet_config.json
│   ├── xlnet_model.ckpt.data-00000-of-00001
│   ├── xlnet_model.ckpt.index
│   └── xlnet_model.ckpt.meta
├── data
│   ├── predict.txt
│   ├── test.txt
│   └── train.txt
├── demo.log
├── demo.py
├── __init__.py
├── keras_adaptive_softmax -> https://github.com/CyberZHG/keras-adaptive-softmax/tree/master/keras_adaptive_softmax
├── keras_transformer_xl -> https://github.com/CyberZHG/keras-transformer-xl/tree/master/keras_transformer_xl
├── keras_trans_mask -> https://github.com/CyberZHG/keras-trans-mask/tree/master/keras_trans_mask
├── keras_xlnet -> https://github.com/CyberZHG/keras-xlnet/tree/master/keras_xlnet
├── keras_embed_sim -> https://github.com/CyberZHG/keras-embed-sim/tree/master/keras_embed_sim
├── keras_transformer -> https://github.com/CyberZHG/keras-transformer/tree/master/keras_transformer
├── keras_layer_normalization -> https://github.com/CyberZHG/keras-layer-normalization/tree/master/keras_layer_normalization
├── keras_multi_head -> https://github.com/CyberZHG/keras-multi-head/tree/master/keras_multi_head
├── keras_self_attention -> https://github.com/CyberZHG/keras-self-attention/tree/master/keras_self_attention
├── keras_position_wise_feed_forward -> https://github.com/CyberZHG/keras-position-wise-feed-forward/tree/master/keras_position_wise_feed_forward
├── keras_pos_embd -> https://github.com/CyberZHG/keras-pos-embd/tree/master/keras_pos_embd
├── LICENSE
├── model
│   ├── embedding_trainable.h5
│   └── model.h5
├── README.md
├── requirements.txt
└── xlnet_embedding.py
```

### 参考/致谢

1.  **Chinese-PreTrained-XLNet** (ymcui) https://github.com/ymcui/Chinese-PreTrained-XLNet
2.  **keras-xlnet** (CyberZHG)  https://github.com/CyberZHG/keras-xlnet
3.  **Keras-TextClassification** (yongzhuo) https://github.com/yongzhuo/Keras-TextClassification
4.  **xlnet** (zihangdai) https://github.com/zihangdai/xlnethttps://zhuanlan.zhihu.com/p/87981833
5.  **XLNet_embbeding** (zedom1) https://github.com/zedom1/XLNet_embbeding
