# DSView_PD_Encoder
incremental rotary encoder, protocal decodes of DSView
DSView的协议解码插件,增量式旋转编码器
<img width="1422" height="310" alt="图片" src="https://github.com/user-attachments/assets/ca84669e-ff50-41e7-902e-9dcd183c93e9" />

<img width="437" height="254" alt="图片" src="https://github.com/user-attachments/assets/d2f1690f-6a88-473d-984b-1f0c1173e381" />

* POS: 增量式旋转编码器的计数值(AB两相4倍频).

* CNT: 该信号边沿属于递增或递减,用于判断信号抖动.

* LAPS: Z相信号的统计数量,以Z相信号上升沿为配匹配条件.

将encoderABZ文件夹复制到DSView安装目录下的decoders文件夹里即可(需重新打开DSView)

已知问题:偶尔会出现第一次打开时不显示POS项,这是由于软件底层不知由于何种原因没有调用python方法end,此时可以重新点击一次编码器选项,再点确定即可刷新

<img width="713" height="317" alt="图片" src="https://github.com/user-attachments/assets/1afcca4b-0121-4445-aa40-44dff8e5ad2f" />

