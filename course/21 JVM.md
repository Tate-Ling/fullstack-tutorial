## 《深入理解Java虚拟机》学习记录

[深入理解Java虚拟机（jvm性能调优+内存模型+虚拟机原理）](https://www.roncoo.com/course/view/0ec92a81e8764b838e86c4febe7a5b17)


| 章节                                                 | 记录 |
| ---------------------------------------------------- | ---- |
| 1 说在前面的话                                       |      |
| 2 整个部分要讲的内容说明                             |      |
| 3 环境搭建以及jdk,jre,jvm的关系                      |      |
| 4 jvm初体验-内存溢出问题的分析与解决                 |      |
| 5 jvm再体验-jvm可视化监控工具                        |      |
| 6 杂谈                                               |      |
| 7 Java的发展历史                                     |      |
| 8 Java的发展历史续                                   |      |
| 9 Java技术体系                                       |      |
| 10 jdk8的新特性                                      |      |
| 11 lanmbda表达式简介                                 |      |
| 12 Java虚拟机-classic vm                             |      |
| 13 Java虚拟机-ExactVM                                |      |
| 14 Java虚拟机-HotSpotVM                              |      |
| 15 Java虚拟机-kvm                                    |      |
| 16 Java虚拟机-JRockit                                |      |
| 17 Java虚拟机-j9                                     |      |
| 18 Java虚拟机-dalvik                                 |      |
| 19 Java虚拟机-MicrosoftJVM                           |      |
| 20 Java虚拟机-高性能Java虚拟机                       |      |
| 21 Java虚拟机-TaobaoVM                               |      |
| 22 Java内存区域-简介                                 |      |
| 23 Java内存区域-Java虚拟机栈                         |      |
| 24 Java内存区域-程序计数器                           |      |
| 25 Java内存区域-本地方法栈                           |      |
| 26 Java内存区域-堆内存                               |      |
| 27 Java内存区域-方法区                               |      |
| 28 Java内存区域-直接内存和运行时常量池               |      |
| 29 对象在内存中的布局-对象的创建                     |      |
| 30 探究对象的结构                                    |      |
| 31 深入理解对象的访问定位                            |      |
| 32 垃圾回收-概述                                     |      |
| 33 垃圾回收-判断对象是否存活算法-引用计数法详解      |      |
| 34 垃圾回收-判断对象是否存活算法-可达性分析法详解    |      |
| 35 垃圾回收算法-标记清除算法                         |      |
| 36 垃圾回收算法-复制算法                             |      |
| 37 垃圾回收算法-标记整理算法和分代收集算法           |      |
| 38 垃圾收集器-serial收集器详解                       |      |
| 39 垃圾收集器-parnew收集器详解                       |      |
| 40 垃圾收集器-parallel收集器详解                     |      |
| 41 垃圾收集器-cms收集器详解                          |      |
| 42 最牛的垃圾收集器-g1收集器详解                     |      |
| 43 内存分配-概述                                     |      |
| 44 内存分配-Eden区域                                 |      |
| 45 内存分配-大对象直接进老年代                       |      |
| 46 内存分配-长期存活的对象进入老年代                 |      |
| 47 内存分配-空间分配担保                             |      |
| 48 内存分配-逃逸分析与栈上分配                       |      |
| 49 虚拟机工具介绍                                    |      |
| 50 虚拟机工具-jps详解                                |      |
| 51 虚拟机工具-jstat详解                              |      |
| 52 虚拟机工具-jinfo详解                              |      |
| 53 虚拟机工具-jmap详解                               |      |
| 54 虚拟机工具-jhat详解                               |      |
| 55 虚拟机工具-jstack详解                             |      |
| 56 可视化虚拟机工具-Jconsole内存监控                 |      |
| 57 可视化虚拟机工具-Jconsole线程监控                 |      |
| 58 死锁原理以及可视化虚拟机工具-Jconsole线程死锁监控 |      |
| 59 VisualVM使用详解                                  |      |
| 60 性能调优概述                                      |      |
| 61 性能调优-案例1                                    |      |
| 62 性能调优-案例2                                    |      |
| 63 性能调优-案例3                                    |      |
| 64 前半部分内容整体回顾                              |      |
| 65 Class文件简介和发展历史                           |      |
| 66 Class文件结构概述                                 |      |
| 67 Class文件设计理念以及意义                         |      |
| 68 文件结构-魔数                                     |      |
| 69 文件结构-常量池                                   |      |
| 70 文件结构-访问标志                                 |      |
| 71 文件结构-类索引                                   |      |
| 72 文件结构-字段表集合                               |      |
| 73 文件结构-方法表集合                               |      |
| 74 文件结构-属性表集合                               |      |
| 75 字节码指令简介                                    |      |
| 76 字节码与数据类型                                  |      |
| 77 加载指令                                          |      |
| 78 运算指令                                          |      |
| 79 类型转换指令                                      |      |
| 80 对象创建与访问指令                                |      |
| 81 操作树栈指令                                      |      |
| 82 控制转移指令                                      |      |
| 83 方法调用和返回指令                                |      |
| 84 异常处理指令                                      |      |
| 85 同步指令                                          |      |
| 86 类加载机制概述                                    |      |
| 87 类加载时机                                        |      |
| 88 类加载的过程-加载                                 |      |
| 89 类加载的过程-验证                                 |      |
| 90 类加载的过程-准备                                 |      |
| 91 类加载的过程-解析                                 |      |
| 92 类加载的过程-初始化                               |      |
| 93 类加载器                                          |      |
| 94 双亲委派模型                                      |      |
| 95 运行时栈帧结构                                    |      |
| 96 局部变量表                                        |      |
| 97 操作数栈                                          |      |
| 98 动态连接                                          |      |
| 99 方法返回地址和附加信息                            |      |
| 100 方法调用-解析调用                                |      |
| 101 方法调用-静态分派调用                            |      |
| 102 方法调用-动态分派调用                            |      |
| 103 动态类型语言支持                                 |      |
| 104 字节码执行引擎小结                               |      |
| 105 总结与回顾                                       |      |
| 106 happens-before简单概述                           |      |
| 107 重排序问题                                       |      |
| 108 锁的内存语义                                     |      |
| 109 volatile的内存语义                               |      |
| 110 final域内存语义                                  |      |