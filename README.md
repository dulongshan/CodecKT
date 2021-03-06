# 《编解码核心技术剖析》实现源码
接触视频编解码技术已五年有余，一直想把视频编解码技术融汇贯通，虽然难度很大，但“世上无难事，只怕有心人”。工作闲暇之余，便想着整理出这本名曰《编解码核心技术剖析》的技术书籍，该书旨在让视频编解码技术“平民化”，不求辞藻华丽，但求通俗易懂。此书本着“免费、开源、共享、实用”四大原则，绝无鸡肋（最近在追《司马懿之军师联盟》，哈哈。），希望将来能够成为Codec领域“共享精神”的领头羊之一，让所有视频编解码技术爱好者都能轻而易举地掌握这门技术。

源码章节划分如下：

第一章 概述 Null

第二章 颜色空间 chapter02

第三章 编码结构 chapter03

第四章 帧内预测 chapter04

第五章 帧间预测 chapter05

第六章 变换量化、反量化反变换 chapter06

第七章 环路滤波 chapter07

第八章 熵编码 chapter08

第九章 参考帧管理技术 chapter09

第十章 码率控制技术 chapter10

第十一章 率失真优化技术 chapter11

第十二章 网络分层技术 chapter12

第十三章 并行处理技术 chapter13

第十四章 Smart视频编码技术 chapter14

第十五章 屏幕内容编码（Screen Content Coding，SCC） chapter15

第十六章 可伸缩视频编码（Scalable Video Coding，SVC） chapter16

第十七章 多视点视频编码（Multiview Video Coding，MVC） chapter17

第十八章 立体视频编码（Stereo Video Coding，3DVC） chapter18

第十九章 虚拟现实编码（Virtual-Reality Coding，VRC） chapter19

第二十章 硬件编解码（Hardware Codec） chapter20

第二十一章 视频编解码技术发展与展望 Null

从本质上讲，各种编码标准的“套路”如出一辙，因此，本书会把主流的编码标准（H.264/HEVC、VP8/VP9、SVAC1/SVAC2、AVS1/AVS2、AV1等）之间的区别整理出来，每一章节独立成文，既可以当做手册使用，又可以当做教程参阅，除此之外，本书中的所有编码技术都会经由本人亲自验证，所有源码均会第一时间在https://github.com/RuidongFang/CodecKT （对应书籍地址：https://www.gitbook.com/book/ruidongfang/codec-key-technologies-analyses ）上公开。因工作繁忙，故此书初稿预计将于2021年07月12日左右完成，期望这个时间节点不会太晚，以至于所验证编码技术已经远远落后于市场主流编解码技术。

方瑞东于杭州高新区

2017年07月12日

# 参考源码
FFMPEG：https://ffmpeg.org/
